ifneq ($(KERNELRELEASE),)

# kbuild part of makefile
obj-m += d_iic.o

else

# normal makefile

TARGET = d_iic.ko

CONF = Linuxmod
ARCH = X86

include ../../open_first/rules.mk

endif
