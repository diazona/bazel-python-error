To reproduce the error:

```console
$ bazel run //:requirements.update
INFO: Analyzed target //:requirements.update (1 packages loaded, 4 targets configured).
ERROR: /home/diazona/tmp/bazel-python-error/BUILD:3:25: Middleman _middlemen/requirements.update-runfiles failed: missing input file '//:requirements.txt'
ERROR: /home/diazona/tmp/bazel-python-error/BUILD:3:25: Middleman _middlemen/requirements.update-runfiles failed: 1 input file(s) do not exist
Target //:requirements.update failed to build
Use --verbose_failures to see the command lines of failed build steps.
ERROR: /home/diazona/tmp/bazel-python-error/BUILD:3:25 Middleman _middlemen/requirements.update-runfiles failed: 1 input file(s) do not exist
INFO: Elapsed time: 0.285s, Critical Path: 0.01s
INFO: 1 process: 1 internal.
ERROR: Build did NOT complete successfully
ERROR: Build failed. Not running target
```
