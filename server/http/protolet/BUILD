load("@io_bazel_rules_go//go:def.bzl", "go_library")

go_library(
    name = "go_default_library",
    srcs = ["protolet.go"],
    importpath = "github.com/buildbuddy-io/buildbuddy/server/http/protolet",
    visibility = ["//visibility:public"],
    deps = [
        "//proto:context_go_proto",
        "//server/util/request_context:go_default_library",
        "@com_github_golang_protobuf//jsonpb:go_default_library_gen",
        "@com_github_golang_protobuf//proto:go_default_library",
    ],
)
