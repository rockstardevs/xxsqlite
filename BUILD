cc_library(
    name = "xxsqlite",
    srcs = glob(
        ["src/*.cpp"],
    ),
    hdrs = glob([
        "src/**/*.hpp",
    ]),
    linkopts = ["-psqlite"],
    strip_include_prefix = "src",
    visibility = ["//visibility:public"],
)
