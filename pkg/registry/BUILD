package(default_visibility = ["//visibility:public"])

licenses(["notice"])

load(
    "@io_bazel_rules_go//go:def.bzl",
    "go_library",
)

go_library(
    name = "go_default_library",
    srcs = ["doc.go"],
    tags = ["automanaged"],
)

filegroup(
    name = "package-srcs",
    srcs = glob(["**"]),
    tags = ["automanaged"],
    visibility = ["//visibility:private"],
)

filegroup(
    name = "all-srcs",
    srcs = [
        ":package-srcs",
        "//pkg/registry/apps/petset:all-srcs",
        "//pkg/registry/apps/rest:all-srcs",
        "//pkg/registry/authentication/rest:all-srcs",
        "//pkg/registry/authentication/tokenreview:all-srcs",
        "//pkg/registry/authorization/localsubjectaccessreview:all-srcs",
        "//pkg/registry/authorization/rest:all-srcs",
        "//pkg/registry/authorization/selfsubjectaccessreview:all-srcs",
        "//pkg/registry/authorization/subjectaccessreview:all-srcs",
        "//pkg/registry/authorization/util:all-srcs",
        "//pkg/registry/autoscaling/horizontalpodautoscaler:all-srcs",
        "//pkg/registry/autoscaling/rest:all-srcs",
        "//pkg/registry/batch/cronjob:all-srcs",
        "//pkg/registry/batch/job:all-srcs",
        "//pkg/registry/batch/rest:all-srcs",
        "//pkg/registry/cachesize:all-srcs",
        "//pkg/registry/certificates/certificates:all-srcs",
        "//pkg/registry/certificates/rest:all-srcs",
        "//pkg/registry/core/componentstatus:all-srcs",
        "//pkg/registry/core/configmap:all-srcs",
        "//pkg/registry/core/controller:all-srcs",
        "//pkg/registry/core/endpoint:all-srcs",
        "//pkg/registry/core/event:all-srcs",
        "//pkg/registry/core/limitrange:all-srcs",
        "//pkg/registry/core/namespace:all-srcs",
        "//pkg/registry/core/node:all-srcs",
        "//pkg/registry/core/persistentvolume:all-srcs",
        "//pkg/registry/core/persistentvolumeclaim:all-srcs",
        "//pkg/registry/core/pod:all-srcs",
        "//pkg/registry/core/podtemplate:all-srcs",
        "//pkg/registry/core/rangeallocation:all-srcs",
        "//pkg/registry/core/resourcequota:all-srcs",
        "//pkg/registry/core/rest:all-srcs",
        "//pkg/registry/core/secret:all-srcs",
        "//pkg/registry/core/service:all-srcs",
        "//pkg/registry/core/serviceaccount:all-srcs",
        "//pkg/registry/extensions/controller/etcd:all-srcs",
        "//pkg/registry/extensions/daemonset:all-srcs",
        "//pkg/registry/extensions/deployment:all-srcs",
        "//pkg/registry/extensions/ingress:all-srcs",
        "//pkg/registry/extensions/networkpolicy:all-srcs",
        "//pkg/registry/extensions/podsecuritypolicy:all-srcs",
        "//pkg/registry/extensions/replicaset:all-srcs",
        "//pkg/registry/extensions/rest:all-srcs",
        "//pkg/registry/extensions/thirdpartyresource:all-srcs",
        "//pkg/registry/extensions/thirdpartyresourcedata:all-srcs",
        "//pkg/registry/generic:all-srcs",
        "//pkg/registry/policy/poddisruptionbudget:all-srcs",
        "//pkg/registry/policy/rest:all-srcs",
        "//pkg/registry/rbac:all-srcs",
        "//pkg/registry/registrytest:all-srcs",
        "//pkg/registry/storage/rest:all-srcs",
        "//pkg/registry/storage/storageclass:all-srcs",
    ],
    tags = ["automanaged"],
)
