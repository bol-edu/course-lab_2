# course-lab_2
Board: PYNQ-Z2/KV260, Vitis version: 2022.1 <br />
PYNQ-Z2 SD card image: v2.7 <br />
KV260 SD card image: iot-kria-classic-desktop-2004-x03-20211110-98

[Youtube Demo Video (Only AXI-Master part)](https://youtu.be/314ENX1QMjo) (Vitis version: 2020.2)

# Running 2022.1-Workbook-Lab2-KV260 on Ubuntu VM
*  The [2022.1-Workbook-Lab2-KV260.pdf](https://github.com/bol-edu/course-lab_2/files/12716246/2022.1-Workbook-Lab2-KV260.pdf) was tested on Windows host Vitis. While you running Workbook on Ubuntu VM, some items are needed to concern. Please refer [Workbook-Lab1 on Ubuntu VM](https://github.com/bol-edu/course-lab_1#running-20221-workbook-lab1-on-ubuntu-vm).
*  Change Windows fc command to Ubuntu diff command, please see https://github.com/bol-edu/HLS-SOC-Discussions/discussions/77 and https://github.com/bol-edu/HLS-SOC-Discussions/discussions/42
*  Known gmp.h issue `error: 'mpfr_srcptr' has not been declared` is happened while running course-lab_2 co-sim under Ubuntu, please see https://github.com/bol-edu/HLS-SOC-Discussions/discussions/69
