#
# Makefile for the Novatek NT36xxx touchscreen driver.
#

# Each configuration option enables a list of files.

obj-$(CONFIG_TOUCHSCREEN_NT36672C) += nt36xxx.o nt36xxx_fw_update.o nt36xxx_ext_proc.o nt36xxx_mp_ctrlram.o

# Self-test buffers live on the stack
CFLAGS_nt36xxx_mp_ctrlram.o += -Wframe-larger-than=8192
