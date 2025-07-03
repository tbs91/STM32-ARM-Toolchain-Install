# STM32-ARM-Toolchain-Install
This is just a write up for the installtion process of setting up the toolchain for programming STM32 microcontrollers.

Install the latest Ubuntu which for me is 24.04.2 LTS.
Within the 'Home' directory, create a folder called 'dev' and within that folder create three folders called 'hw', 'sw' and 'tools'
Download 'gcc-arm-none-eabi-10.3-2021.10-x86_64-linux.tar.bz2' from https://developer.arm.com/downloads/-/gnu-rm
Extract the contents, move down one folder and copy the folder 'gcc-arm-none-eabi-10.3-2021.10' to previosuly created 'tools' folder.

Install 'make' with command 'sudo apt install make'
Navigate to the location of the gcc compiler '/home/thomas/dev/tools/gcc-arm-none-eabi-10.3-2021.10/bin' and run command 'chmod +x ./arm-none-eabi-gcc' if you have issues with not having permission to run the compiler.

The following steps have been taken from https://wiki.st.com/stm32mpu/wiki/STM32CubeProgrammer
Download STM32CubeProgrammer from ST's website, extract and run 'SetupSTM32CubeProgrammer-2.19.0.linux'. Follow the installation procedure.

