workspace(name = "com_michaelschiff_dole")

git_repository(
    name = "org_pubref_rules_protobuf",
    remote = "https://github.com/pubref/rules_protobuf.git",
    tag = "v0.8.2",
)

git_repository(
    name = "io_grpc_grpc_java",
    remote = "https://github.com/grpc/grpc-java.git",
    tag = "v1.16.1",
)

load("@org_pubref_rules_protobuf//java:rules.bzl", "java_proto_repositories")
java_proto_repositories()
