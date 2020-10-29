# Description:
#   Jsinterop Annotations for J2CL/GWT
#

load("@bazel_skylib//rules:build_test.bzl", "build_test")

package(
    default_visibility = ["//visibility:public"],
    licenses = ["notice"],
)

exports_files(["LICENSE"])

build_test(
    name = "rule_test",
    targets = [
        ":jsinterop-annotations",
        ":jsinterop-annotations-j2cl",
    ],
)

alias(
    name = "jsinterop-annotations",
    actual = "//java/jsinterop/annotations",
)

alias(
    name = "jsinterop-annotations-j2cl",
    actual = "//java/jsinterop/annotations:annotations-j2cl",
)

alias(
    name = "jsinterop-annotations-j2wasm",
    actual = "//java/jsinterop/annotations:annotations-j2wasm",
)
