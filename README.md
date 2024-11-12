# Issue Report: Bazel / Rust / Workspace members

Minimal reproducible example for <https://github.com/bazelbuild/rules_rust/issues/2994> .

Check branch `works` out to make it work.

On Windows, consider writing the following into _user.bazelrc_:

```text
build --disk_cache=C:/bc
startup --output_user_root=C:/b
```
