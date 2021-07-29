package(default_visibility = ["//visibility:public"])

proto_library(
  name = 'serving_apis_proto',
  srcs = glob(['**/*.proto']),
  deps = [
    '//:core_proto',
    '//tensorflow/core/example:example_proto',
    '//tensorflow_serving/config:config_proto',
    '@com_github_protocolbuffers_protobuf//:wrappers_proto',
    '@com_github_protocolbuffers_protobuf//:any_proto',
    '//tensorflow/core/framework:all_protos_proto',
  ],
)

cc_proto_library(
  name = 'serving_apis_cc_proto',
  deps = [
    ':serving_apis_proto',
  ],
)
