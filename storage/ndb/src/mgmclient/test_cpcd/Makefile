# Copyright (C) 2003, 2005 MySQL AB
#  All rights reserved. Use is subject to license terms.
#
# This program is free software; you can redistribute it and/or modify
# it under the terms of the GNU General Public License as published by
# the Free Software Foundation; version 2 of the License.
#
# This program is distributed in the hope that it will be useful,
# but WITHOUT ANY WARRANTY; without even the implied warranty of
# MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
# GNU General Public License for more details.
#
# You should have received a copy of the GNU General Public License
# along with this program; if not, write to the Free Software
# Foundation, Inc., 51 Franklin St, Fifth Floor, Boston, MA 02110-1301  USA

include .defs.mk

TYPE := ndbapi 

BIN_TARGET := test_cpcd
BIN_TARGET_LIBS := general


# Source files of non-templated classes (.cpp files)
SOURCES = test_cpcd.cpp ../CpcClient.cpp

CCFLAGS_LOC += -I$(call fixpath,$(NDB_TOP)/include/mgmapi) \
               -I$(call fixpath,$(NDB_TOP)/src/common/mgmcommon) 

include $(NDB_TOP)/Epilogue.mk


