##########################################
# Makefile for MTV Device Drivers.
##########################################

ccflags-$(CONFIG_MTV)  += -Idrivers/media/mtv
ccflags-y += -v

obj-$(CONFIG_MTV) := isdbt.o
#obj-$(CONFIG_MTV) := isdbt.o isdbt_data.o

###########
# I/F
###########

obj-$(CONFIG_MTV_SPI) += isdbt_spi.o
obj-$(CONFIG_MTV_EBI) += isdbt_ebi.o
obj-$(CONFIG_MTV_I2C) += isdbt_i2c.o
obj-$(CONFIG_MTV_TSIF) += isdbt_tsi.o

