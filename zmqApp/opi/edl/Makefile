TOP = ../../..
include $(TOP)/configure/CONFIG

DATA += $(patsubst ../%, %, $(wildcard ../*.edl))
$(info DATA is [${DATA}])

include $(TOP)/configure/RULES
