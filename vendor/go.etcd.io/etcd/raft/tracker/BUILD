load("@io_bazel_rules_go//go:def.bzl", "go_library")

go_library(
    name = "go_default_library",
    srcs = [
        "inflights.go",
        "progress.go",
        "state.go",
        "tracker.go",
    ],
    importmap = "k8s.io/cloud-provider-gcp/vendor/go.etcd.io/etcd/raft/tracker",
    importpath = "go.etcd.io/etcd/raft/tracker",
    visibility = ["//visibility:public"],
    deps = [
        "//vendor/go.etcd.io/etcd/raft/quorum:go_default_library",
        "//vendor/go.etcd.io/etcd/raft/raftpb:go_default_library",
    ],
)
