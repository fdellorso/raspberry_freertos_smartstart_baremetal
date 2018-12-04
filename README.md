# FreeRTOS 10.1.1 (Pi 2,3 32Bit and Pi3 AARCH64 now working)
![](https://github.com/LdB-ECM/Docs_and_Images/blob/master/Images/FreeRTOS.jpg?raw=true)
>
I have been messing around with Task Switchers (Single/Multicore) in 32Bit or 64Bit mode and have decided to put some up. This is the easiest one to understand and start with being a simple FreeRTOS 10.1.1 port. Yes it all boots from the standard SmartStart system as usual so it autodetect models etc.  So on this example we have the RTOS simply running on one core doing the boring time slicing. 
>
Technically it probably should be called 10.1.2 because it has a couple of minor changes I added. I improved a couple of task display string functions and added CPU load percentage as a standard funtion
#### unsigned int xLoadPercentCPU(void);
>
Sorry it's a pretty boring example just moving a couple bars backwards forward, I will try and make some more advanced samples.
>
### > As usual you can copy prebuilt files in "DiskImg" directory on formatted SD card to test <

To compile edit the makefile so the compiler path matches your compiler:
>
For Pi1: 
>     Make Pi1
For Pi2:
>     Make Pi2
For Pi3 in 32 Bit:
>     Make Pi3
For Pi3 in 64 Bit:
>     Make Pi3-64     
     
To clean for full compile:     
>     Make Clean
     


