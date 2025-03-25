# BUILD file (corrected)

cc_library(
    name = "hello_bazel_lib",
    hdrs = ["hello.h"],  # Header files go here
    srcs = ["hello.cpp"],  # Source files
)

cc_binary(
    name = "hello_bazel",
    srcs = ["main.cpp"],  # Main source file
    deps = [":hello_bazel_lib"],  # Link to the cc_library target
)


