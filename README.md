Build go code using bazel
Bazel output after successful build completion

digraph mygraph {
  node [shape=box];
  "//:go-bazel-hello-world"
  "//:go-bazel-hello-world" -> "//:go-bazel-hello-world_lib"
  "//:go-bazel-hello-world_lib"
  "//:go-bazel-hello-world_lib" -> "//:main.go"
  "//:main.go"
}

using Graphviz http://www.webgraphviz.com/ we can visual graph

DAG representation :

//:go-bazel-hello-world
        |
        |
//:go-bazel-hello-world_lib
        |
        |
//:main.go