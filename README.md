# Device Tree Compiler (Windows MinGW) 

Ready to use project DTC for Windows. 

## Getting Started

This repository contains Eclipse project with source DTC ([http://devicetree.org/Device_Tree_Compiler](http://devicetree.org/Device_Tree_Compiler))

 - -[Device Tree Compiler for Windows](https://github.com/lbmeng/dtc) - Origin source here

### Prerequisites

- Windows 10
- Eclipse  
- MinGW

### Set up workspace

- clone 
- Eclipse Run
- import project 
- build 

### Testing

Copy **/Debug/mdtc.exe**  to  **/test**

Run **CMD** console 

Execute 

```
mdtc.exe -I dts -O dtb -o my-tree.dtb zynq-zed.dts
```
 
