<h1>Task 5: Advanced Filtering with TCP Dump</h1>
<h2>Objective:</h2>
•	Learn to create advanced packet capture filters using expressions in TCP dump.
<br />
<br />
<br /><h2>Steps:</h2>
<h3>1.	Create a New Shell Script:</h3>
<br />•	Create a new shell script file named advanced_capture.sh.
<br /><br /><h3>2.	Build TCP Dump Command with Expression:</h3>
<br />•	Use the following TCP dump command with an advanced filter expression:
<br />tcpdump -n -XX -tttt 'tcp[12:1] & 0xf0 >> 2 = 0x47 and tcp[((tcp[12:1] & 0xf0) >> 2):4] = 0x47455420' -w capture.pcap 
<br /><br />•	Breakdown of the expression:
<br />•	Extract the TCP header length offset.
<br />•	Capture packets with a GET request (hex values for "GET ").
<img src="-" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br /><br /><h3>3.	Execute the Script:</h3>
<br />•	Give execution permissions: chmod +x advanced_capture.sh
<br />•	Run the script: ./advanced_capture.sh
<br /><br /><h3>4.	Generate GET Requests:</h3>
<br />•	Use a web browser or tools to generate GET requests to a website.
<br />•	For example, access a website that allows you to submit a GET request, such as a search form.
<br /><br /><h3>5.	Analyze Captured Packets:</h3>
<br />•	After generating GET requests, interrupt the script (Ctrl+C).
<br />•	Open the generated capture.pcap file with Wireshark for detailed packet analysis.
<br /><br /><h3>6.	Understand the Expression:</h3>
<br />•	Break down the filter expression to understand how it selects packets.
<br />•	Focus on the TCP header offset and the comparison for GET requests.
<br /><br /><h3>7.	Explore Advanced Expressions:</h3>
<br />•	Research and experiment with different filter expressions to capture specific types of traffic.
<br />•	Utilize online resources or TCP dump documentation for advanced filter options.
<br /><br /><h3>8.	Review the Cumulative Challenge:</h3>
<br />•	Consider participating in the cumulative challenge provided to test your understanding and application of the learned skills.
<br /><br />Conclusion:
<br />•	Understand the capability of TCP dump expressions for advanced packet filtering.
<br />•	Explore the flexibility to capture specific types of network traffic based on detailed conditions.
<br />
