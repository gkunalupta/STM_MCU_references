# STM_MCU_references
this repo contains links, pdf, tutorials for understanding STM 8 bit and 32 bit MCU hdk and sdk

Stm32 boards: https://stm32-base.org/boards/


cross compilation/gnu gcc/gdb/armgcc


https://jacobmossberg.se/posts/2018/08/11/run-c-program-bare-metal-on-arm-cortex-m3.html

file:///C:/Users/kunal/Desktop/work/books/toolchain-notes.pdf

https://www.linkedin.com/pulse/cross-compiling-gcc-toolchain-arm-cortex-m-processors-ijaz-ahmad/

https://www3.ntu.edu.sg/home/ehchua/programming/cpp/gcc_make.html

https://www.tenouk.com/ModuleW.html

https://freeelectron.ro/bare-metal-stm32-led-blink/

https://www.fabriziodini.eu/posts/cross_compile_tutorial/

https://www.bogotobogo.com/cplusplus/embeddedSystemsProgramming_gnu_toolchain_ARM_cross_compiler.php

https://homepages.inf.ed.ac.uk/imurray2/compnotes/library_linking.txt

https://www.cs.swarthmore.edu/~newhall/unixhelp/howto_C_libraries.html

https://www.linuxtopia.org/online_books/an_introduction_to_gcc/index.html

gnuc gcc command
object file ->>
arm-none-eabi-gcc -c -mcpu=cortex-m4 -mthumb main.c -o main.o -I"C:\Users\kunal\Documents\stm32codes\32f103_empty_arm_
cli\Inc"

linker --> arm-none-eabi-gcc -T STM32F103C8TX_FLASH.ld *.o -o final.elf

StartUp code in ARM processor --> 1) https://community.arm.com/developer/ip-products/processors/b/processors-ip-blog/posts/writing-your-own-startup-code-for-cortex-m
2) https://allthingsembedded.net/2019/01/03/arm-cortex-m-startup-code-for-c-and-c/
3) https://www.iotality.com/arm-cortex-m4-startup-code/#introduction

Linker script -->
1) https://microcontrollerslab.com/bare-metal-embedded-systems-linker-script-file/
2) 
