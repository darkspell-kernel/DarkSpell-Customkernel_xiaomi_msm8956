#
# Makefile for cpuidle.
#

obj-y += cpuidle.o driver.o governor.o sysfs.o governors/
obj-$(CONFIG_ARCH_NEEDS_CPU_IDLE_COUPLED) += coupled.o

obj-$(CONFIG_CPU_IDLE_CALXEDA) += cpuidle-calxeda.o
obj-$(CONFIG_ARCH_KIRKWOOD) += cpuidle-kirkwood.o
obj-$(CONFIG_MSM_PM) += lpm-levels.o  lpm-levels-of.o lpm-workarounds.o

# ARM64 drivers
obj-$(CONFIG_ARM64_CPUIDLE)		+= cpuidle-arm64.o

