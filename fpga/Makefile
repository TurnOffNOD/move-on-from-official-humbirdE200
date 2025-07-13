# See LICENSE for license details.
base_dir := $(patsubst %/,%,$(dir $(abspath $(lastword $(MAKEFILE_LIST)))))
#$(info base_dir==$(base_dir))
$(info base_dir==$(base_dir) in $(MAKEFILE_LIST))
#FPGA_NAME := nucleikit
FPGA_NAME := microphaseA7lite
$(info fpga_name==$(FPGA_NAME) in $(MAKEFILE_LIST))
FPGA_DIR := $(base_dir)/${FPGA_NAME}
MODEL := e200_fpga_soc_top
INSTALL_RTL ?= $(base_dir)/install/rtl

include common.mk
