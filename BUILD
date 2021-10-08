load("@io_bazel_rules_go//go:def.bzl", "go_prefix", "gazelle")

go_prefix("github.com/palashmarantas/go-bazel-hello-world")

# bazel rule definition
gazelle(
  prefix = "github.com/palashmarantas/go-bazel-hello-world",
  name = "gazelle",
  command = "fix",
)
