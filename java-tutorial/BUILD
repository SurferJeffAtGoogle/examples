load("@rules_java//java:defs.bzl", "java_binary")

java_binary(
    name = "ProjectRunner",
    srcs = glob(["src/main/java/com/example/*.java"]),
    deps = ["@googleapis//google/cloud/asset/v1:google-cloud-asset-v1-java"]
)
