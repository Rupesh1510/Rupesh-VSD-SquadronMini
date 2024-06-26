# Rupesh-VSD-SquadronMini
The repository tracks all the progress for a duration of 4 weeks of the Internship provided by VSD (VLSI System Design) 

## Task 0: Installation of Toolchain:

1.Install Ubuntu

I have already installed Ubuntu as my primary OS.

![image](https://github.com/Rupesh1510/Rupesh-VSD-SquadronMini/assets/94752269/7d990106-e23f-4b01-857b-92508db81f93)


2.Install riscv-gnu-toolchain (https://github.com/riscv-collab/riscv-gnu-toolchain)

```
$ git clone https://github.com/riscv/riscv-gnu-toolchain
```
install pre-requisites for Ubuntu

```
$ sudo apt-get install autoconf automake autotools-dev curl python3 python3-pip libmpc-dev libmpfr-dev libgmp-dev gawk build-essential bison flex texinfo gperf libtool patchutils bc zlib1g-dev libexpat-dev ninja-build git cmake libglib2.0-dev libslirp-dev
```

Install

```
cd riscv-gnu-toolchain
./configure --prefix=/opt/riscv
sudo make linux

```

![image](https://github.com/Rupesh1510/Rupesh-VSD-SquadronMini/assets/94752269/31d05ee6-bfff-497a-9964-81771c233f69)


3. Install Yosys

```
git clone https://github.com/YosysHQ/yosys.git
cd yosys
sudo apt install make (If make is not installed please install it) 
sudo apt-get install build-essential clang bison flex \
    libreadline-dev gawk tcl-dev libffi-dev git \
    graphviz xdot pkg-config python3 libboost-system-dev \
    libboost-python-dev libboost-filesystem-dev zlib1g-dev
make config-gcc
make 
sudo make install

```

![image](https://github.com/Rupesh1510/Rupesh-VSD-SquadronMini/assets/94752269/11c4c21a-7aad-4751-b26a-b163e5548a50)


4. Install iverilog
```
sudo apt-get install iverilog

```
![image](https://github.com/Rupesh1510/Rupesh-VSD-SquadronMini/assets/94752269/ca744ff0-a209-479f-b942-78417bf14387)


5. Install gtkwave
```
sudo apt update
sudo apt install gtkwave

```
![image](https://github.com/Rupesh1510/Rupesh-VSD-SquadronMini/assets/94752269/dd391c52-ac1b-4ddb-958a-a608d9b071f5)

## Task 1: Basic C progams

![image](https://github.com/Rupesh1510/Rupesh-VSD-SquadronMini/assets/94752269/d219fb5f-4358-4108-a9c8-1297093a696c)

![image](https://github.com/Rupesh1510/Rupesh-VSD-SquadronMini/assets/94752269/218c1dae-2de2-4dfe-a371-a59a7e4bd0fd)


