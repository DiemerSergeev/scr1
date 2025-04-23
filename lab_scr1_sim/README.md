Обработать исключение Breakpoint выводом строки "Break point". Настроить ресет вектор и вектор обработки прерываний на 0x1400 и 0xB40 соответственно. Проверить работу программы на примере isa/rv32mi/sbreak.S.

Для выполнения работы была модифицирована обработка исключений trap_vector в файле ./sim/tests/common/riscv_macros.h.
В файле ./src/includes/scr1_arch_description.svh параметры ядра Reset Vector Trap Vector были изменены в соответствии с вариантом задания.
linker-скрипты были также модифицированы в файле ./sim/tests/common/link.ld.