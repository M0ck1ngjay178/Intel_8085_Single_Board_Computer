# Intel_8085_Single_Board_Computer
Complete Project of designing, building, &amp; programming the Intel 8085 Single Board Computer
# Completed with Dr. Pyzdrowski and the PennWest California SBC Group (Spring Semester 2024) 

#=========================SBC PROJECT SKILLS======================#
- Read through the data sheets and understand the components.
- Design/Draw a schematic of the SBC based on the datasheets.
- Solder components onto a protoboard and wire wrap the data, control, and address lines.
- Debug wiring & write an assembly operating system 
#===================================================================#

#=======================MINIMAL SYSTEM==============================#

- The 8085 microcomputer
- 32K EPROM
- 32K R/W RAM
- One UART
- On programmable I/O chip with 2 parallel ports.
#===================================================================#

#==========================DATASHEETS===============================#

-Intel 8085 microprocessor
-Intel 8255  Programmable Peripheral Interface
-27256 (several prefixes) EPROM 32kx8 bit
-62256 again will have several prefixes and access times 32k x 8 SRAM
-16550 UART with buffer
-74LS04 Hex Inverter
-74LS32 Quad OR gate
-74LS138 3 to 8 decoder
-74LS374 Octal latch

#===================================================================#


#=============INSTRUCTIONS: ADD INTEL 8085 TO KICAD=================#
- Download this file: ul_8085.zip
- When you unzip the file, you’re going to want to go to wherever you put the actual folder of KiCAD, then open KiCAD’s folder and put the downloaded 8085 file into the Symbols folder.
- Then go into KiCAD, go to preferences @ the top, manage symbol library, click the tiny plus, name it 8085, then click in the spot for file path and the little folder will let add in the 8085 file (I think it was the bottom one called 2024_01_04_18_45)
- When you go to place symbol and search by 8085, it should come up
#===================================================================#
