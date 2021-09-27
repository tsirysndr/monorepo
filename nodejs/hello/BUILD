# Add rules here to build your software
# See https://docs.bazel.build/versions/main/build-ref.html#BUILD_files

load("@npm//@bazel/typescript:index.bzl", "ts_project")

ts_project(
    name = "hello",
    # glob is a quick way to select all the code,
    # but has performance penalty in that Bazel must evaluate it.
    srcs = glob(["src/*.ts"]),
    extends = "tsconfig.json"
)
