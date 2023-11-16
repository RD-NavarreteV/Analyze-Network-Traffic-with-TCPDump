<h1>Task 3: Save Captured Packets and Analyze with Wireshark</h1>
<h2>Objective:</h2>
•	Learn how to save captured packets to a dump file using TCP dump.
<br />•	Use Wireshark to analyze the contents of the captured dump file.
<br />
<br /><h2>Steps:</h2>
<h3>1.	Capture Packets and Save to Dump File:</h3>
<img src="https://i.imgur.com/XhwHRf1.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/7i95Khr.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
•	Execute the TCP dump command with the -w option to write the captured packets to a dump file named capture.pcap.
<br />tcpdump -n -t -c 10 -w capture.pcap 
<br />•	Generate traffic by accessing the specified website (e.g., skyward66.com) and allow TCP dump to capture 10 packets.
<br /><br /><h3>2.	Explore the Dump File:</h3>
<img src="https://i.imgur.com/wGJyMSH.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/sLBf7Y5.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
•	Open the dump file using TCP dump and examine the captured packets:
<br />tcpdump -r capture.pcap -XX -tttt 
<br />•	Observe the contents of the dump file as if it were freshly captured on the wire.
<br /><br /><h3>3.	Open Wireshark:</h3>
<img src="https://i.imgur.com/8LUtOdl.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
•	Open a new terminal and type wireshark to launch the Wireshark application.
<br /><br /><h3>4.	Load Captured Dump File in Wireshark:</h3>
<img src="https://i.imgur.com/0RCCxvy.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/d9vDMWx.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
•	In Wireshark, click on the folder icon to open a file.
<br />•	Navigate to the location where the dump file is saved (e.g., desktop/capture.pcap).
<br />•	Open the dump file.
<br /><br /><h3>5.	Analyze Captured Packets in Wireshark:</h3>
<img src="https://i.imgur.com/9bK7z1T.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/kF21w5K.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
•	Wireshark displays the captured packets in a user-friendly format.
<br />•	Explore the details of each packet, including source and destination IP addresses, protocols, lengths, and more.
<br />•	Click on a specific packet to view its breakdown and interpretation.
<br /><br /><h3>Understand Wireshark Features:</h3>
<br />•	Familiarize yourself with Wireshark's features, such as filtering, coloring rules, and packet details.
<br />•	Experiment with various options to customize the view based on your analysis needs.
<br /><br /><h3>Advanced Wireshark Features:</h3>
<br />•	Explore advanced features in Wireshark, such as packet coloring rules, filtering expressions, and protocol-specific analysis.
<br /><br /><h3>Understand the Value of Wireshark:</h3>
<br />•	Recognize the value of using Wireshark for in-depth packet analysis and visualization.
<br /><br /><h3>Conclusion: </h3>
<br />In this task, you've learned how to save captured packets to a dump file using TCP dump and analyze the contents of the dump file using Wireshark. Wireshark provides a user-friendly interface for detailed packet inspection and interpretation.
<br />
