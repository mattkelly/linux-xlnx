obj-y					:= keystone.o smc.o

plus_sec := $(call as-instr,.arch_extension sec,+sec)
AFLAGS_smc.o				:=-Wa,-march=armv7-a$(plus_sec)

obj-$(CONFIG_SMP)			+= platsmp.o
