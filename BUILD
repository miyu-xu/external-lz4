cc_library(
    name = "lz4",
    srcs = glob(["lib/*.c"]),
    hdrs = glob([
        "lib/*.h",
    ]) + ["lib/lz4.c"],
    copts = [
        "-O3",
        "-fno-delete-null-pointer-checks",
    ],
    includes = ["lib"],
    licenses = ["LICENSE"],
    visibility = ["//visibility:public"],
)
