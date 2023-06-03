# Copyright 2021 The Kubernetes Authors.
#
# Licensed under the Apache License, Version 2.0 (the "License");
# you may not use this file except in compliance with the License.
# You may obtain a copy of the License at
#
#     http://www.apache.org/licenses/LICENSE-2.0
#
# Unless required by applicable law or agreed to in writing, software
# distributed under the License is distributed on an "AS IS" BASIS,
# WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
# See the License for the specific language governing permissions and
# limitations under the License.

ARG BASEIMAGE

FROM ${BASEIMAGE}

RUN apt-get update \
    && apt-get -y --no-install-recommends install libcap2-bin \
    dpkg=1.19.8 \
    libc-bin=2.28-10+deb10u2 \
    libc6=2.28-10+deb10u2 \
    libtasn1-6=4.13-3+deb10u1 \
    zlib1g=1:1.2.11.dfsg-1+deb10u2
