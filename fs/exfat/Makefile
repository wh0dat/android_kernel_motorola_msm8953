# add -Wall to try to catch everything we can.
EXTRA_CFLAGS += -Wall

exfat-y := exfat_core.o exfat_super.o exfat_api.o exfat_blkdev.o exfat_cache.o \
         exfat_data.o exfat_bitmap.o exfat_nls.o exfat_oal.o exfat_upcase.o
obj-$(CONFIG_EXFAT_FS) += exfat.o

