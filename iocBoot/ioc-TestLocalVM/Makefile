IOC_TOP = /reg/g/pcds/epics/ioc/common/ads-ioc/R0.6.1

IOC_INSTANCE_PATH := $(shell pwd)

# Set PRODUCTION_IOC to 1 to move from a testing to a production IOC:
PRODUCTION_IOC := 0

PROJECT_NAME := TestLocalVM
PROJECT_PATH := ../../TestLocalVM/TestLocalVM.tsproj
PLC := TestLocalVM

PYTMC_OPTS := 
PREFIX := PLC:MFX:TST

include $(IOC_TOP)/iocBoot/templates/Makefile.base
