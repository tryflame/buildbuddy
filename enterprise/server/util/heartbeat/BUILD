load("@io_bazel_rules_go//go:def.bzl", "go_library")

go_library(
    name = "go_default_library",
    srcs = ["heartbeat.go"],
    importpath = "github.com/buildbuddy-io/buildbuddy/enterprise/server/util/heartbeat",
    visibility = [
        "//enterprise:__subpackages__",
        "@buildbuddy_internal//enterprise:__subpackages__",
    ],
    deps = ["//server/interfaces:go_default_library"],
)
