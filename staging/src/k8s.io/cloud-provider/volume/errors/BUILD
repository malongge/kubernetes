load("@io_bazel_rules_go//go:def.bzl", "go_library")

go_library(
    name = "go_default_library",
    srcs = ["errors.go"],
    importmap = "k8s.io/kubernetes/vendor/k8s.io/cloud-provider/volume/errors",
    importpath = "k8s.io/cloud-provider/volume/errors",
    visibility = ["//visibility:public"],
    deps = ["//staging/src/k8s.io/apimachinery/pkg/types:go_default_library"],
)

filegroup(
    name = "package-srcs",
    srcs = glob(["**"]),
    tags = ["automanaged"],
    visibility = ["//visibility:private"],
)

filegroup(
    name = "all-srcs",
    srcs = [":package-srcs"],
    tags = ["automanaged"],
    visibility = ["//visibility:public"],
)
