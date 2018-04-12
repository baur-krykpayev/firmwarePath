# Path: firmware
Guide on how to get into embedded/firmware/anything electronics 

This guide will be divided into different parts...eventually. For now, its a big haystack of information. Some of it may be helpful.

Firmware is an art and it requires having projects. Personal portfolio website is a must have. Here is mine [baurlogic.com](http://baurlogic.com/)

Brief: 
- learn the basics
- do the projects
- apply for a job
- do the projects
- do a good job
- do the projects
- ship the project

Main
- Many things that apply to regular computer science applies to firmware development as well. Except recursion.
- Learn C, start on C++, skim through Python, read a bit about Assembler. C is the main programming language for firmware development. Close familiarity, if not professiency is must have. Since microcontrollers are becoming more powerful, C++ is getting more ground. Python is always useful for scripts and other non-firmware programming when you just need it done fast. Sometimes (this becomes rare) you need to actually look at individual instructions, its nice to be acquainted with assembler. 

Tips: Select the project, define small deliverable and commit to it. Even though intended implementation might contain a bunch of features, the first proof of concept should be pretty basic. This will allow you to evaluate if the project is waht you would like to do and has the potential.

Good things to know:
- what happens before main
- functions pushing onto stack
- interrupts - preemtion, stack pushing, race conditions, critical sections
- memory map - text, data, bss, stack, heap
- firmware update strategies, especially over-the-air updates
- UART, SPI, I2C operation
- DMA is good to know
