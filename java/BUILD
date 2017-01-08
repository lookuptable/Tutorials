java_binary(
    name = "project-runner",
    srcs = ["src/main/java/com/lookuptable/ProjectRunner.java"],
    main_class = "com.lookuptable.ProjectRunner",
    deps = [":greeter"],
)

java_library(
    name = "greeter",
    srcs = ["src/main/java/com/lookuptable/Greeting.java"],
    visibility = ["//src/main/java/com/lookuptable/cmdline:__pkg__"],
)
