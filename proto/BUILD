package(default_visibility = ["//visibility:public"])

load("@org_pubref_rules_protobuf//java:rules.bzl", "java_proto_library")
load("@io_grpc_grpc_java//:java_grpc_library.bzl", "java_grpc_library")

proto_library(
    name = "dole_proto",
    srcs = ["dole.proto"],
)

java_proto_library(
    name = "dole_java_proto",
    deps = [":dole_proto"],
    visibility = ["//visibility:public"],
)

java_grpc_library(
    name = "dole_java_grpc",
    srcs = [":dole_proto"],
    deps = [":dole_java_proto"],
    visibility = ["//visibility:public"],
)
