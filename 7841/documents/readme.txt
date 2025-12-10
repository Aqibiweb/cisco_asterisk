bPhone details:
MAC :00B0E1143BA2

firmware:
sip78xx.11-7-1-17

Important resources:
https://github.com/NamoDev/Cisco-IP-Phone-Provisioning-Files/blob/master/7821.cnf.xml

https://usecallmanager.nz/sepmac-cnf-xml.html



I am working on cisco ip xml programming task. My admin managing sip server and pbs asterisk. We have applied different phone services using xml files. Here is task status

IPT Feature
8800 series (8861)
1- Making call (working) 
2- call tranfer (working)
3- confrance call(admin configured)(not working)
4- forword call (admin configured)(not working)
5- Missed call (working)
6- On hold (working) 
7- add new call during call (working)
8- call decline (working)

IPT Feature
7800 series (7821 , 7841)
1- Making call (working) 
2- call tranfer (working) 
3- confrance call (admin configured)(not working)
4- forword call (admin configured)(not working)
5- Missed call (working)
6- On hold (working) 
7- add new call during call (working)
8- call decline (not working )


I have modify xml files loacated in 7841/dev using claude but remaning features are not work here are result after testing with phone

Call conference:
User A Call user B , user B pick phone then press confernce button then Call C user C pick then press conference button to confirm it work but on press confrerence button it not work

Forward call:
Forward call button show but it now work as my admin said you need to configure *72 code when press forward all soft key

Decline call:

Decline call work for 88xx series but not on 78xx series. Soft key show decline but it soft key but it not work. 

Coding files arein 7841/dev/