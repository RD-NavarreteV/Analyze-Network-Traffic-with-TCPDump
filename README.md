<h1>Analyze Network Traffic with TCPDump</h1>

<h2>Description</h2>
In the realm of network diagnostics and security, understanding the intricacies of data transmission is crucial. "Analyzing Network Traffic with TCPDump" offers a comprehensive guide on leveraging TCPDump, a powerful packet analyzer, to inspect and interpret network traffic effectively.
tcpdump is a powerful command-line packet analyzer that allows you to capture and analyze network traffic on a Unix or Linux-based system. Here are some commonly used tcpdump commands with explanations:

These are just some examples of tcpdump commands, and the tool offers a wide range of options for more advanced filtering and analysis. Always refer to the tcpdump manual (man tcpdump) for a comprehensive list of options and usage details.

<br />
<br />
<h2>Project Tasks</h2>
<br />

- <b>Task 1: Overview and warm up</b>
  - [Overview and warm up](https://github.com/RD-NavarreteV/Analyze-Network-Traffic-with-TCPDump/blob/main/Tasks1-Warm-Up.md)
 
- <b>Task 2: Create shell script and explore more options</b>
  - [Create shell script and explore more options](https://github.com/RD-NavarreteV/Task2/blob/main/Create%20Shell%20Script%20.md)
 
- <b>Task 3: Create and read dump files</b>
  - [Create and read dump files](https://github.com/RD-NavarreteV/TCPDumpTask3/blob/main/Save%20Captured%20Packets.md)
 
- <b>Task 4: Create sequence of dump files with size and time limits</b>
  - [Create sequence of dump files with size and time limits](https://github.com/RD-NavarreteV/TCPDumpTask4/blob/main/Set%20Time%20and%20Size%20Limits.md)
 
- <b>Task 5: Advanced expressions for more filtering options</b>
  - [Advanced expressions for more filtering options](https://github.com/RD-NavarreteV/TCPDumpTask5/blob/main/Advanced%20Filtering%20.md)
 
<br />

<h2>Languages and Utilities Used</h2>

- <b>Linux Terminal</b> 
- <b>TCPDump</b>

<h2>Environments Used </h2>

- <b>Ubuntu Linux</b>

<h2>Top commands for TCPDump:</h2>

<br />
Basic Packet Capture:<br /><br />
-i: Specifies the network interface to capture packets from.
Example: tcpdump -i eth0: <br/>
<img src="https://i.imgur.com/rBG1Nqq.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Capture Packets with Specific Port:<br /><br />
Capture packets on a specific port.<br />
Example: tcpdump -i eth0 port 80 
<img src="https://i.imgur.com/UFfT5Is.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Display Packet Details in ASCII:<br /><br />
-A: Display packet details in ASCII.<br />
Example: tcpdump -A -i eth0
<img src="https://i.imgur.com/sanKEVS.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Capture and Save to a File:<br /><br />
-w: Write the raw packets to a file for later analysis.<br />
Example: tcpdump -i eth0 -w output.pcap
<img src="https://i.imgur.com/BeFRfEM.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Display Packet Timestamps:<br /><br />
-tttt: Display timestamps for each packet.<br />
Example: tcpdump -tttt -i eth0
<img src="https://i.imgur.com/BzivB1k.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Filter by IP Address:<br /><br />
Capture packets involving a specific IP address.<br />
Example: tcpdump -i eth0 host 192.168.1.1
<img src="https://i.imgur.com/WEo6OEv.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Filter by Source or Destination IP:<br /><br />
Capture packets with a specific source or destination IP address.<br />
Example: tcpdump -i eth0 src 192.168.1.2
<img src="https://i.imgur.com/G70XcSO.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Capture ICMP (Ping) Packets:<br /><br />
Capture ICMP packets.<br />
Example: tcpdump -i eth0 icmp
<img src="https://i.imgur.com/jMW659Q.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Capture Only N Packets:<br /><br />
-c: Capture only a specified number of packets.<br />
Example: tcpdump -i eth0 -c 10
<img src="https://i.imgur.com/BqaPTZ2.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Display Captured Packets in Real Time:<br /><br />
-n: Don't resolve hostnames.<br />
-l: Line-buffered output (useful for real-time display).<br />
Example: tcpdump -i eth0 -n -l
<img src="https://i.imgur.com/NKM9HhU.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Capture Specific Protocol:<br /><br />
Capture packets of a specific protocol (e.g., tcp, udp, arp).<br />
Example: tcpdump -i eth0 tcp
<img src="https://i.imgur.com/HWNjnQB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
<br />
</p>

<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
