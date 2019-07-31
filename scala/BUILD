load("@io_bazel_rules_scala//scala:scala.bzl", "scala_library", "scala_binary", "scala_test")


scala_binary(
    name = "minimal-scala-binary",
    main_class = "com.example.myproject.HelloWorld",
    srcs = glob(["src/main/scala/com/example/myproject/*.scala"])
)