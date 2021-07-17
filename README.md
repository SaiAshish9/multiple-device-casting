# multiple-device-casting

1. Extract ip address of the device by going to -> Settings -> About Phone -> Status
 
 (ipv6 / ipv4)
 
a) fe80::a8c3:18ff:fec3:f5b8 / 192.168.0.102

b) fe80::54c5:2be9:7da0:f7ed / 192.168.0.103

Connect one device :
 
execute adb tcpip 5555

Connect another :
 
execute adb tcpip 5556

2 numbers can be selected from :

( 5555/5556/5557/5558 )

repeat the same for other devices
