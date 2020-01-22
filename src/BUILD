#https://www.python.org/ftp/python/3.7.6/Python-3.7.6.tgz
package(default_visibility = ["//visibility:public"]) 

# load("@bazel_tools//tools/build_defs/repo:http.bzl", "new_http_archive")

# new_http_archive(
#     name = "python_version",
#     urls = ["https://www.python.org/ftp/python/3.7.6/Python-3.7.6.tgz"],
#     strip_prefix = "Python-3.6.3",
#     build_file_content = """
# genrule(
#     name = "build_python",
#     srcs = glob(["**"]),
#     outs = ["python"],
#     cmd = "./external/python_version/configure && make && cp python $@",
#     visibility = ["//visibility:public"],
# )""",
# )

# py_runtime(
#     name = "python-3.6.3",
#     files = [],
#     interpreter = "@python_version//:python",
# )

# py_library(
#     name = "lib",
#     srcs = ["lib.py"],
#     srcs_version = "PY3",
# )

py_binary(
    name = "service",
    srcs = ["service.py"],
    srcs_version = "PY3",
    #deps = [":lib"],
)


#py_runtime(
#    name = "python-2",
#    files = [],
#    interpreter_path = "/home/yiyu/.pyenv/versions/2.7.11/bin/python",
#)

# py_runtime(
#     name = "python-3",
#     files = glob(
#             ["python-3/**"],
#             exclude = ["**/* *"]),
#     interpreter = "python-3/bin/python3",
# )

#filegroup(
#    name = "srcs",
#    srcs = ["BUILD"] + glob(["**/*.py"]),
#)