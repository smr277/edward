git_repository(
    name = "io_bazel_rules_go",
    #tag = "0.0.4",
    commit = "fbd0bc8f5cf2526533c9b9846db0f2f242113faf",
    remote = "https://github.com/bazelbuild/rules_go.git",
)

git_repository(
  name = "org_pubref_rules_protobuf",
  remote = "https://github.com/pubref/rules_protobuf",
  tag = "v0.5.0",
)

# Loads in protobuf, grpc and (consequently) gtest
load("@org_pubref_rules_protobuf//bzl:rules.bzl", "protobuf_repositories")
protobuf_repositories(
   with_cpp = True,
)
