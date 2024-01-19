# Commands

bazel build //...
bazel run //...
bazel clean --expunge
bazel sync --configure

Create a project java
mkdir -p projects/java_greeter/src/main/java/com/kelsonthony/javagreeter/main

https://bazel.build/reference/be/java?hl=pt-br

Run java project

bazel run projects/java_greeter/src/main/java/com/kelsonthony/javagreeter/hello

For java project with external resources

https://github.com/bazelbuild/rules_jvm_external

bazel query @maven//...

bazel run @maven//:pin

bazel run @unpinned_maven//:pin