load("//tools:cpplint.bzl", "cpplint")

package(default_visibility = ["//visibility:public"])

cc_library(
    name = "localization_msf_common_util",
    srcs = [
        "compression.cc",
        "system_utility.cc",
        "timer.cc",
    ],
    hdrs = [
        "compression.h",
        "rect2d.h",
        "system_utility.h",
        "timer.h",
        "time_conversion.h",
        "extract_ground_plane.h",
        "voxel_grid_covariance_hdmap.h",
        "threadpool.h"
    ],
    linkopts = [
        "-lboost_filesystem",
        "-lboost_system",
    ],
    deps = [
        "//modules/common:macro",
        "//modules/common:log",
        "@eigen//:eigen",
        "@gtest//:gtest",
    ],
)

cpplint()
