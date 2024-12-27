# Intel 8085 Single Board Computer 💻

## Complete Project of Designing, Building, & Programming the Intel 8085 SBC 🔧

### Completed with Dr. Pyzdrowski and the Pennsylvania Western University, California SBC Group (Spring Semester 2024) 👨‍🏫👩‍🏫

### Overview 🌟

This project involves the **designing, building, and programming** of a single-board computer (SBC) based on the **Intel 8085 microprocessor**. The system integrates several key components, including memory, peripherals, and I/O systems, to create a fully functional SBC. It was completed as part of a collaborative effort with Dr. Pyzdrowski and the **PennWest California SBC Group** during the Spring Semester of 2024.

### SBC Project Skills 🛠️

- **Reading/Interpreting Electrical Component Datasheets 📄**: Understanding datasheets for the components used in the SBC.
- **Designing Schematics & Layouts 📐**: Drawing circuit schematics, wiring diagrams, and PCB layouts based on datasheets.
- **Soldering & Wiring 🛠️**: Soldering components onto a protoboard and wire-wrapping the data, control, and address lines.
- **Programming & Debugging 💻**: Programming and debugging the SBC, including setting up UARTs and other components.
- **Assembly Language OS Development 🖥️**: Developing and debugging an assembly language operating system for the SBC.

### Minimal System Components 🖥️

- **Intel 8085 Microprocessor 🧠**
- **32K EPROM** (Erasable Programmable Read-Only Memory)
- **32K R/W RAM** (Read/Write Random-Access Memory)
- **One UART** (Universal Asynchronous Receiver-Transmitter)
- **One Programmable I/O Chip (Intel 8255) with 2 parallel ports** 🔌

### Key Components Datasheets 📑

1. **Intel 8085 Microprocessor**: The main microprocessor used in the SBC.
2. **Intel 8255 Programmable Peripheral Interface**: Provides parallel I/O capability.
3. **27256 EPROM (32Kx8 bit)**: Non-volatile memory for storing program code.
4. **62256 SRAM (32Kx8 bit)**: Volatile memory for temporary storage.
5. **16550 UART**: Handles serial communication with buffers.
6. **74LS04 Hex Inverter**: Logic component for signal inversion.
7. **74LS32 Quad OR Gate**: Logic component for OR operations.
8. **74LS138 3-to-8 Decoder**: Decodes binary signals into multiple outputs.
9. **74LS374 Octal Latch**: Holds data for efficient transfer and control.

### Instructions: Add Intel 8085 to KiCAD 🔧

1. **Download the file**: Download `ul_8085.zip`.
2. **Unzip the file**: Extract the contents to a location on your system.
3. **Add to KiCAD Symbols Folder**: Go to your KiCAD installation folder and open the `Symbols` folder. Move the extracted file into this folder.
4. **Add Symbol Library in KiCAD**:
    - Open KiCAD, go to **Preferences** > **Manage Symbol Libraries**.
    - Click the tiny **plus icon** and name it `8085`.
    - Browse for the unzipped 8085 file (it should be named something like `2024_01_04_18_45`).
    - After adding, you can place the symbol by searching for `8085` in the "Place Symbol" option.
    
### Conclusion 🎉

This project demonstrates hands-on skills in **hardware design**, **circuit analysis**, **system programming**, and **debugging** in a real-world SBC application. It integrates the Intel 8085 microprocessor with modern peripherals and memory systems to create a functional microcomputer system.

---

**License**: This project is open-source and follows the MIT License. Feel free to clone, modify, and contribute!


