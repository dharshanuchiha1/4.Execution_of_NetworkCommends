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

   Connection-specific DNS Suffix  . :
   IPv6 Address. . . . . . . . . . . : 2409:40f4:32:8ece:f5e3:8a1a:6fa:9fe7
   Temporary IPv6 Address. . . . . . : 2409:40f4:32:8ece:48cb:9eb6:d330:fe9b
   Link-local IPv6 Address . . . . . : fe80::d827:63e8:1a3b:2d20%8
   IPv4 Address. . . . . . . . . . . : 10.117.17.164
   Subnet Mask . . . . . . . . . . . : 255.255.255.0
   Default Gateway . . . . . . . . . : fe80::286d:57ff:fead:d119%8
                                       10.117.17.140

Ethernet adapter Ethernet:

   Media State . . . . . . . . . . . : Media disconnected
   Connection-specific DNS Suffix  . :

C:\Users\dhars>ipconfig /all

Windows IP Configuration

   Host Name . . . . . . . . . . . . : Dharshan
   Primary Dns Suffix  . . . . . . . :
   Node Type . . . . . . . . . . . . : Hybrid
   IP Routing Enabled. . . . . . . . : No
   WINS Proxy Enabled. . . . . . . . : No

Ethernet adapter Ethernet 2:

   Connection-specific DNS Suffix  . :
   Description . . . . . . . . . . . : VirtualBox Host-Only Ethernet Adapter
   Physical Address. . . . . . . . . : 0A-00-27-00-00-05
   DHCP Enabled. . . . . . . . . . . : No
   Autoconfiguration Enabled . . . . : Yes
   Link-local IPv6 Address . . . . . : fe80::7767:e1b4:ab93:3ee6%5(Preferred)
   IPv4 Address. . . . . . . . . . . : 192.168.56.1(Preferred)
   Subnet Mask . . . . . . . . . . . : 255.255.255.0
   Default Gateway . . . . . . . . . :
   DHCPv6 IAID . . . . . . . . . . . : 738852903
   DHCPv6 Client DUID. . . . . . . . : 00-01-00-01-2E-C2-7B-59-D0-C1-B5-39-19-5E
   NetBIOS over Tcpip. . . . . . . . : Enabled

Unknown adapter Local Area Connection:

   Media State . . . . . . . . . . . : Media disconnected
   Connection-specific DNS Suffix  . :
   Description . . . . . . . . . . . : TAP-Windows Adapter V9
   Physical Address. . . . . . . . . : 00-FF-4A-DB-27-7C
   DHCP Enabled. . . . . . . . . . . : Yes
   Autoconfiguration Enabled . . . . : Yes

Wireless LAN adapter Local Area Connection* 1:

   Media State . . . . . . . . . . . : Media disconnected
   Connection-specific DNS Suffix  . :
   Description . . . . . . . . . . . : Microsoft Wi-Fi Direct Virtual Adapter
   Physical Address. . . . . . . . . : DC-97-BA-E9-20-6F
   DHCP Enabled. . . . . . . . . . . : Yes
   Autoconfiguration Enabled . . . . : Yes

Wireless LAN adapter Local Area Connection* 2:

   Media State . . . . . . . . . . . : Media disconnected
   Connection-specific DNS Suffix  . :
   Description . . . . . . . . . . . : Microsoft Wi-Fi Direct Virtual Adapter #2
   Physical Address. . . . . . . . . : DE-97-BA-E9-20-6E
   DHCP Enabled. . . . . . . . . . . : Yes
   Autoconfiguration Enabled . . . . : Yes

Wireless LAN adapter Wi-Fi:

   Connection-specific DNS Suffix  . :
   Description . . . . . . . . . . . : Intel(R) Wi-Fi 6 AX201 160MHz
   Physical Address. . . . . . . . . : DC-97-BA-E9-20-6E
   DHCP Enabled. . . . . . . . . . . : Yes
   Autoconfiguration Enabled . . . . : Yes
   IPv6 Address. . . . . . . . . . . : 2409:40f4:32:8ece:f5e3:8a1a:6fa:9fe7(Preferred)
   Temporary IPv6 Address. . . . . . : 2409:40f4:32:8ece:48cb:9eb6:d330:fe9b(Preferred)
   Link-local IPv6 Address . . . . . : fe80::d827:63e8:1a3b:2d20%8(Preferred)
   IPv4 Address. . . . . . . . . . . : 10.117.17.164(Preferred)
   Subnet Mask . . . . . . . . . . . : 255.255.255.0
   Lease Obtained. . . . . . . . . . : 21 August 2026 9.32.46 PM
   Lease Expires . . . . . . . . . . : 21 August 2026 10.32.44 PM
   Default Gateway . . . . . . . . . : fe80::286d:57ff:fead:d119%8
                                       10.117.17.140
   DHCP Server . . . . . . . . . . . : 10.117.17.140
   DHCPv6 IAID . . . . . . . . . . . : 131897274
   DHCPv6 Client DUID. . . . . . . . : 00-01-00-01-2E-C2-7B-59-D0-C1-B5-39-19-5E
   DNS Servers . . . . . . . . . . . : 10.117.17.140
                                       2409:40f4:32:8ece::6f
   NetBIOS over Tcpip. . . . . . . . : Enabled

Ethernet adapter Ethernet:

   Media State . . . . . . . . . . . : Media disconnected
   Connection-specific DNS Suffix  . :
   Description . . . . . . . . . . . : Realtek PCIe GbE Family Controller
   Physical Address. . . . . . . . . : D0-C1-B5-39-19-5E
   DHCP Enabled. . . . . . . . . . . : Yes
   Autoconfiguration Enabled . . . . : Yes

C:\Users\dhars>ipconfig /release

Windows IP Configuration

No operation can be performed on Local Area Connection while it has its media disconnected.
No operation can be performed on Local Area Connection* 1 while it has its media disconnected.
No operation can be performed on Local Area Connection* 2 while it has its media disconnected.
No operation can be performed on Ethernet while it has its media disconnected.

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

   Connection-specific DNS Suffix  . :
   IPv6 Address. . . . . . . . . . . : 2409:40f4:32:8ece:f5e3:8a1a:6fa:9fe7
   Temporary IPv6 Address. . . . . . : 2409:40f4:32:8ece:48cb:9eb6:d330:fe9b
   Link-local IPv6 Address . . . . . : fe80::d827:63e8:1a3b:2d20%8
   Default Gateway . . . . . . . . . : fe80::286d:57ff:fead:d119%8

Ethernet adapter Ethernet:

   Media State . . . . . . . . . . . : Media disconnected
   Connection-specific DNS Suffix  . :

C:\Users\dhars>ipconfig /renew

Windows IP Configuration

No operation can be performed on Local Area Connection while it has its media disconnected.
No operation can be performed on Local Area Connection* 1 while it has its media disconnected.
No operation can be performed on Local Area Connection* 2 while it has its media disconnected.
No operation can be performed on Ethernet while it has its media disconnected.

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

   Connection-specific DNS Suffix  . :
   IPv6 Address. . . . . . . . . . . : 2409:40f4:32:8ece:f5e3:8a1a:6fa:9fe7
   Temporary IPv6 Address. . . . . . : 2409:40f4:32:8ece:48cb:9eb6:d330:fe9b
   Link-local IPv6 Address . . . . . : fe80::d827:63e8:1a3b:2d20%8
   IPv4 Address. . . . . . . . . . . : 10.117.17.164
   Subnet Mask . . . . . . . . . . . : 255.255.255.0
   Default Gateway . . . . . . . . . : fe80::286d:57ff:fead:d119%8
                                       10.117.17.140

Ethernet adapter Ethernet:

   Media State . . . . . . . . . . . : Media disconnected
   Connection-specific DNS Suffix  . :

C:\Users\dhars>ping google.com

Pinging google.com [2404:6800:4007:808::200e] with 32 bytes of data:
Reply from 2404:6800:4007:808::200e: time=129ms
Reply from 2404:6800:4007:808::200e: time=24ms
Reply from 2404:6800:4007:808::200e: time=33ms
Reply from 2404:6800:4007:808::200e: time=63ms

Ping statistics for 2404:6800:4007:808::200e:
    Packets: Sent = 4, Received = 4, Lost = 0 (0% loss),
Approximate round trip times in milli-seconds:
    Minimum = 24ms, Maximum = 129ms, Average = 62ms

C:\Users\dhars>tracert google.com

Tracing route to google.com [2404:6800:4007:808::200e]
over a maximum of 30 hops:

  1     7 ms     5 ms     3 ms  2409:40f4:32:8ece::6f
  2     *        *        *     Request timed out.
  3    94 ms    31 ms    49 ms  2405:200:5218:21:3925::1
  4    17 ms    31 ms    17 ms  2405:200:88c:1513:62::4
  5     *        *        *     Request timed out.
  6    29 ms    57 ms    24 ms  2405:200:801:900::1624
  7     *        *        *     Request timed out.
  8    56 ms   189 ms    38 ms  2001:4860:1:1::170
  9   186 ms    60 ms    50 ms  2001:4860:1:1::170
 10    45 ms   177 ms    21 ms  2404:6800:8202:480::1
 11   116 ms    40 ms    45 ms  maa05s10-in-x0e.1e100.net [2404:6800:4007:808::200e]

Trace complete.

C:\Users\dhars>nslookup google.com
Server:  UnKnown
Address:  10.117.17.140

Non-authoritative answer:
Name:    google.com
Addresses:  2404:6800:4007:835::200e
          142.251.220.110


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
  TCP    0.0.0.0:49671          Dharshan:0             LISTENING
  TCP    10.117.17.164:139      Dharshan:0             LISTENING
  TCP    127.0.0.1:8884         Dharshan:0             LISTENING
  TCP    127.0.0.1:19294        Dharshan:0             LISTENING
  TCP    127.0.0.1:53610        Dharshan:65001         ESTABLISHED
  TCP    127.0.0.1:54143        Dharshan:0             LISTENING
  TCP    127.0.0.1:56198        Dharshan:0             LISTENING
  TCP    127.0.0.1:61578        Dharshan:0             LISTENING
  TCP    127.0.0.1:65001        Dharshan:0             LISTENING
  TCP    127.0.0.1:65001        Dharshan:53610         ESTABLISHED
  TCP    192.168.56.1:139       Dharshan:0             LISTENING
  TCP    [::]:135               Dharshan:0             LISTENING
  TCP    [::]:445               Dharshan:0             LISTENING
  TCP    [::]:49664             Dharshan:0             LISTENING
  TCP    [::]:49665             Dharshan:0             LISTENING
  TCP    [::]:49666             Dharshan:0             LISTENING
  TCP    [::]:49667             Dharshan:0             LISTENING
  TCP    [::]:49668             Dharshan:0             LISTENING
  TCP    [::]:49671             Dharshan:0             LISTENING
  TCP    [::1]:49669            Dharshan:0             LISTENING
  TCP    [2409:40f4:32:8ece:48cb:9eb6:d330:fe9b]:49678  [2603:1061:14:154::1]:https  ESTABLISHED
  TCP    [2409:40f4:32:8ece:48cb:9eb6:d330:fe9b]:50132  whatsapp-cdn6-shv-02-maa5:https  ESTABLISHED
  TCP    [2409:40f4:32:8ece:48cb:9eb6:d330:fe9b]:50282  [64:ff9b::14b8:af08]:https  ESTABLISHED
  TCP    [2409:40f4:32:8ece:48cb:9eb6:d330:fe9b]:51112  sg-in-f188:5228        ESTABLISHED
  TCP    [2409:40f4:32:8ece:48cb:9eb6:d330:fe9b]:51528  [64:ff9b::d4e:6da3]:https  ESTABLISHED
  TCP    [2409:40f4:32:8ece:48cb:9eb6:d330:fe9b]:51990  [64:ff9b::d59:b30c]:https  TIME_WAIT
  TCP    [2409:40f4:32:8ece:48cb:9eb6:d330:fe9b]:53264  sg-in-f188:5228        ESTABLISHED
  TCP    [2409:40f4:32:8ece:48cb:9eb6:d330:fe9b]:54845  [2603:1061:14:151::1]:https  ESTABLISHED
  TCP    [2409:40f4:32:8ece:48cb:9eb6:d330:fe9b]:57344  lb-140-82-114-26-iad:https  ESTABLISHED
  TCP    [2409:40f4:32:8ece:48cb:9eb6:d330:fe9b]:61407  cm-in-f95:https        TIME_WAIT
  TCP    [2409:40f4:32:8ece:48cb:9eb6:d330:fe9b]:62390  [64:ff9b::14b8:af08]:https  ESTABLISHED
  TCP    [2409:40f4:32:8ece:48cb:9eb6:d330:fe9b]:62652  lcbomp-in-f84:https    TIME_WAIT
  TCP    [2409:40f4:32:8ece:48cb:9eb6:d330:fe9b]:64948  [2603:1040:a06:6::]:https  ESTABLISHED
  TCP    [2409:40f4:32:8ece:48cb:9eb6:d330:fe9b]:64949  [2603:1040:a06:6::]:https  ESTABLISHED
  TCP    [2409:40f4:32:8ece:48cb:9eb6:d330:fe9b]:65308  lb-140-82-114-21-iad:https  ESTABLISHED
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
  UDP    0.0.0.0:54818          *:*
  UDP    0.0.0.0:63418          *:*
  UDP    10.117.17.164:137      *:*
  UDP    10.117.17.164:138      *:*
  UDP    10.117.17.164:1900     *:*
  UDP    10.117.17.164:5353     *:*
  UDP    10.117.17.164:56623    *:*
  UDP    127.0.0.1:1900         *:*
  UDP    127.0.0.1:10040        *:*
  UDP    127.0.0.1:55757        127.0.0.1:55757
  UDP    127.0.0.1:55758        *:*
  UDP    127.0.0.1:55771        *:*
  UDP    127.0.0.1:56624        *:*
  UDP    192.168.56.1:137       *:*
  UDP    192.168.56.1:138       *:*
  UDP    192.168.56.1:1900      *:*
  UDP    192.168.56.1:5353      *:*
  UDP    192.168.56.1:56622     *:*
  UDP    [::]:5353              *:*
  UDP    [::]:5353              *:*
  UDP    [::]:5353              *:*
  UDP    [::]:5353              *:*
  UDP    [::]:5353              *:*
  UDP    [::]:5355              *:*
  UDP    [::]:54818             *:*
  UDP    [::]:63419             *:*
  UDP    [::1]:1900             *:*
  UDP    [::1]:5353             *:*
  UDP    [::1]:56621            *:*
  UDP    [fe80::7767:e1b4:ab93:3ee6%5]:1900  *:*
  UDP    [fe80::7767:e1b4:ab93:3ee6%5]:56619  *:*
  UDP    [fe80::d827:63e8:1a3b:2d20%8]:546  *:*
  UDP    [fe80::d827:63e8:1a3b:2d20%8]:1900  *:*
  UDP    [fe80::d827:63e8:1a3b:2d20%8]:56620  *:*

C:\Users\dhars>netstat -r
===========================================================================
Interface List
  5...0a 00 27 00 00 05 ......VirtualBox Host-Only Ethernet Adapter
  7...00 ff 4a db 27 7c ......TAP-Windows Adapter V9
 16...dc 97 ba e9 20 6f ......Microsoft Wi-Fi Direct Virtual Adapter
 14...de 97 ba e9 20 6e ......Microsoft Wi-Fi Direct Virtual Adapter #2
  8...dc 97 ba e9 20 6e ......Intel(R) Wi-Fi 6 AX201 160MHz
 11...d0 c1 b5 39 19 5e ......Realtek PCIe GbE Family Controller
  1...........................Software Loopback Interface 1
===========================================================================

IPv4 Route Table
===========================================================================
Active Routes:
Network Destination        Netmask          Gateway       Interface  Metric
          0.0.0.0          0.0.0.0    10.117.17.140    10.117.17.164     50
      10.117.17.0    255.255.255.0         On-link     10.117.17.164    306
    10.117.17.164  255.255.255.255         On-link     10.117.17.164    306
    10.117.17.255  255.255.255.255         On-link     10.117.17.164    306
        127.0.0.0        255.0.0.0         On-link         127.0.0.1    331
        127.0.0.1  255.255.255.255         On-link         127.0.0.1    331
  127.255.255.255  255.255.255.255         On-link         127.0.0.1    331
     192.168.56.0    255.255.255.0         On-link      192.168.56.1    281
     192.168.56.1  255.255.255.255         On-link      192.168.56.1    281
   192.168.56.255  255.255.255.255         On-link      192.168.56.1    281
        224.0.0.0        240.0.0.0         On-link         127.0.0.1    331
        224.0.0.0        240.0.0.0         On-link      192.168.56.1    281
        224.0.0.0        240.0.0.0         On-link     10.117.17.164    306
  255.255.255.255  255.255.255.255         On-link         127.0.0.1    331
  255.255.255.255  255.255.255.255         On-link      192.168.56.1    281
  255.255.255.255  255.255.255.255         On-link     10.117.17.164    306
===========================================================================
Persistent Routes:
  None

IPv6 Route Table
===========================================================================
Active Routes:
 If Metric Network Destination      Gateway
  8     66 ::/0                     fe80::286d:57ff:fead:d119
  1    331 ::1/128                  On-link
  8     66 2409:40f4:32:8ece::/64   On-link
  8    306 2409:40f4:32:8ece:48cb:9eb6:d330:fe9b/128
                                    On-link
  8    306 2409:40f4:32:8ece:f5e3:8a1a:6fa:9fe7/128
                                    On-link
  5    281 fe80::/64                On-link
  8    306 fe80::/64                On-link
  5    281 fe80::7767:e1b4:ab93:3ee6/128
                                    On-link
  8    306 fe80::d827:63e8:1a3b:2d20/128
                                    On-link
  1    331 ff00::/8                 On-link
  5    281 ff00::/8                 On-link
  8    306 ff00::/8                 On-link
===========================================================================
Persistent Routes:
  None

C:\Users\dhars>arp -a

Interface: 192.168.56.1 --- 0x5
  Internet Address      Physical Address      Type
  192.168.56.255        ff-ff-ff-ff-ff-ff     static
  224.0.0.2             01-00-5e-00-00-02     static
  224.0.0.22            01-00-5e-00-00-16     static
  224.0.0.251           01-00-5e-00-00-fb     static
  224.0.0.252           01-00-5e-00-00-fc     static
  239.255.255.250       01-00-5e-7f-ff-fa     static

Interface: 10.117.17.164 --- 0x8
  Internet Address      Physical Address      Type
  10.117.17.140         2a-6d-57-ad-d1-19     dynamic
  10.117.17.255         ff-ff-ff-ff-ff-ff     static
  224.0.0.22            01-00-5e-00-00-16     static
  224.0.0.251           01-00-5e-00-00-fb     static
  224.0.0.252           01-00-5e-00-00-fc     static
  239.255.255.250       01-00-5e-7f-ff-fa     static
  255.255.255.255       ff-ff-ff-ff-ff-ff     static
```
## Result
Thus Execution of Network commands Performed 
