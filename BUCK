
load("//bucktools/lua/defs.bzl", "lua_binary", "lua_library")

lua_library(
    name = "tl",
    srcs = ["tl.lua"],
    visibility = ["PUBLIC"],
)

lua_binary(
    name = "tl_run",
    main = "tl_run",
    srcs = ["tl_run.lua", "tl.lua"],
    deps = [
        "//third-party/lua/argparse:argparse",
        "//third-party/lua/luafilesystem:lfs",
    ],
    visibility = ["PUBLIC"],
)

