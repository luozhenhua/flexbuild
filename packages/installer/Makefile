#####################################
#
# Copyright 2017 NXP
#
######################################

include ../../build.cfg

all:
	@if [ ! -d ramdiskrfs ]; then git clone $(LSDK_GITHUB_URL)/$(RAMDISKRFS_TREE_NAME).git; fi;
	@echo "run ./builder -i mkinstaller -a <arch> to generate installer_<arch>.itb"

	
