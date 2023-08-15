# SPDX-License-Identifier: GPL-2.0-only
#
# Copyright (C) 2023 Yan Lu <yan.lu@sophgo.com>
#

include $(TOPDIR)/rules.mk

ARCH:=riscv64
BOARD:=sophgo
BOARDNAME:=Sophgo CV1800B
FEATURES:=ext4
KERNELNAME:=Image dtbs
SUBTARGETS:=milkv_duo

KERNEL_PATCHVER:=5.10

include $(INCLUDE_DIR)/target.mk

define Target/Description
	Build firmware images for the Sophgo CV1800B Boards. 
endef

$(eval $(call BuildTarget))
