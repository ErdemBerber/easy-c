# easy-c
# MPL / Easy Compiler

### MPL Compiler Features :

* Written in MPL / Easy language
* Supports dynamic nature of MPL / Easy language
* Build on core MPL / Easy written Standard Library and LLVM
* Multi-pass architecture for MPL / Easy optimization
* Capable of compiling any MPL code with any complexity
* Ability to build transformable LLVM IR codes
* Self-hosted

## Building MPL Compiler
* **1.** git clone git@[github.com:Matway/easy-c](https://github.com/Matway/easy-c).git
* **2.** cd easy-c
* **3.** git clone git@[github.com:Matway/easy-sl](https://github.com/Matway/easy-sl).git sl
* **4.** git clone git@[github.com:Matway/easy-llvm](https://github.com/Matway/easy-llvm).git llvm
* **5.** Extract all files from bundle: [https://matway.net/easy/easyc_bundle.7z](https://matway.net/easy/easyc_bundle.7z)
* **6.** Run build.bat

Resulting ***test.exe*** is the easy compiler binary. It can be renamed to ***easyc.exe***.

## References
### [MPL Standard Library](https://github.com/Matway/easy-sl)
Library (built with MPL) contains generic algorithms and data structures for MPL. It provides useful utilities in all stages of the MPL Compiler development.
### [LLVM IR Library](https://github.com/Matway/easy-llvm)
Uniform API for creating LLVM IR code, built with MPL.
## Project Development Status
### Visual Studio Integration
In progress.
