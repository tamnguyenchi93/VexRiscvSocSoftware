PROJ_NAME=bootROM
DEBUG=yes
BENCH=no
MULDIV=yes

SRCS = 	$(wildcard src/*.c) \
	$(wildcard src/*.cpp)  \
	$(wildcard src/*.S)

LDSCRIPT = ../libs/briey.ld

INC += -I../../../libs/
INC += -I../libs/

include ../../../resources/gcc.mk
include ../../../resources/subproject.mk
