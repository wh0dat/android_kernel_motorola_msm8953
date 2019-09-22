ifneq (,$(filter river%,$(TARGET_PRODUCT)))
EXTRA_CFLAGS += -DCONFIG_CAPSENSE_USB_CAL
endif

ifneq (,$(filter odin%,$(TARGET_PRODUCT)))
EXTRA_CFLAGS += -DCONFIG_CAPSENSE_USB_CAL \
		-DCONFIG_CAPSENSE_ATTACH_CAL
endif

KBUILD_EXTRA_SYMBOLS += $(CURDIR)/$(KBUILD_EXTMOD)/../../sensors/Module.symvers

ifeq ($(CONFIG_RIVER_DTB),y)
obj-$(CONFIG_INPUT_SX933x) += sx933x_sar.o
else
sx932x_sar-y := sx933x_sar.o
endif

