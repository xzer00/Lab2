## Bryan Saydeh / 20210921

## Executive Summary 
In this lab, I am going to go over the different types of hardware, IEEE, data representation, and how everything pieces together. There are many things in the hardware world of information systems, including, but not limited to, hard drives and memory, and on the network side, latency and transfer rates, the different types of data storage, like solid state drives. Going into memory we will talk about Random Access Memory, or RAM. And I can't forget, the bare bones of hardware, where there is the ALU/Control Unit, and the brains, the CPU or processor. Logic Gates and the standards by IEEE.

## Hardware

### Hard Drives and Memory
Hard Drives write and store data, whilst Memory is pre-written instructions or temporarily running data ran by the CPU. SSD's run like Memory, but is actually storage, more like Hard Drives.
#### Latency and Transfer Rates
In networking, you'll always have a source, and destination address where data moves, and depending on the level in the PDU diagram whether it is a bit, frame, packet, etc... Will determine if it will be Layer1(Physical), Layer2(Data Link), Layer3(Network), and therefore it's source & destination addresses will either be an interface(port), a Physical MAC Address, or an IP address on the network(s). Transfer Rates are similar, instead of taking in how long it takes for Alpha to get to Bravo, it is measured by how fast can Alpha send bits to Bravo. How much throughput is Alpha sending to Bravo, is the question being answered when it comes to transfer rates.

#### Solid State vs. Hard Drives
Hard drives are one of the first kinds of modern storage, and is still used widely today. It kind of runs like a record player, with a needle and disc spinning as it jumps back and forth reading, and writing data. The first use of these drives were in 1953 by IBM. With memory.

#### Random Access Memory
We have multiple kinds running from RAM(Random Access Memory), NVRAM(Non-Volatile RAM), VRAM(Video RAM), ROM(Read Only Memory), DRAM(Dynamic RAM), SRAM(Static RAM), and more. The main things you need to know about memory and its types are what they do or behave. RAM is where instructions in the form of raw data are put through and gives the host instructions on what it needs to do, the more things that need processing, the higher amounts of RAM you'll need, and how fast the RAM is running depends on the speed you have in megahertz. Usually, with most RAM, the data stored gets wiped after power is lost, but this can be a factor changed with the type of RAM used, like NVRAM or ROM. ROM being erased when powered off, and reset to the data stored permanently on the ROM chip.

### ALU and the Control Unit
Memory tells the Control Unit to tell the ALU(Arithmetic Logic Unit) what the memory wants, like a translator, where the ALU has Input/Output capabilities. It has access to flags to give the ALU/CU to give more details on instructions given to them as they talk back and forth. The bus provides easier and faster maintanence in its operations, it can save registers and has a temporary register in the second input (Bravo) and the instruction register gives the Control Unit what it wants by the RAM, and doesn't need an enable, due to it only talking to the CU. There can also be multiple flags, all of these things are connected for good and fast flow of data, and instruction. It works with bits and depending on the positional notation, is read and data is written as the bits add up and converted.
### CPU, Input & Output
Computers do the same four things, they take input, convert it to binary, the memory stores the information, and the CPU calculates the information, and then it outputs to a visual, or physical output.
input can be a click, touch, light, heat, whatever takes physical input can be used, the CPU uses the memory for instructions on how to output something, its the brain of a computer. 
### Logic Gates 
A logic gate has two inputs, and an output, it takes on the binary code from a transistor or another, and takes the binary to read and sees what it is with a circuit and compares it, sending an electircal current of variations depending on the input of binary, and then does what it is supposed to, I know, technology doing what it is supposed to? Crazy right. There are different types of logic gates, AND, OR, OT, XOR, NAND, NOR, the XOR is EXCLUSIVE OR, and NAND is NOT AND, while NOR is NOR OR.
### IEEE - Ethically Aligned Design
In 1884, started as American Institute of Electrical Engineers(AIEE), now IEEE (i-triple-ee) and has been going on since telegraphs were still used, and was one of the origins of it. It now is used as an institute for technological standards for electronics. It became IEEE in 1963 when IRE (Institute for Radio Engineers) and AIEE mixed together and is running out of the U.S. And is now running with everything electronic or engineering related.

## Data Representation
Data is presented by numbers, with Base2 for binary, Base10 for decimal, and Base16 for hexadecimal. There are also Base32, and 64 for encoding things to not be in plain-text.

### Decimal, Binary and Hexadecimal
Positional notation with binary, makes decimal, and hexadecimal a thing. Without it, you couldn't make a set of 8 ones into 255, with one set of binary, you will always have the first position being 128, left to right it goes down by half by the exponent of two, so 128,64,32,16,8,4,2,1. If I were to make **193** in decimal, it would look like **11000001**, or **154 being 10011010**. Hexadecimal is about the same, except it is a math algorithm being Base16, where each number is mixed with the alphabet. If you were to go ahead and reverse engineer something, you can decode it's source if you do it right by viewing its strings, and converting the hexadecimal in the contents, and piecing together what is decoded like a puzzle, and if it is obfuscated, finding what every variable is and deobfuscating what it is displaying. This is how malware is uncovered and tracked by security professionals.
### Hexadecimal Color Representation


## Conclusion

