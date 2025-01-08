# Samsung-RISCV
RISC-V: An open-source instruction set designed for creating custom processors tailored to various applications, based on the Reduced Instruction Set Computer (RISC) architecture.

### 1. Download the Oracle Virtual Machine
<img src="https://github.com/user-attachments/assets/dd7eed6f-afc5-4a4d-9d28-5c94b033e330" alt="screenshot-1" style="width:80%; height:auto;">


### 2. What is OpenLane?
OpenLane is an advanced silicon implementation platform that integrates open-source tools like Yosys, OpenROAD, Magic, KLayout, and other open-source or proprietary utilities.

### 3. Installed OpenLane in Ubuntu
<img src="https://github.com/user-attachments/assets/29ba59cc-6836-481a-8b53-2b7bec2e71c7" alt="screenshot-2" style="width:80%; height:auto;">

## Task 1
This task involves understanding how to execute a C program within the RISC-V environment. It also includes determining the number of memory addresses occupied by the main section in the executed program.
<details> <summary>Click here to view the results</summary>


### 1. Sample C Program Code:
```c
#include <stdio.h>
int main() {
  	int i, sum = 0, n = 70;
  	for (i=1; i <= n; ++i) {
  	sum += i;
  	}
  	printf("Sum of numbers from 1 to %d is %d\n", n, sum);
  	return 0;
}
```
<img src="https://github.com/user-attachments/assets/610236e6-1d2c-4464-8e67-16aff8e5422e" alt="screenshot-3" style="width:80%; height:auto;">



### 2. Compilation and Result
<img src="https://github.com/user-attachments/assets/06afcca1-f39b-4521-902d-7f3ca5bbfe7b" alt="screenshot-4" style="width:80%; height:auto;">


### 3. Identifying the Main Section
<img src="https://github.com/user-attachments/assets/42f6541c-4816-437a-9eb6-b9717d51f325" alt="screenshot-5" style="width:80%; height:auto;">


### 4. Calculate the Total Addresses
<img src="https://github.com/user-attachments/assets/f3ca4b90-454f-432c-8f15-80ae0b8ca3d5" alt="screenshot-6" style="width:80%; height:auto;">

