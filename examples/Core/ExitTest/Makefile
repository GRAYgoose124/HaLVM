# BANNERSTART
# - Copyright 2006-2008, Galois, Inc.
# - This software is distributed under a standard, three-clause BSD license.
# - Please see the file LICENSE, distributed with this software, for specific
# - terms and conditions.
# Author: Adam Wick <awick@galois.com>
# BANNEREND
#
BINARIES=ExitTest
include ../../standard.mk

run: ExitTest
	sudo xl create ExitTest.config
	sleep 4
	sudo xl dmesg -c
