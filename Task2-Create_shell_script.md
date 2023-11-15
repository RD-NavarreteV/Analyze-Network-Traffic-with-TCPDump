<h1>Task 2: Create Shell Script and Explore More Options</h1>
<h2>Objective:</h2>
<br />•	Create a shell script using Visual Studio Code.
<br />•	Explore additional options for TCP dump, such as filtering by host, port, and direction.
<br />•	Test the shell script to capture network traffic to a specific website.
<h2>Steps:</h2>
<br /><h3>1.	Open Visual Studio Code:</h3>
<br />•	Launch Visual Studio Code on your desktop.
<br /><br /><h3>2.	Open Integrated Terminal:</h3>
<br />•	Right-click on the Explorer panel and create a new file named watch.sh.
<br /><br /><h3>3.	Write the TCP Dump Command:</h3>
<br />•	In the watch.sh file, construct the TCP dump command:
<br />#!/bin/bash tcpdump -n -t -c 10 -XX host skyward66.com 
<img src="https://i.imgur.com/rBG1Nqq.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />•	This command captures the first 10 packets to and from skyward66.com and displays them in hex and ASCII.
<br /><br /><h3>4.	Save and Set Execution Permissions:</h3>
<br />•	Save the file and set execution permissions:
<br />chmod +x watch.sh 
<br /><br /><h3>5.	Open Integrated Terminal Again:</h3>
<br />•	Open an integrated terminal in Visual Studio Code.
<br /><br /><h3>6.	Execute the Shell Script:</h3>
<br />•	Run the shell script:
<br />./watch.sh 
<br />•	Observe the captured packets on the terminal.
<br /><br /><h3>7.	Filter by Port:</h3>
<br />•	Modify the TCP dump command to filter by port (e.g., HTTPS port 443):
<br />tcpdump -n -t -c 10 -XX port 443 
<br />•	Save the file, set execution permissions, and execute the updated script.
<br /><br /><h3>8.	Filter by Host and Port:</h3>
<br />•	Modify the TCP dump command to filter both by host and port:
<br />tcpdump -n -t -c 10 -XX host skyward66.com and port 443 
<br />•	Save the file, set execution permissions, and execute the updated script.
<br /><br /><h3>9.	Filter by Direction:</h3>
<br />•	Explore filtering by direction (source or destination):
<br />•	For incoming traffic: tcpdump -n -t -c 10 -XX src host skyward66.com
<br />•	For outgoing traffic: tcpdump -n -t -c 10 -XX dst host skyward66.com
<br />•	Save the file, set execution permissions, and test both directions.
<br /><br /><h3>10.	Explore Other Options:</h3>
<br />•	Experiment with other TCP dump options (e.g., -w for writing to a file) based on the project's requirements.
<br /><br /><h3>11.	Optional Assessment:</h3>
<br />•	Participate in the optional assessment to test your understanding of the concepts covered in Task 2.
<br /><br /><h3>12.	Conclusion:</h3>
<br />•	You've successfully created a shell script to capture network traffic using TCP dump with various filtering options. In the next task, you'll learn how to interpret the captured packets.
<br />
<br />
<br />
<br />
<br />