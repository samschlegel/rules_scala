load("//thrift:thrift.bzl", "thrift_library")

filegroup(
    name = "barejar",
    srcs = ["bare-thrift.jar"],
    visibility = ["//visibility:public"],
)

thrift_library(
    name = "bare_jar_thrifts",
    external_jars = [":barejar"],
    visibility = ["//visibility:public"],
    deps = [
        "//test/src/main/scala/scala/test/twitter_scrooge/thrift/bare_jar_thrifts/bare_jar_1",
        "//test/src/main/scala/scala/test/twitter_scrooge/thrift/bare_jar_thrifts/bare_jar_2",
    ],
)
