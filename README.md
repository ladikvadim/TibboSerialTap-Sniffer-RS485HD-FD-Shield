# TibboSerialTap-Sniffer-RS485HD-FD-Shield
IO Ninja Serial Tap RS-485 Shield converts data lines from Half - to Full-Duplex.

Many of us often need to monitor data streams on the UART/RS232/RS485 lines. This is especially true when you need to debug the interaction between devices. For this purpose, I bought an [IO Ninja Setial Tap](https://tibbo.com/store/ninja/ninja-serial-tap.html "IO Ninja Serial Tap"). This is an excellent hardware sniffer terminal, but it has one unpleasant feature - it does not allow separating the data into individual messages when monitoring the RS485 Half Duplex bus. For the last few years, I have been working a lot with industrial equipment, which communicates via RS485 HD. Therefore, for the convenience of data analysis, I developed a simple shield, which allows converting signals from the RS485 HD bus to Sniffer RS485 FD and thus separating messages in the terminal. This solution makes it possible to use the sniffer to analyze the data transmitted over the RS485 HD bus, and I hope it can be helpful to the community.
<p align="center">
  <img src="https://user-images.githubusercontent.com/17494764/219967143-cc7fe6d0-84a6-432a-8074-188c7e40fec9.PNG"/>
</p>
<p align="center"> Shield's Schematic Diagram </p>

<p align="center">
  <img src="https://user-images.githubusercontent.com/17494764/219965195-7a487865-a1d9-4a5e-ba9f-2af2334f87fd.svg"/>
</p>
<p align="center"> Devices Connection Diagram </p>

![1](https://user-images.githubusercontent.com/17494764/219965978-43ab11a7-2eb1-4da1-99a5-cd7f082ec94b.PNG)
<p align="center"> The shield with a Serial Tap Device </p>

![Untitled-1](https://user-images.githubusercontent.com/17494764/219966213-566600e8-f113-4065-967a-13bd895060e6.png)
<p align="center">Two-device RS485 communication data log without and with the shield</p>






Bill of Materials

| #  | Name | Quantity  | Value |
| ------------- | ------------- | ------------- | ------------- |
| 1  | U3, U4  | 2 | MAX13487EESA+ |
| 2  | U1, U2  | 2 | MAX485CSA+ |
| 3  | U5  | 1 | AM1L-0503S-FZ |
| 4  | C1-C4  | 4 | 0603, 0.1 uF |
| 5  | R1-R4 | 4 | 0603, 2 kOhm |
| 6  | RS485.SnifferSide, RS485.FieldSide | 2 | XH2.54 4Pin |
| 7  | Power| 1 | XH2.54 2Pin |
