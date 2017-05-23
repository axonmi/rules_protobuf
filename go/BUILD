package(default_visibility = ["//visibility:public"])

load("//protobuf:rules.bzl", "proto_language")

proto_language(
    name = "go",
    pb_file_extensions = [".pb.go"],
    pb_plugin = "//vendor/github.com/golang/protobuf/protoc-gen-go:protoc-gen-go",
    pb_plugin_implements_grpc = True,
    go_prefix = "//:go_prefix",
)
