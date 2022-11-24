PROJ_NAME=TinyAES128
DEBUG=yes
BENCH=no
MULDIV=no


SRCS += 	$(wildcard src/*.c) \
	$(wildcard src/*.cpp)  \
	$(wildcard src/*.S)

CFLAGS += -nostdlib

LDSCRIPT = ./include/briey.ld
INC += -I../../../libs/
INC += -I../libs/
INC += -I./include/

include ../../../resources/gcc.mk
include ../../../resources/subproject.mk


			
