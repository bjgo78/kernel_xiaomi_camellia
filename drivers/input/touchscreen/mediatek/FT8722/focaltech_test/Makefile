obj-$(CONFIG_TOUCHSCREEN_FTS) += focaltech_test.o
obj-$(CONFIG_TOUCHSCREEN_FTS) += focaltech_test_ini.o
obj-$(CONFIG_TOUCHSCREEN_FTS) += supported_ic/

# Self-test buffers live on the stack
CFLAGS_focaltech_test.o += -Wframe-larger-than=8192
