# Cross-Platform Development and Toolchain Customization  

The purpose of this assignment is to deepen our understanding of cross-compilation and toolchain customization by executing a C program on the MIPS architecture. 

---
## **Objective**
The objective of this assignment is to:
- Gain hands-on experience with cross-compilation.
- Understand the differences between cross-compilation and native toolchains.
- Successfully execute the previously compiled `hello.c` program on the MIPS architecture.
- Document the entire process with detailed explanations and screenshots.

---
## **Setup and Instructions**
### **1. Background Information**
In Lab 01, we used Crosstool-ng to build a cross-compiling toolchain and executed `hello.c` on an ARM architecture. Now, we will extend this knowledge to the MIPS architecture.

### **2. Required Tools & Commands**
To complete this task, we will use the following tools:
- `mips-unknown-linux-gnu`  
- `mips-linux-gcc`  
- `qemu-mips`

### **3. Execution Steps**
1. Set up the MIPS toolchain using `mips-unknown-linux-gnu`.
2. Compile `hello.c` using `mips-linux-gcc`.
3. Run the compiled binary on a MIPS emulator using `qemu-mips`.
4. Capture screenshots of each step and include them in the final report.

---
## **Report Requirements**
Your report should include the following sections:
### **1. Architecture Comparison**
- Differences between MIPS and ARM architectures.
- Applications and use cases of both architectures.

### **2. Toolchain Explanation**
- Difference between a cross-compiling toolchain and a native toolchain.
- Why a cross-compiling toolchain is needed for this task.

### **3. Key Definitions**
- Explanation of **bootloader, kernel, and filesystem**.
- Definitions and practical applications of **kernel modules**.

### **4. Execution Documentation**
- Screenshots demonstrating each step of the process.
- Example output of the program displaying `hello ${yourName}`.
 
