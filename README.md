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
  - [Overview and warm up](https://github.com/RD-NavarreteV/Analyze-Network-Traffic-with-TCPDump/blob/main/README.md)
 
- <b>Task 2: Create shell script and explore more options</b>
  - [Create shell script and explore more options](https://github.com/RD-NavarreteV/Analyze-Network-Traffic-with-TCPDump/blob/main/README.md)
 
- <b>Task 3: Create and read dump files</b>
  - [Create and read dump files](https://github.com/RD-NavarreteV/Analyze-Network-Traffic-with-TCPDump/blob/main/README.md)
 
- <b>Task 4: Create sequence of dump files with size and time limits</b>
  - [Create sequence of dump files with size and time limits](https://github.com/RD-NavarreteV/Analyze-Network-Traffic-with-TCPDump/blob/main/README.md)
 
- <b>Task 5: Advanced expressions for more filtering options</b>
  - [Advanced expressions for more filtering options](https://github.com/RD-NavarreteV/Analyze-Network-Traffic-with-TCPDump/blob/main/README.md)
 
<br />

<h2>Languages and Utilities Used</h2>

- <b>Linux Terminal</b> 
- <b>TCPDump</b>

<h2>Environments Used </h2>

- <b>Ubuntu Linux</b>

<h2>Top commands for TCPDump:</h2>

<br />
Basic Packet Capture:
  -i: Specifies the network interface to capture packets from.
Example: tcpdump -i eth0: <br/>
<br />
<img src="https://i.imgur.com/rBG1Nqq.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Capture Packets with Specific Port:
  Capture packets on a specific port.
Example: tcpdump -i eth0 port 80
<br />
<img src="https://i.imgur.com/UFfT5Is.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Display Packet Details in ASCII:
  -A: Display packet details in ASCII.
Example: tcpdump -A -i eth0
<br />
<img src="https://i.imgur.com/sanKEVS.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Capture and Save to a File:
  -w: Write the raw packets to a file for later analysis.
Example: tcpdump -i eth0 -w output.pcap
  <br />
<img src="https://i.imgur.com/BeFRfEM.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Display Packet Timestamps:
  -tttt: Display timestamps for each packet.
Example: tcpdump -tttt -i eth0
  <br />
<img src="https://i.imgur.com/BzivB1k.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Filter by IP Address:
  Capture packets involving a specific IP address.
Example: tcpdump -i eth0 host 192.168.1.1
  <br />
<img src="https://i.imgur.com/WEo6OEv.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Filter by Source or Destination IP:
  Capture packets with a specific source or destination IP address.
Example: tcpdump -i eth0 src 192.168.1.2
  <br />
<img src="https://i.imgur.com/G70XcSO.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Capture ICMP (Ping) Packets:
  Capture ICMP packets.
Example: tcpdump -i eth0 icmp
  <br />
<img src="https://i.imgur.com/jMW659Q.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Capture Only N Packets:
  -c: Capture only a specified number of packets.
Example: tcpdump -i eth0 -c 10
  <br />
<img src="https://i.imgur.com/BqaPTZ2.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Display Captured Packets in Real Time:
  -n: Don't resolve hostnames.
-l: Line-buffered output (useful for real-time display).
Example: tcpdump -i eth0 -n -l
  <br />
<img src="https://i.imgur.com/NKM9HhU.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Capture Specific Protocol:
  Capture packets of a specific protocol (e.g., tcp, udp, arp).
Example: tcpdump -i eth0 tcp
  <br />
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
