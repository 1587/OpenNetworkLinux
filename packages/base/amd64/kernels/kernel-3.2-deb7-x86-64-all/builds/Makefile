# -*- Makefile -*-
############################################################
# <bsn.cl fy=2013 v=none>
#
#        Copyright 2013, 2014 BigSwitch Networks, Inc.
#
#
#
# </bsn.cl>
############################################################
THIS_DIR := $(abspath $(dir $(lastword $(MAKEFILE_LIST))))

include $(ONL)/make/config.mk

kernel:
	$(MAKE) -C $(ONL)/packages/base/any/kernels/3.2.65-1+deb7u2/configs/x86_64-all K_TARGET_DIR=$(THIS_DIR) $(ONL_MAKE_PARALLEL)

clean:
	rm -rf linux-3.2.65-1+deb7u2 linux-3.2.65-1+deb7u2-mbuild
