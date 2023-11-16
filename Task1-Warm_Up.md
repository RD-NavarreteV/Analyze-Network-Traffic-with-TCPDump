<h1>Task 1: Overview and Warm Up</h1>

<h3>1.	Execute Basic TCP Dump Command:</h3>
•	Type tcpdump in the terminal and observe the captured network traffic.
<br />
•	Note that it continuously captures packets until you stop it.
<img src="https://i.imgur.com/Y7nlhqk.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
<h3>2.	Stop TCP Dump:</h3>
•	To stop the TCP dump, press Ctrl + C in the terminal.
<img src="-" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
<h3>3.	Explore Basic TCP Dump Options:</h3>
•	Understand the basic options:</h3>
•	-c: Limit the number of packets to capture (e.g., tcpdump -c 10 captures the first 10 packets).
<br />
•	-n: Show numeric IP addresses.
<br />
•	-q: Quick (print less protocol information).
<br />
•	-A: Print each packet in ASCII.
<br />
•	-X: Show packet contents in both hex and ASCII.
<br />
<br />
<h3>4.	Capture and Display Packets with Limited Count:</h2>
•	Use the command tcpdump -c 10 -n -q to capture and display the first 10 packets with minimal information.
<img src="https://i.imgur.com/Y7nlhqk.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
<h3>5.	Display Packet Contents in ASCII:</h3>
•	Use the command tcpdump -A to display packet contents in ASCII.
<img src="-" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
<h3>6.	Display Packet Contents in Hex and ASCII:</h3>
•	Use the command tcpdump -XX to display packet contents in both hex and ASCII.
<img src="-" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
<h3>7.	Display Timestamps:</h3>
•	Use the command tcpdump -tttt to display timestamps for each packet.
<img src="-" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
<h3>8.	Show Available Network Interfaces:</h3>
•	Use the command tcpdump -D to list all available network interfaces.
<img src="-" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
<h3>9.	Filter by Interface:</h3>
•	Use the command tcpdump -i <interface> to capture packets only from a specific network interface (e.g., tcpdump -i ens5).
<img src="-" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
<h3>10.	Explore Time Stamps and Interfaces:</h3>
<img src="-" height="80%" width="80%" alt="Disk Sanitization Steps"/>
•	Use the command tcpdump -t -i ens5 to display human-readable time stamps for packets on a specific interface.
<br />
<br />
<h3>11.	Save for Later Analysis:</h3>
•	Optionally, use the command tcpdump -w <output_file> to save captured packets to a file for later analysis (e.g., tcpdump -w capture.pcap).
<img src="-" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
<h3>12.	Understand Other Options:</h3>
•	Explore other options by using man tcpdump to access the manual and learn more about available command-line options.
<img src="-" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
<h3>13.	Prepare for the Next Tasks:</h3>
•	Understand the objective of the project: to create a script to monitor traffic to a specific website (mindskywards66.com).
<img src="-" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
<h3>14.	Optional Content:</h3>
•	Explore optional tasks mentioned in the project to enhance learning.
<img src="-" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
<h3>15.	Bookmark Tabs:</h3>
•	Familiarize yourself with the tabs open in the browser, including Visual Studio Code, WireShark, and others.
<img src="-" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
<h3>Conclusion:</h3>
The warm-up task provides an introduction to TCP dump, its basic commands, and options. It sets the foundation for the subsequent tasks, where you'll create a script to monitor network traffic to a specific website.
<br />

<h2>Languages and Utilities Used</h2>

- <b>Linux Terminal</b> 
- <b>TCPDump</b>

<h2>Environments Used </h2>

- <b>Ubuntu Linux</b>


<br />
<br />
<br />
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

