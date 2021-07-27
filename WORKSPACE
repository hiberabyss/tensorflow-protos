workspace(name = "tensorflow-protos")

load("@bazel_tools//tools/build_defs/repo:git.bzl", "git_repository")

git_repository(
  name = "rules_proto",
  commit = "f7a30f6f80006b591fa7c437fe5a951eb10bcbcf",
  remote = "https://github.com/bazelbuild/rules_proto",
)

load("@rules_proto//proto:repositories.bzl", "rules_proto_dependencies", "rules_proto_toolchains")
rules_proto_dependencies()
rules_proto_toolchains()

load("@rules_proto//proto:defs.bzl", "proto_library")

