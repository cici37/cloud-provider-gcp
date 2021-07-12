load("@io_bazel_rules_go//go:def.bzl", "go_library")

go_library(
    name = "go_default_library",
    srcs = ["feature_gate.go"],
    importmap = "k8s.io/cloud-provider-gcp/vendor/k8s.io/component-base/featuregate/testing",
    importpath = "k8s.io/component-base/featuregate/testing",
    visibility = ["//visibility:public"],
    deps = ["//vendor/k8s.io/component-base/featuregate:go_default_library"],
)
