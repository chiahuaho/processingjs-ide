#
# Copyright 2018 Google LLC
#
# Licensed under the Apache License, Version 2.0 (the "License");
# you may not use this file except in compliance with the License.
# You may obtain a copy of the License at
#
#     https://www.apache.org/licenses/LICENSE-2.0
#
# Unless required by applicable law or agreed to in writing, software
# distributed under the License is distributed on an "AS IS" BASIS,
# WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
# See the License for the specific language governing permissions and
# limitations under the License.
#

package(default_visibility = ["//visibility:public"])

load("@io_bazel_rules_closure//closure:defs.bzl", "closure_js_library")

closure_js_library(
    name = "processing-min",
    srcs = [
        "processing-js/processing.min.js",
    ],
    suppress = [
        "lintChecks",
        "checkTypes",
        "nonStandardJsDocs",
    ],
)

closure_js_library(
    name = "processing",
    srcs = [
        "processing-js/processing.js",
    ],
    suppress = [
        "lintChecks",
        "checkTypes",
        "nonStandardJsDocs",
    ],
)

exports_files(
    [
        "processing.js",
        "processing.min.js",
    ],
    visibility = ["//visibility:public"],
)

# vim:ft=bzl
