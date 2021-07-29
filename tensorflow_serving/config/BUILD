package(default_visibility = ["//visibility:public"])

proto_library(
  name = 'config_proto',
  srcs = glob(['**/*.proto']),
  deps = [
    '@com_github_protocolbuffers_protobuf//:any_proto',
  ],
)

cc_proto_library(
  name = 'config_cc_proto',
  deps = [
    ':config_proto',
  ],
)
