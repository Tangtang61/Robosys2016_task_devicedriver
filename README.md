#Robosys2016_task_devicedriver
The sinple device driver for Raspberry Pi 3 (Rapbian)

##Descriptoin
This is the repository for the lecture RobotSystemEngineering’s task#1 in CIT.  
Tha device driver is included here.  
If you use this driver, you can turn a LED on by pushing switch.　
Remote Control Raspberry Pi 3 from note PC using SSH by wireless LAN.  
LED    → GPIO25  　
Switch → GPIO20  
*In my driver, Swtich's pin GPIO20 is used with pull down*  

##Usage
###[Linux kernel build scripts](https://github.com/ryuichiueda/raspberry_pi_kernel_build_scripts/blob/master/kernel_build_and_install_for_pi2_pi3.bash)
####*In my driver, Swtich's pin GPIO20 is used with pull down*

##Reference
###・[Tiryouh's repository](https://github.com/Tiryoh/robosys2016.git) 
####(last reading: 2017/01/07)
###・[ryuichiueda's repository](https://github.com/ryuichiueda/robosys_device_drivers.git)
####(last reading: 2017/01/07)
###・[GitHub Gist](https://gist.github.com/wate/7072365)
####(last reading: 2017/01/07)

##License
This repository is licensed under the GPLv3 license, see LICENSE.
