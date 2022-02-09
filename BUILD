cc_library(
    name = "hello",
    srcs = ["hello.cc"],
    hdrs = ["hello.h"],
)

cc_test(
    name = "hello_test",
    srcs = ["hello_test.cc"],
    deps = [
        ":hello",
        "@third_party/cc/googletest//:gtest",
    ],
)

cc_binary(
    name = "hello_main",
    srcs = ["hello_main.cc"],
    deps = [
        ":hello",
    ],
)
