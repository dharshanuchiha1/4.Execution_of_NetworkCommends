# 4.Execution_of_NetworkCommands
## AIM :Use of Network commands in Real Time environment
## Software : Command Prompt And Network Protocol Analyzer
## Procedure: To do this EXPERIMENT- follows these steps:
<BR>
In this EXPERIMENT- students have to understand basic networking commands e.g cpdump, netstat, ifconfig, nslookup ,traceroute and also Capture ping and traceroute PDUs using a network protocol analyzer 
<BR>
All commands related to Network configuration which includes how to switch to privilege mode
<BR>
and normal mode and how to configure router interface and how to save this configuration to
<BR>
flash memory or permanent memory.
<BR>
This commands includes
<BR>
• Configuring the Router commands
<BR>
• General Commands to configure network
<BR>
• Privileged Mode commands of a router 
<BR>
• Router Processes & Statistics
<BR>
• IP Commands
<BR>
• Other IP Commands e.g. show ip route etc.
<BR>

## Output
```
Microsoft Windows [Version 10.0.26200.9168]
(c) Microsoft Corporation. All rights reserved.

C:\Users\dhars>ping google.com

Pinging google.com [2404:6800:4007:838::200e] with 32 bytes of data:
Reply from 2404:6800:4007:838::200e: time=14ms
Reply from 2404:6800:4007:838::200e: time=13ms
Reply from 2404:6800:4007:838::200e: time=23ms
Reply from 2404:6800:4007:838::200e: time=6ms

Ping statistics for 2404:6800:4007:838::200e:
    Packets: Sent = 4, Received = 4, Lost = 0 (0% loss),
Approximate round trip times in milli-seconds:
    Minimum = 6ms, Maximum = 23ms, Average = 14ms

C:\Users\dhars>ipconfig

Windows IP Configuration


Ethernet adapter Ethernet 2:

   Connection-specific DNS Suffix  . :
   Link-local IPv6 Address . . . . . : fe80::7767:e1b4:ab93:3ee6%5
   IPv4 Address. . . . . . . . . . . : 192.168.56.1
   Subnet Mask . . . . . . . . . . . : 255.255.255.0
   Default Gateway . . . . . . . . . :

Unknown adapter Local Area Connection:

   Media State . . . . . . . . . . . : Media disconnected
   Connection-specific DNS Suffix  . :

Wireless LAN adapter Local Area Connection* 1:

   Media State . . . . . . . . . . . : Media disconnected
   Connection-specific DNS Suffix  . :

Wireless LAN adapter Local Area Connection* 2:

   Media State . . . . . . . . . . . : Media disconnected
   Connection-specific DNS Suffix  . :

Wireless LAN adapter Wi-Fi:

   Connection-specific DNS Suffix  . : saveetha.in
   IPv6 Address. . . . . . . . . . . : 2403:8600:c090:42:0:401:caaa:6393
   Link-local IPv6 Address . . . . . : fe80::d827:63e8:1a3b:2d20%8
   Autoconfiguration IPv4 Address. . : 169.254.76.224
   Subnet Mask . . . . . . . . . . . : 255.255.0.0
   Default Gateway . . . . . . . . . : fe80::eedd:24ff:fe3d:ced5%8

Ethernet adapter Bluetooth Network Connection:

   Media State . . . . . . . . . . . : Media disconnected
   Connection-specific DNS Suffix  . :

Ethernet adapter Ethernet:

   Media State . . . . . . . . . . . : Media disconnected
   Connection-specific DNS Suffix  . :

C:\Users\dhars>tracert google.com

Tracing route to google.com [2404:6800:4007:838::200e]
over a maximum of 30 hops:

  1     9 ms     4 ms    13 ms  2403:8600:c090:42::1
  2     *        *        *     Request timed out.
  3     *        *        *     Request timed out.
  4     *        *        *     Request timed out.
  5     *        *        *     Request timed out.
  6     *        *        *     Request timed out.
  7     *        *        *     Request timed out.
  8     *        *        *     Request timed out.
  9     *        *        *     Request timed out.
 10     8 ms     7 ms     6 ms  lcmaaa-ao-in-x0e.1e100.net [2404:6800:4007:838::200e]

Trace complete.

C:\Users\dhars>nslookup google.com
Server:  UnKnown
Address:  2403:8600:c090:42:a000::200

Non-authoritative answer:
Name:    google.com
Addresses:  2404:6800:4007:838::200e
          142.251.223.14


C:\Users\dhars>netstat -a

Active Connections

  Proto  Local Address          Foreign Address        State
  TCP    0.0.0.0:135            Dharshan:0             LISTENING
  TCP    0.0.0.0:445            Dharshan:0             LISTENING
  TCP    0.0.0.0:1309           Dharshan:0             LISTENING
  TCP    0.0.0.0:5040           Dharshan:0             LISTENING
  TCP    0.0.0.0:49664          Dharshan:0             LISTENING
  TCP    0.0.0.0:49665          Dharshan:0             LISTENING
  TCP    0.0.0.0:49666          Dharshan:0             LISTENING
  TCP    0.0.0.0:49667          Dharshan:0             LISTENING
  TCP    0.0.0.0:49668          Dharshan:0             LISTENING
  TCP    0.0.0.0:49670          Dharshan:0             LISTENING
  TCP    127.0.0.1:8884         Dharshan:0             LISTENING
  TCP    127.0.0.1:19294        Dharshan:0             LISTENING
  TCP    127.0.0.1:55248        Dharshan:65001         ESTABLISHED
  TCP    127.0.0.1:62394        Dharshan:0             LISTENING
  TCP    127.0.0.1:63306        Dharshan:0             LISTENING
  TCP    127.0.0.1:63745        Dharshan:0             LISTENING
  TCP    127.0.0.1:65001        Dharshan:0             LISTENING
  TCP    127.0.0.1:65001        Dharshan:55248         ESTABLISHED
  TCP    169.254.76.224:139     Dharshan:0             LISTENING
  TCP    192.168.56.1:139       Dharshan:0             LISTENING
  TCP    [::]:135               Dharshan:0             LISTENING
  TCP    [::]:445               Dharshan:0             LISTENING
  TCP    [::]:49664             Dharshan:0             LISTENING
  TCP    [::]:49665             Dharshan:0             LISTENING
  TCP    [::]:49666             Dharshan:0             LISTENING
  TCP    [::]:49667             Dharshan:0             LISTENING
  TCP    [::]:49668             Dharshan:0             LISTENING
  TCP    [::]:49670             Dharshan:0             LISTENING
  TCP    [::1]:49669            Dharshan:0             LISTENING
  TCP    [2403:8600:c090:42:0:401:caaa:6393]:49800  [2603:1063:2001:190b::365:ff1]:https  ESTABLISHED
  TCP    [2403:8600:c090:42:0:401:caaa:6393]:49801  [2603:1063:2001:190b::365:ff1]:https  ESTABLISHED
  TCP    [2403:8600:c090:42:0:401:caaa:6393]:49872  g2600-140f-5e00-0005-0000-0000-17d3-3c66:http  ESTABLISHED
  TCP    [2403:8600:c090:42:0:401:caaa:6393]:54425  pnmaaa-be-in-x03:https  ESTABLISHED
  TCP    [2403:8600:c090:42:0:401:caaa:6393]:54607  lcbomp-in-f84:https    ESTABLISHED
  TCP    [2403:8600:c090:42:0:401:caaa:6393]:55177  lcmaaa-az-in-x0e:https  ESTABLISHED
  TCP    [2403:8600:c090:42:0:401:caaa:6393]:55250  [64:ff9b::d4e:6da3]:https  ESTABLISHED
  TCP    [2403:8600:c090:42:0:401:caaa:6393]:56480  sf-in-f188:https       ESTABLISHED
  TCP    [2403:8600:c090:42:0:401:caaa:6393]:58239  lb-140-82-113-26-iad:https  ESTABLISHED
  TCP    [2403:8600:c090:42:0:401:caaa:6393]:59186  [2606:4700:4403::ac40:94eb]:https  ESTABLISHED
  TCP    [2403:8600:c090:42:0:401:caaa:6393]:59435  pnmaaa-ba-in-x0e:https  ESTABLISHED
  TCP    [2403:8600:c090:42:0:401:caaa:6393]:59522  [2600:1901:0:47fc::]:https  ESTABLISHED
  TCP    [2403:8600:c090:42:0:401:caaa:6393]:60654  [2603:1040:a06:6::]:https  ESTABLISHED
  TCP    [2403:8600:c090:42:0:401:caaa:6393]:60655  [2603:1040:a06:6::]:https  ESTABLISHED
  TCP    [2403:8600:c090:42:0:401:caaa:6393]:61387  [2606:4700:4408::ac40:9bd1]:https  ESTABLISHED
  TCP    [2403:8600:c090:42:0:401:caaa:6393]:62079  [2600:1901:0:47fc::]:https  ESTABLISHED
  TCP    [2403:8600:c090:42:0:401:caaa:6393]:62425  [2606:4700:3030::6815:2bbe]:https  ESTABLISHED
  UDP    0.0.0.0:123            *:*
  UDP    0.0.0.0:5050           *:*
  UDP    0.0.0.0:5353           *:*
  UDP    0.0.0.0:5353           *:*
  UDP    0.0.0.0:5353           *:*
  UDP    0.0.0.0:5353           *:*
  UDP    0.0.0.0:5353           *:*
  UDP    0.0.0.0:5353           *:*
  UDP    0.0.0.0:5353           *:*
  UDP    0.0.0.0:5353           *:*
  UDP    0.0.0.0:5353           *:*
  UDP    0.0.0.0:5355           *:*
  UDP    0.0.0.0:50656          *:*
  UDP    0.0.0.0:65488          *:*
  UDP    127.0.0.1:1900         *:*
  UDP    127.0.0.1:10030        *:*
  UDP    127.0.0.1:49827        127.0.0.1:49827
  UDP    127.0.0.1:52630        *:*
  UDP    127.0.0.1:53382        127.0.0.1:53382
  UDP    127.0.0.1:53383        *:*
  UDP    127.0.0.1:59833        *:*
  UDP    169.254.76.224:137     *:*
  UDP    169.254.76.224:138     *:*
  UDP    169.254.76.224:1900    *:*
  UDP    169.254.76.224:5353    *:*
  UDP    169.254.76.224:59832   *:*
  UDP    192.168.56.1:137       *:*
  UDP    192.168.56.1:138       *:*
  UDP    192.168.56.1:1900      *:*
  UDP    192.168.56.1:5353      *:*
  UDP    192.168.56.1:59831     *:*
  UDP    [::]:123               *:*
  UDP    [::]:5353              *:*
  UDP    [::]:5353              *:*
  UDP    [::]:5353              *:*
  UDP    [::]:5353              *:*
  UDP    [::]:5353              *:*
  UDP    [::]:5355              *:*
  UDP    [::]:50656             *:*
  UDP    [::]:65489             *:*
  UDP    [::1]:1900             *:*
  UDP    [::1]:59830            *:*
  UDP    [2403:8600:c090:42:0:401:caaa:6393]:5353  *:*
  UDP    [fe80::7767:e1b4:ab93:3ee6%5]:1900  *:*
  UDP    [fe80::7767:e1b4:ab93:3ee6%5]:59828  *:*
  UDP    [fe80::d827:63e8:1a3b:2d20%8]:1900  *:*
  UDP    [fe80::d827:63e8:1a3b:2d20%8]:5353  *:*
  UDP    [fe80::d827:63e8:1a3b:2d20%8]:59829  *:*

C:\Users\dhars>arp -a

Interface: 192.168.56.1 --- 0x5
  Internet Address      Physical Address      Type
  192.168.56.255        ff-ff-ff-ff-ff-ff     static
  224.0.0.2             01-00-5e-00-00-02     static
  224.0.0.22            01-00-5e-00-00-16     static
  224.0.0.251           01-00-5e-00-00-fb     static
  224.0.0.252           01-00-5e-00-00-fc     static
  230.0.0.1             01-00-5e-00-00-01     static
  239.255.255.250       01-00-5e-7f-ff-fa     static

Interface: 169.254.76.224 --- 0x8
  Internet Address      Physical Address      Type
  169.254.173.129       a8-e2-91-95-62-20     dynamic
  169.254.255.255       ff-ff-ff-ff-ff-ff     static
  224.0.0.2             01-00-5e-00-00-02     static
  224.0.0.22            01-00-5e-00-00-16     static
  224.0.0.251           01-00-5e-00-00-fb     static
  224.0.0.252           01-00-5e-00-00-fc     static
  230.0.0.1             01-00-5e-00-00-01     static
  239.255.255.250       01-00-5e-7f-ff-fa     static
  255.255.255.255       ff-ff-ff-ff-ff-ff     static

C:\Users\dhars>hostname
Dharshan

C:\Users\dhars>route print
===========================================================================
Interface List
  5...0a 00 27 00 00 05 ......VirtualBox Host-Only Ethernet Adapter
  7...00 ff 4a db 27 7c ......TAP-Windows Adapter V9
 16...dc 97 ba e9 20 6f ......Microsoft Wi-Fi Direct Virtual Adapter
 14...de 97 ba e9 20 6e ......Microsoft Wi-Fi Direct Virtual Adapter #2
  8...dc 97 ba e9 20 6e ......Intel(R) Wi-Fi 6 AX201 160MHz
 15...dc 97 ba e9 20 72 ......Bluetooth Device (Personal Area Network)
 11...d0 c1 b5 39 19 5e ......Realtek PCIe GbE Family Controller
  1...........................Software Loopback Interface 1
===========================================================================

IPv4 Route Table
===========================================================================
Active Routes:
Network Destination        Netmask          Gateway       Interface  Metric
        127.0.0.0        255.0.0.0         On-link         127.0.0.1    331
        127.0.0.1  255.255.255.255         On-link         127.0.0.1    331
  127.255.255.255  255.255.255.255         On-link         127.0.0.1    331
      169.254.0.0      255.255.0.0         On-link    169.254.76.224    286
   169.254.76.224  255.255.255.255         On-link    169.254.76.224    286
  169.254.255.255  255.255.255.255         On-link    169.254.76.224    286
     192.168.56.0    255.255.255.0         On-link      192.168.56.1    281
     192.168.56.1  255.255.255.255         On-link      192.168.56.1    281
   192.168.56.255  255.255.255.255         On-link      192.168.56.1    281
        224.0.0.0        240.0.0.0         On-link         127.0.0.1    331
        224.0.0.0        240.0.0.0         On-link      192.168.56.1    281
        224.0.0.0        240.0.0.0         On-link    169.254.76.224    286
  255.255.255.255  255.255.255.255         On-link         127.0.0.1    331
  255.255.255.255  255.255.255.255         On-link      192.168.56.1    281
  255.255.255.255  255.255.255.255         On-link    169.254.76.224    286
===========================================================================
Persistent Routes:
  None

IPv6 Route Table
===========================================================================
Active Routes:
 If Metric Network Destination      Gateway
  8    286 ::/0                     fe80::eedd:24ff:fe3d:ced5
  1    331 ::1/128                  On-link
  8    286 2403:8600:c090:42::/84   On-link
  8    286 2403:8600:c090:42:0:401:caaa:6393/128
                                    On-link
  5    281 fe80::/64                On-link
  8    286 fe80::/64                On-link
  5    281 fe80::7767:e1b4:ab93:3ee6/128
                                    On-link
  8    286 fe80::d827:63e8:1a3b:2d20/128
                                    On-link
  1    331 ff00::/8                 On-link
  5    281 ff00::/8                 On-link
  8    286 ff00::/8                 On-link
===========================================================================
Persistent Routes:
  None

C:\Users\dhars>getmac

Physical Address    Transport Name                                          
=================== ==========================================================
D0-C1-B5-39-19-5E   Media disconnected                                      
DC-97-BA-E9-20-6E   \Device\Tcpip_{78029B66-2AB3-48A4-BC59-7C24D30D483D}    
0A-00-27-00-00-05   \Device\Tcpip_{33B6B0B6-771A-4C6A-8527-9222B7FE1A93}    
DC-97-BA-E9-20-72   Media disconnected                                      
00-FF-4A-DB-27-7C   Media disconnected                                      

C:\Users\dhars>nmap
'nmap' is not recognized as an internal or external command,
operable program or batch file.

C:\Users\dhars>ssh
usage: ssh [-46AaCfGgKkMNnqsTtVvXxYy] [-B bind_interface] [-b bind_address]
           [-c cipher_spec] [-D [bind_address:]port] [-E log_file]
           [-e escape_char] [-F configfile] [-I pkcs11] [-i identity_file]
           [-J destination] [-L address] [-l login_name] [-m mac_spec]
           [-O ctl_cmd] [-o option] [-P tag] [-p port] [-Q query_option]
           [-R address] [-S ctl_path] [-W host:port] [-w local_tun[:remote_tun]]
           destination [command [argument ...]]

C:\Users\dhars>
```
## Result
Thus Execution of Network commands Performed 
