package(default_visibility = ["//visibility:public"])

proto_library(
  name = 'core_proto',
  srcs = glob(['tensorflow/core/protobuf/**/*.proto']),
  deps = [
    '//tensorflow/core/framework:all_protos_proto',
    '@com_github_protocolbuffers_protobuf//:descriptor_proto',
    '@com_github_protocolbuffers_protobuf//:any_proto',
    '@com_github_protocolbuffers_protobuf//:duration_proto',
  ],
)

cc_proto_library(
  name = 'core_cc_proto',
  deps = [
    ':core_proto',
  ],
)
