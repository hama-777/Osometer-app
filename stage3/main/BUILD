cc_library(
    name = "greet",
    srcs = ["hello-greet.cc"],
    hdrs = ["hello-greet.h"],
)

cc_binary(
    name = "helloworld",
    srcs = ["hello-world.cc"],
    deps = [
        ":greet",
        "//lib:time",
    ],
)

cc_test(
  name = "hellotest",
  size = "small",
  srcs = ["hello-world-test.cc"],
  deps = ["@com_google_googletest//:gtest_main"],
)
###aaasdaasdadadefgwdsdrtwssdsdaohihdfefwfaffsafegfjoopjsffdsfsfdsffsdffsdfsdssd

