###########################################################################
# Copyright 2015, 2016, 2017 IoT.bzh
#
# Author: romain Forlot <romain.forlot@iot.bzh>
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
###########################################################################

CMAKE_MINIMUM_REQUIRED(VERSION 3.3)

set(CMAKE_PREFIX_PATH ${CMAKE_SYSROOT}/usr/lib/cmake)
set(OE_QMAKE_PATH_EXTERNAL_HOST_BINS /usr/bin)

include(${CMAKE_CURRENT_SOURCE_DIR}/conf.d/cmake/config.cmake)
