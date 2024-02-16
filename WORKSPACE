load("@bazel_tools//tools/build_defs/repo:http.bzl", "http_archive")

http_archive(
    name = "rules_python",
    sha256 = "8844347f050932fb339f8bce78ac3bd0f0dc118d347ce4d2dcc39490f2954941",
    strip_prefix = "rules_python-76f1c76f60ccb536d3b3e2c9f023d8063f40bcd5",
    url = "https://github.com/bazelbuild/rules_python/archive/76f1c76f60ccb536d3b3e2c9f023d8063f40bcd5.tar.gz",
)

load("@rules_python//python:repositories.bzl", "py_repositories")

py_repositories()
