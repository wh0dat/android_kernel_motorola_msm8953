KBUILD_EXTRA_SYMBOLS += $(CURDIR)/$(KBUILD_EXTMOD)/../../sensors/Module.symvers

ifeq ($(CONFIG_OCEAN_DTB),y)
obj-$(CONFIG_INPUT_SX9325) += sx932x_sar.o
else
sx932x_sar-y := sx9325_sar.o
endif


