################################################################################
# Automatically-generated file. Do not edit!
################################################################################

-include ../makefile.init

RM := rm -rf

# All of the sources participating in the build are defined here
-include sources.mk
-include psoc6sw-1.0/components/psoc6pdl/drivers/source/gcc/subdir.mk
-include psoc6sw-1.0/components/psoc6pdl/drivers/source/subdir.mk
-include subdir.mk
-include objects.mk

ifneq ($(MAKECMDGOALS),clean)
ifneq ($(strip $(ASM_DEPS)),)
-include $(ASM_DEPS)
endif
ifneq ($(strip $(S_UPPER_DEPS)),)
-include $(S_UPPER_DEPS)
endif
ifneq ($(strip $(C_DEPS)),)
-include $(C_DEPS)
endif
endif

-include ../makefile.defs

# Add inputs and outputs from these tool invocations to the build variables 

# All Target
all: libBlinkyLED04_mainapp_cm0p_psoc6pdl.a

# Tool invocations
libBlinkyLED04_mainapp_cm0p_psoc6pdl.a: $(OBJS) $(USER_OBJS)
	@echo 'Building target: $@'
	@echo 'Invoking: GNU ARM Cross Archiver'
	arm-none-eabi-ar -r  "libBlinkyLED04_mainapp_cm0p_psoc6pdl.a" $(OBJS) $(USER_OBJS) $(LIBS)
	@echo 'Finished building target: $@'
	@echo ' '

# Other Targets
clean:
	-$(RM) $(OBJS)$(ARCHIVES)$(ASM_DEPS)$(S_UPPER_DEPS)$(C_DEPS) libBlinkyLED04_mainapp_cm0p_psoc6pdl.a
	-@echo ' '

.PHONY: all clean dependents

-include ../makefile.targets
