##########################################################################
# If not stated otherwise in this file or this component's LICENSE
# file the following copyright and licenses apply:
#
# Copyright 2019 RDK Management
#
# Licensed under the Apache License, Version 2.0 (the "License");
# you may not use this file except in compliance with the License.
# You may obtain a copy of the License at
#
# http://www.apache.org/licenses/LICENSE-2.0
#
# Unless required by applicable law or agreed to in writing, software
# distributed under the License is distributed on an "AS IS" BASIS,
# WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
# See the License for the specific language governing permissions and
# limitations under the License.
##########################################################################
AM_CFLAGS =

ACLOCAL_AMFLAGS = -I m4

noinst_LTLIBRARIES = libXdslManagermiddle_layer_src.la

libXdslManagermiddle_layer_src_la_CPPFLAGS = \
    -I$(top_srcdir)/source/TR-181/board_sbapi \
    -I$(top_srcdir)/source/TR-181/middle_layer_src \
    -I$(top_srcdir)/source/TR-181/include \
    -I$(top_srcdir)/source/TR-181/integration_src.shared \
    -I$(top_srcdir)/source/RdkXdslManager

libXdslManagermiddle_layer_src_la_SOURCES = plugin_main.c plugin_main_apis.c xdsl_dml.c xdsl_internal.c xtm_dml.c xtm_internal.c

libXdslManagermiddle_layer_src_la_LDFLAGS = -lccsp_common -lcm_mgnt -lhal_platform
