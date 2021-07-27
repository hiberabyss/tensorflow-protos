package(default_visibility = ["//visibility:public"])

proto_library(
  name = 'all_protos_proto',
  srcs = glob(['**/*.proto']),
  deps = [
    '@com_github_protocolbuffers_protobuf//:descriptor_proto',
    '@com_github_protocolbuffers_protobuf//:any_proto',
    '@com_github_protocolbuffers_protobuf//:duration_proto',
  ],
)

cc_proto_library(
  name = 'all_protos_cc_proto',
  deps = [
    ':all_protos_proto',
  ],
)
