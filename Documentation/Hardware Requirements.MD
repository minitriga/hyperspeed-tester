
# Hardware Requirements

**Odroid Board**

The main piece of hardware for the line tester is an Odroid C2 64 bit quad core single board computer. 
The board is conceptually like a Raspberry Pi however it features a 1 Gig NIC, essential for the line tests. 
The board can saturate this as well making it a good fit. The board has the following specifications:

	* 85x56mm
	* 40g
	* Amlogic S905 1.5Ghz quad core CPU
	* 2GB DDR3 SDRAM
	* HDMI
	* Gigabit Ethernet
	* USB2.0
	* 40+7pin GPIO port
	
The board takes a Micro SD card or eMMC card. For the line tester we settled with a 16GB card which is plenty of storage 
for the OS installation and additional storage. The log files created are not that large. In addition to the board we use 
a 16x2 LCD + IO Shield screen. This slots onto the GPIO port on the Odroid board. We use this to display the information 
regarding the line tests onto the screen. Even with the screen attached the entire package is relatively small and lightweight.


**Servers (Iperf server & SQL/Front End)**

The two server requirments are simple:

	* Ubuntu 16.04
	* 1Gb Nic 
	* Good amount of storage for logs
