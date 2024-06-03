# Create-static-IP-raspberrypi
To set up a static IP address on your Raspberry Pi

## Steps
 - Connect to rasbperry pi with ssh or vnc
 - Open terminal
 - Use ```sudo nano /etc/dhcpcd.conf```

   ![image](https://github.com/Rabie45/Create-static-IP-raspberrypi/assets/76526170/c8f943fe-e24c-4641-b683-d2c18007e0f1)
 - Write the Ip u want to be static
 - If u use wifi write wlan0 interface if u use ethernet use eth0
 - Use this command if u dont know the name of ur interface ```ifconfig```
   
![image](https://github.com/Rabie45/Create-static-IP-raspberrypi/assets/76526170/d281a0aa-cf2e-4b35-8ea4-5f74aceb969d)
 - ```sudo reboot```

![image](https://github.com/Rabie45/Create-static-IP-raspberrypi/assets/76526170/334c2e87-0fac-400c-93e9-6717d0c6e575)
 - Ur ip is static now 
