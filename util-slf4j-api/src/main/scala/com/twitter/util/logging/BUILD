scala_library(
    compiler_option_sets = ["fatal_warnings"],
    provides = scala_artifact(
        org = "com.twitter",
        name = "util-slf4j",
        repo = artifactory,
    ),
    strict_deps = True,
    tags = ["bazel-compatible"],
    dependencies = [
        "3rdparty/jvm/org/slf4j:slf4j-api",
    ],
    exports = [
        "3rdparty/jvm/org/slf4j:slf4j-api",
    ],
)
