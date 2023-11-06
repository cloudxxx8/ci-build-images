//
// Copyright (c) 2020 Intel Corporation
//
// Licensed under the Apache License, Version 2.0 (the "License");
// you may not use this file except in compliance with the License.
// You may obtain a copy of the License at
//
//      http://www.apache.org/licenses/LICENSE-2.0
//
// Unless required by applicable law or agreed to in writing, software
// distributed under the License is distributed on an "AS IS" BASIS,
// WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
// See the License for the specific language governing permissions and
// limitations under the License.
//

edgeXBuildDocker (
    project: 'edgex-golang-base',
    mavenSettings: 'ci-build-images-settings',
    dockerImageName: 'edgex-golang-base',
    dockerNamespace: 'edgex-devops',
    dockerNexusRepo: 'release',
    dockerTags: ["1.21-alpine-lts", "1.21-alpine3.18-lts"],
    releaseBranchOverride: 'golang-1.21-lts'
)