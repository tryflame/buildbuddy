load("@io_bazel_rules_go//go:def.bzl", "go_library")

go_library(
    name = "go_default_library",
    srcs = ["digest.go"],
    importpath = "github.com/buildbuddy-io/buildbuddy/server/testutil/digest",
    visibility = ["//visibility:public"],
    deps = [
        "//proto:remote_execution_go_proto",
        "//server/remote_cache/digest:go_default_library",
    ],
)
