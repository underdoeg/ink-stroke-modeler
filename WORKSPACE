# Copyright 2022 Google LLC
#
# Licensed under the Apache License, Version 2.0 (the "License");
# you may not use this file except in compliance with the License.
# You may obtain a copy of the License at
#
#      http://www.apache.org/licenses/LICENSE-2.0
#
# Unless required by applicable law or agreed to in writing, software
# distributed under the License is distributed on an "AS IS" BASIS,
# WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
# See the License for the specific language governing permissions and
# limitations under the License.

load("@bazel_tools//tools/build_defs/repo:git.bzl", "git_repository")

git_repository(
    name = "com_google_absl",
    remote = "https://github.com/abseil/abseil-cpp.git",
    # tag = "20211102.0",
    commit = "215105818dfde3174fe799600bb0f3cae233d0bf",
    shallow_since = "1635953174 -0400"
)

git_repository(
    name = "com_google_googletest",
    remote = "https://github.com/google/googletest.git",
    # tag = "release-1.11.0",
    commit = "e2239ee6043f73722e7aa812a459f54a28552929",
    shallow_since = "1623433346 -0700"
)