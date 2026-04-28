**Devbored RP2040**

I finally finished my first PCB! It’s a Devboard using the RP2040 chip. It was more comples than I thought it would be, but I got it working and learned alot from it.I wanted to learn how to make a PCB but I often get bored when I am not intrusted in the project or it feels too 'beginner' so i decided to jump in the middle end of the pool and make a Devbored!!

This project is a custom RP2040 Devboard. It’s a 2-layer PCB designed in KiCad that breaks out the pins for the RP2040 chip and includes all the necessary parts like the crystal, power whires, and a USB-C port.

**Pictures:**

<img width="662" height="735" alt="image" src="https://github.com/user-attachments/assets/e692af3f-341d-4d86-82ff-14dbc63db721" />


**no errors :)))**
<img width="1543" height="833" alt="Screenshot 2026-04-27 120632" src="https://github.com/user-attachments/assets/11371bda-7d95-43cd-90d1-be3566be6fb0" />

**BOM:**

[DevboredBOM.csv](https://github.com/user-attachments/files/27150701/DevboredBOM.csv)
Reference	Value	Datasheet	Footprint	Qty	DNP


C1,C2,C3,C4,C5,C6,C7,C8,C9,C11,C17	0.1uf		Capacitor_SMD:C_0402_1005Metric	11	


C10,C12	1uf		Capacitor_SMD:C_0402_1005Metric	2	


C13,C14	10uf		Capacitor_SMD:C_0603_1608Metric	2	


C15,C16	15pf		Capacitor_SMD:C_0402_1005Metric	2	


C18	C			1	


C26	1uf		C_0402_1005Metric	1	


C29	1uf			1	


J1	USB_C_Receptacle_USB2.0_14P	https://www.usb.org/sites/default/files/documents/usb_type-c.zip	Connector_USB:USB_C_Receptacle_HRO_TYPE-C-31-M-12	1	


J2,J3	Conn_01x20_Pin		Connector_PinSocket_2.54mm:PinSocket_1x20_P2.54mm_Vertical	2	


J4	Conn_01x03_Pin		Connector_PinSocket_2.54mm:PinSocket_1x03_P2.54mm_Vertical	1


R1,R2	5.1k		Resistor_SMD:R_0402_1005Metric	2	


R3,R4	27om		Resistor_SMD:R_0402_1005Metric	2	


R5,R18	1k		Resistor_SMD:R_0402_1005Metric	2


R6	10k		Resistor_SMD:R_0402_1005Metric	1	


SW1	SW_Push		Button_Switch_SMD:SW_Push_SPST_NO_Alps_SKRK	1	


U1	RP2040	https://datasheets.raspberrypi.com/rp2040/rp2040-datasheet.pdf	Package_DFN_QFN:QFN-56-1EP_7x7mm_P0.4mm_EP3.2x3.2mm	1	


U2	NCP1117-1.5_SOT223	http://www.onsemi.com/pub_link/Collateral/NCP1117-D.PDF	Package_TO_SOT_SMD:SOT-223-3_TabPin2	1	


U3	W25Q128JVS	https://www.winbond.com/resource-files/w25q128jv_dtr%20revc%2003272018%20plus.pdf	Package_SO:SOIC-8_5.3x5.3mm_P1.27mm	1	


U4	APS1604M-3SQRx-ZR	https://www.mouser.com/datasheet/2/1127/APM_PSRAM_QSPI_APS1604M_3SQR_v2_7_PKG-1954896.pdf	Package_SON:Winbond_USON-8-1EP_3x2mm_P0.5mm_EP0.2x1.6mm	1	


Y1	12 MHz		Crystal:Crystal_SMD_3225-4Pin_3.2x2.5mm	1	

