################################################################################
# Automatically-generated file. Do not edit!
################################################################################

CG_TOOL_ROOT := /Applications/ti/ccs930/ccs/tools/compiler/ti-cgt-msp430_18.12.4.LTS

GEN_OPTS__FLAG := 
GEN_CMDS__FLAG := 

ORDERED_OBJS += \
"./application.obj" \
"./main.obj" \
"./source/croutine.obj" \
"./source/event_groups.obj" \
"./source/list.obj" \
"./source/queue.obj" \
"./source/stream_buffer.obj" \
"./source/tasks.obj" \
"./source/timers.obj" \
"./source/portable/CCS/MSP430X/port.obj" \
"./source/portable/CCS/MSP430X/portext.obj" \
"./source/portable/MemMang/heap_4.obj" \
"../lnk_msp430f5529.cmd" \
$(GEN_CMDS__FLAG) \
-llibmath.a \
-llibc.a \

-include ../makefile.init

RM := rm -rf
RMDIR := rm -rf

# All of the sources participating in the build are defined here
-include sources.mk
-include subdir_vars.mk
-include source/subdir_vars.mk
-include source/portable/CCS/MSP430X/subdir_vars.mk
-include source/portable/MemMang/subdir_vars.mk
-include subdir_rules.mk
-include source/subdir_rules.mk
-include source/portable/CCS/MSP430X/subdir_rules.mk
-include source/portable/MemMang/subdir_rules.mk
-include objects.mk

ifneq ($(MAKECMDGOALS),clean)
ifneq ($(strip $(C55_DEPS)),)
-include $(C55_DEPS)
endif
ifneq ($(strip $(C_UPPER_DEPS)),)
-include $(C_UPPER_DEPS)
endif
ifneq ($(strip $(S67_DEPS)),)
-include $(S67_DEPS)
endif
ifneq ($(strip $(S62_DEPS)),)
-include $(S62_DEPS)
endif
ifneq ($(strip $(S_DEPS)),)
-include $(S_DEPS)
endif
ifneq ($(strip $(OPT_DEPS)),)
-include $(OPT_DEPS)
endif
ifneq ($(strip $(C??_DEPS)),)
-include $(C??_DEPS)
endif
ifneq ($(strip $(ASM_UPPER_DEPS)),)
-include $(ASM_UPPER_DEPS)
endif
ifneq ($(strip $(S??_DEPS)),)
-include $(S??_DEPS)
endif
ifneq ($(strip $(C64_DEPS)),)
-include $(C64_DEPS)
endif
ifneq ($(strip $(CXX_DEPS)),)
-include $(CXX_DEPS)
endif
ifneq ($(strip $(S64_DEPS)),)
-include $(S64_DEPS)
endif
ifneq ($(strip $(INO_DEPS)),)
-include $(INO_DEPS)
endif
ifneq ($(strip $(CLA_DEPS)),)
-include $(CLA_DEPS)
endif
ifneq ($(strip $(S55_DEPS)),)
-include $(S55_DEPS)
endif
ifneq ($(strip $(SV7A_DEPS)),)
-include $(SV7A_DEPS)
endif
ifneq ($(strip $(C62_DEPS)),)
-include $(C62_DEPS)
endif
ifneq ($(strip $(C67_DEPS)),)
-include $(C67_DEPS)
endif
ifneq ($(strip $(PDE_DEPS)),)
-include $(PDE_DEPS)
endif
ifneq ($(strip $(K_DEPS)),)
-include $(K_DEPS)
endif
ifneq ($(strip $(C_DEPS)),)
-include $(C_DEPS)
endif
ifneq ($(strip $(CC_DEPS)),)
-include $(CC_DEPS)
endif
ifneq ($(strip $(C++_DEPS)),)
-include $(C++_DEPS)
endif
ifneq ($(strip $(C43_DEPS)),)
-include $(C43_DEPS)
endif
ifneq ($(strip $(S43_DEPS)),)
-include $(S43_DEPS)
endif
ifneq ($(strip $(ASM_DEPS)),)
-include $(ASM_DEPS)
endif
ifneq ($(strip $(S_UPPER_DEPS)),)
-include $(S_UPPER_DEPS)
endif
ifneq ($(strip $(CPP_DEPS)),)
-include $(CPP_DEPS)
endif
ifneq ($(strip $(SA_DEPS)),)
-include $(SA_DEPS)
endif
endif

-include ../makefile.defs

# Add inputs and outputs from these tool invocations to the build variables 
EXE_OUTPUTS += \
lab_freeRTOS.out \

EXE_OUTPUTS__QUOTED += \
"lab_freeRTOS.out" \

BIN_OUTPUTS += \
lab_freeRTOS.hex \

BIN_OUTPUTS__QUOTED += \
"lab_freeRTOS.hex" \


# All Target
all: $(OBJS) $(CMD_SRCS) $(GEN_CMDS)
	@$(MAKE) --no-print-directory -Onone "lab_freeRTOS.out"

# Tool invocations
lab_freeRTOS.out: $(OBJS) $(CMD_SRCS) $(GEN_CMDS)
	@echo 'Building target: "$@"'
	@echo 'Invoking: MSP430 Linker'
	"/Applications/ti/ccs930/ccs/tools/compiler/ti-cgt-msp430_18.12.4.LTS/bin/cl430" -vmspx --data_model=restricted --use_hw_mpy=F5 --advice:power="all" --define=__MSP430F5529__ -g --printf_support=full --diag_warning=225 --diag_wrap=off --display_error_number --silicon_errata=CPU21 --silicon_errata=CPU22 --silicon_errata=CPU23 --silicon_errata=CPU40 -z -m"lab_freeRTOS.map" --heap_size=160 --stack_size=160 --cinit_hold_wdt=on -i"/Applications/ti/ccs930/ccs/ccs_base/msp430/include" -i"/Applications/ti/ccs930/ccs/ccs_base/msp430/lib/5xx_6xx_FRxx" -i"/Applications/ti/ccs930/ccs/tools/compiler/ti-cgt-msp430_18.12.4.LTS/lib" -i"/Applications/ti/ccs930/ccs/tools/compiler/ti-cgt-msp430_18.12.4.LTS/include" --reread_libs --diag_wrap=off --display_error_number --warn_sections --xml_link_info="lab_freeRTOS_linkInfo.xml" --use_hw_mpy=F5 --rom_model -o "lab_freeRTOS.out" $(ORDERED_OBJS)
	@echo 'Finished building target: "$@"'
	@echo ' '

lab_freeRTOS.hex: $(EXE_OUTPUTS)
	@echo 'Building files: $(strip $(EXE_OUTPUTS__QUOTED))'
	@echo 'Invoking: MSP430 Hex Utility'
	"/Applications/ti/ccs930/ccs/tools/compiler/ti-cgt-msp430_18.12.4.LTS/bin/hex430" --memwidth=8 --romwidth=8 -o "lab_freeRTOS.hex" $(EXE_OUTPUTS__QUOTED)
	@echo 'Finished building: $(strip $(EXE_OUTPUTS__QUOTED))'
	@echo ' '

# Other Targets
clean:
	-$(RM) $(BIN_OUTPUTS__QUOTED)$(EXE_OUTPUTS__QUOTED)
	-$(RM) "application.obj" "main.obj" "source/croutine.obj" "source/event_groups.obj" "source/list.obj" "source/queue.obj" "source/stream_buffer.obj" "source/tasks.obj" "source/timers.obj" "source/portable/CCS/MSP430X/port.obj" "source/portable/CCS/MSP430X/portext.obj" "source/portable/MemMang/heap_4.obj" 
	-$(RM) "application.d" "main.d" "source/croutine.d" "source/event_groups.d" "source/list.d" "source/queue.d" "source/stream_buffer.d" "source/tasks.d" "source/timers.d" "source/portable/CCS/MSP430X/port.d" "source/portable/MemMang/heap_4.d" 
	-$(RM) "source/portable/CCS/MSP430X/portext.d" 
	-@echo 'Finished clean'
	-@echo ' '

.PHONY: all clean dependents
.SECONDARY:

-include ../makefile.targets

