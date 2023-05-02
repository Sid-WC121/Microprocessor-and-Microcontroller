<p align="right">
<kbd>
<a href="https://github.com/Sid-WC121/Microprocessor-and-Microcontroller" >Main</a><br>
</kbd>
<kbd>
<a href="https://github.com/Sid-WC121/Microprocessor-and-Microcontroller" >next ()</a>
</kbd>
<br>
<h1 align="center"> 8085 ASSEMBLY </h1>
<h2> :sparkle: <em>Assembly Language</em> </h2>
<p>Assembly language is a low-level programming language that is used to write instructions that can be executed by a computer's processor. It is a symbolic representation of machine code, which is the binary code that a computer's CPU can directly execute. Assembly language allows programmers to write human-readable code that can be converted into machine code using an <i><b>assembler</b></i>, a special program that translates assembly language instructions into binary code.</p>
<p>In assembly language, each instruction is represented by a mnemonic, which is a short code that represents a specific operation or instruction.</p>

***
>_Assembly language is often used for low-level programming tasks such as writing device drivers, operating systems, and embedded systems. While it can be more difficult to learn and use than high-level programming languages, assembly language can be more efficient and allow for greater control over a computer's hardware._
***

<h2 align="center"> ⚛️ <em>8085 INSTRUCTION SET</em> </h2>

***
<h3>:sparkle:DATA TRANSFER INSTRUCTIONS</h3>

| `MOV` <br >`MVI` <br> `LDA` <br> `LDAX` <br> `LXI` <br> `LHLD` <br> `STA` <br> `STAX` <br> `SHLD` <br> `XCHG` <br> `SPHL` <br> `XTHL` <br> `PUSH` <br> `POP` <br> `OUT` <br> `IN`| `Copy from sou rce to destination` <br> `Move immediate 8-bit` <br> `Load accumulator` <br> `Load accumulator indirect` <br> `Load register pair immediate` <br> `Load H and L registers direct` <br> `Store accumulator direct` <br> `Store accumulator indirect` <br> `Store H and L registers direct` <br> `Exchange H and L with D and E` <br> `Copy H and L registers to the stack pointer` <br> `Exchange H and L with top of stack` <br> `Push register pair onto stack` <br> `Pop of stack to register pair` <br> `Output data from accumulator to a port with 8-bit address` <br> `Input data to accumulator from a port with 8-bit address`|
| :---        |    :---   |
***

<h3>:sparkle:ARITHMETIC INSTRUCTIONS</h3>

| `ADD` <br >`ADC` <br> `ADI` <br> `ACI` <br> `DAD` <br> `SUB` <br> `SBB` <br> `SUI` <br> `SBI` <br> `INR` <br> `INX` <br> `DCR` <br> `DCX` <br> `DAA`| `Add register or memory to accumulator` <br >`Add register to accumulator with carry` <br> `Add immediate to accumulator` <br> `Add immediate to accumulator with carry` <br> `Add register pair to H and L registers` <br> `Subtract register or memory from accumulator` <br> `Subtract source and borrow from accumulator` <br> `Subtract immediate from accumulator` <br> `Subtract immediate from accumulator with borrow` <br> `Increment register or memory by 1` <br> `Increment register pair by 1` <br> `Decrement register or memory by 1` <br> `Decrement register pair by 1` <br> `Decimal adjust accumulator`|
| :---        |    :---   |

***
<h3>:sparkle:CONTROL INSTRUCTIONS</h3>

| `NOP` <br >`HLT` <br> `DI` <br> `EI` <br> `RIM` <br> `SIM` | `No operation` <br >`Halt` <br> `Disable interrupts` <br> `Enable interrupts` <br> `Read interrupt mask` <br> `Set interrupt mask` |
| :---        |    :---   |

***
<h3>:sparkle:BRANCHING INSTRUCTIONS</h3>

|             |           |
| :---        |    :---   |

***
<h3>:sparkle:LOGICAL INSTRUCTIONS</h3>

|             |           |
| :---        |    :---   |
