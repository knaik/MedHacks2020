So I reflashed everything, things started working but the rPi initially but required a keyboard mouse setup to enable ssh and the wifi was broken

Sat 1025pm

I have had to travel all day since when I woke up and got ready till now. I visited my Grandma's house first. Now I am at my cousin where there are no ethernet jacks. and I had to steal a power supply from somewhere. 

But the night is just starting.

Trying 
https://medium.com/@jrcharney/connect-your-raspberry-pi-to-your-computer-via-ethernet-4564e1e68922  
now

sun1250am
I got distracted helping cousin fix his mic problems

322am
The wifi went out

so what now


I was really excited for this

there's still hope 3:33


eth0: flags=4099<UP,BROADCAST,MULTICAST>  mtu 1500
        ether b8:27:eb:8f:70:c4  txqueuelen 1000  (Ethernet)
        RX packets 1146  bytes 119623 (116.8 KiB)
        RX errors 0  dropped 0  overruns 0  frame 0
        TX packets 514  bytes 88264 (86.1 KiB)
        TX errors 0  dropped 0 overruns 0  carrier 0  collisions 0

lo: flags=73<UP,LOOPBACK,RUNNING>  mtu 65536
        inet 127.0.0.1  netmask 255.0.0.0
        inet6 ::1  prefixlen 128  scopeid 0x10<host>
        loop  txqueuelen 1000  (Local Loopback)
        RX packets 181  bytes 18292 (17.8 KiB)
        RX errors 0  dropped 0  overruns 0  frame 0
        TX packets 181  bytes 18292 (17.8 KiB)
        TX errors 0  dropped 0 overruns 0  carrier 0  collisions 0

wlan0: flags=4163<UP,BROADCAST,RUNNING,MULTICAST>  mtu 1500
        inet 192.168.1.48  netmask 255.255.255.0  broadcast 192.168.1.255
        inet6 fe80::1f46:2934:b260:ea4b  prefixlen 64  scopeid 0x20<link>
        ether 00:0f:60:0a:28:f3  txqueuelen 1000  (Ethernet)
        RX packets 464388  bytes 686204814 (654.4 MiB)
        RX errors 0  dropped 0  overruns 0  frame 0
        TX packets 171067  bytes 15010880 (14.3 MiB)
        TX errors 0  dropped 0 overruns 0  carrier 0  collisions 0


VNC works
3:50am