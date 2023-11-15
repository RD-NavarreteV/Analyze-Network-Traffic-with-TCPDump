<h1>Analyze Network Traffic with TCPDump</h1>

<h2>Description</h2>
In the realm of network diagnostics and security, understanding the intricacies of data transmission is crucial. "Analyzing Network Traffic with TCPDump" offers a comprehensive guide on leveraging TCPDump, a powerful packet analyzer, to inspect and interpret network traffic effectively.
tcpdump is a powerful command-line packet analyzer that allows you to capture and analyze network traffic on a Unix or Linux-based system. Here are some commonly used tcpdump commands with explanations:

1. Basic Packet Capture:
  -i: Specifies the network interface to capture packets from.
Example: tcpdump -i eth0

2. Capture Packets with Specific Port:
  Capture packets on a specific port.
Example: tcpdump -i eth0 port 80

3. Display Packet Details in ASCII:
  -A: Display packet details in ASCII.
Example: tcpdump -A -i eth0

4. Capture and Save to a File:
  -w: Write the raw packets to a file for later analysis.
Example: tcpdump -i eth0 -w output.pcap

5. Display Packet Timestamps:
  -tttt: Display timestamps for each packet.
Example: tcpdump -tttt -i eth0

6. Filter by IP Address:
  Capture packets involving a specific IP address.
Example: tcpdump -i eth0 host 192.168.1.1

7. Filter by Source or Destination IP:
  Capture packets with a specific source or destination IP address.
Example: tcpdump -i eth0 src 192.168.1.2

8. Capture ICMP (Ping) Packets:
  Capture ICMP packets.
Example: tcpdump -i eth0 icmp

9. Capture Only N Packets:
  -c: Capture only a specified number of packets.
Example: tcpdump -i eth0 -c 10

10. Display Captured Packets in Real Time:
  -n: Don't resolve hostnames.
-l: Line-buffered output (useful for real-time display).
Example: tcpdump -i eth0 -n -l

11. Capture Specific Protocol:
  Capture packets of a specific protocol (e.g., tcp, udp, arp).
Example: tcpdump -i eth0 tcp

These are just some examples of tcpdump commands, and the tool offers a wide range of options for more advanced filtering and analysis. Always refer to the tcpdump manual (man tcpdump) for a comprehensive list of options and usage details.



<br />


<h2>Languages and Utilities Used</h2>

- <b>Ubuntu Terminal</b> 
- <b>TCPDump</b>

<h2>Environments Used </h2>

- <b>Ubuntu Linux</b> (21H2)

<h2>Program walk-through:</h2>

<p align="center">
Launch the utility: <br/>
<img src="https://i.imgur.com/62TgaWL.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Select the disk:  <br/>
<img src="https://i.imgur.com/tcTyMUE.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Enter the number of passes: <br/>
<img src="https://i.imgur.com/nCIbXbg.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Confirm your selection:  <br/>
<img src="https://i.imgur.com/cdFHBiU.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Wait for process to complete (may take some time):  <br/>
<img src="https://i.imgur.com/JL945Ga.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Sanitization complete:  <br/>
<img src="https://i.imgur.com/K71yaM2.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Observe the wiped disk:  <br/>
<img src="https://i.imgur.com/AeZkvFQ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
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
