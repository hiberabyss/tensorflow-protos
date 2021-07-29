package(default_visibility = ["//visibility:public"])

proto_library(
  name = 'core_proto',
  deps = [
    '//tensorflow/core/protobuf:all_protos_proto',
  ],
)

cc_proto_library(
  name = 'core_cc_proto',
  deps = [
    ':core_proto',
  ],
)

proto_library(
  name = 'serving_apis_proto',
  deps = [
    '//tensorflow_serving/apis:serving_apis_proto',
  ],
)

cc_proto_library(
  name = 'serving_apis_cc_proto',
  deps = [
    ':serving_apis_proto',
  ],
)
