<h1>Task 4: Set Time and Size Limits for Capturing Packets</h1>
<h2>Objective:</h2>
•	Learn how to create dump files with time and size limits using TCP dump.
<br />
<br />
<br /><h2>Steps:</h2>
<h3>1.	Create Dump File with Time Limit:</h3>
<br />•	Add the -G option to specify a time limit for the dump file in seconds.
<br /><br />Example: tcpdump -n -t -G 600 -w capture.pcap
<br />This command creates a dump file (capture.pcap) and updates it every 600 seconds (10 minutes).
<img src="-" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br /><br /><h3>2.	Generate Traffic and Test:</h3>
<br />•	Execute the script (./watch.sh) and generate traffic by accessing the specified website (e.g., skyward66.com).
<br />•	Observe that the dump file is updated at regular intervals (every 10 minutes) and contains recent traffic.
<br /><br /><h3>3.	Create Dump File with Size Limit:</h3>
<br />•	Add the -C option to specify a size limit for the dump file in million bytes.
<br /><br />Example: tcpdump -n -t -C 1 -w capture.pcap
<br />This command creates a dump file (capture.pcap) and generates a new file when it reaches 1 million bytes.
<br /><br /><h3>4.	Generate Traffic and Test Size Limit:</h3>
<br />•	Execute the script and generate a significant amount of traffic.
<br />•	Observe that the dump file size does not exceed 1 million bytes, and a new file is created when the limit is reached.
<br /><br /><h3>5.	Combine Time and Size Limits:</h3>
<br />•	Add both -G and -C options to create a dump file with time and size limits.
<br /><br />Example: tcpdump -n -t -G 600 -C 1 -w capture.pcap
<br />This command updates the dump file every 10 minutes and creates a new file when the size limit is reached.
<br /><br /><h3>6.	Generate Traffic and Test Combined Limits:</h3>
<br />•	Execute the script and generate traffic.
<br />•	Observe that the dump file is updated every 10 minutes and stays within the size limit.
<br /><br /><h3>7.	Understand Time and Size Limits:</h3>
<br />•	Acknowledge that the -G option sets the time limit in seconds, and the -C option sets the size limit in million bytes.
<br /><br /><h3>8.	Review and Cleanup:</h3>
<br />•	Check the generated dump files to see how they adhere to the specified time and size limits.
<br />•	Optionally, delete the dump files to keep your system clean.
<br /><br /><h3>9.	Optional Assessment Task:</h3>
<br />•	Consider participating in the optional assessment task provided to test your understanding.
<br /><br />Conclusion: In this task, you've learned how to set time and size limits for capturing packets using TCP dump. This is useful for creating manageable dump files for specific durations and preventing file sizes from becoming overly large.
<br />
