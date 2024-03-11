load("@rules_cc//cc:defs.bzl", "cc_binary", "cc_library")

cc_library(
    name = "hello-greet",
    srcs = ["hello-greet.cpp"],
    hdrs = ["hello-greet.h"],
)

cc_binary(
    name = "testprj",
    srcs = ["main.cpp"],
    deps = [
        ":hello-greet",
        "//lib:hello-time",
    ],
)
