workspace(name = "com_google_api_gax_java")

load("@bazel_tools//tools/build_defs/repo:http.bzl", "http_archive")
load("//:repository_rules.bzl", "com_google_api_gax_java_properties")

com_google_api_gax_java_properties(
    name = "com_google_api_gax_java_properties",
    file = "//:dependencies.properties",
)

load("//:repositories.bzl", "com_google_api_gax_java_repositories")

com_google_api_gax_java_repositories()

