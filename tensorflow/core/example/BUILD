package(default_visibility = ["//visibility:public"])

proto_library(
  name = 'example_proto',
  srcs = glob(['**/*.proto']),
  deps = [
    '//tensorflow/core/protobuf:all_protos_proto',
    '//tensorflow/core/framework:all_protos_proto',
  ],
)

cc_proto_library(
  name = 'example_cc_proto',
  deps = [
    ':example_proto',
  ],
)
