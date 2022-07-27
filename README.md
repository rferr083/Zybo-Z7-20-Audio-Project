# Zybo-Z7-20-Audio-Project
This project demonstrates how to use the Zybo Z7-20's Audio Codec and RAM to record samples of audio and play them back. Vivado is used to build the demo's hardware platform, and Xilinx SDK is used to program the bitstream onto the board and to build and deploy a C application.

To use this demo, the Zybo Z7-20 must be connected to a computer over MicroUSB, which must be running a serial terminal. For more information on how to set up and use a serial terminal, such as Tera Term or PuTTY, refer to [this tutorial](https://reference.digilentinc.com/learn/programmable-logic/tutorials/tera-term).

The audio demo records a 5 second sample from microphone(J6) or line in (J7) and plays it back on headphone out(J5). Recording and playback are controlled by push buttons from a usb uart serial menu as shown below.
|  Button  | Function             |
| -------- | -------------------- |
|  BTN0    |  no effect           |
|  BTN1    |  record from mic in  |
|  BTN2    |  play on hph out     |
|  BTN3    |  record from line in |
