Download Link: https://assignmentchef.com/product/solved-cs352-assignment-project-2-mininet
<br>
<h1>Objective</h1>

The objective of this project is to become familiar with Networking and Mininet.  This will be done using the following assessments:

<h1>Description</h1>

Software Installation

<strong>Note 1: </strong>This assignment/project is based on the fact that you will use your personal laptop to run Wireshark. Also, the laptop in use is connected to the Internet through a Wi-Fi router (Access point), at home or somewhere else.

<strong>Note 2:</strong> Make sure to clear your web browser’s cache. We <strong>HIGHLY</strong> recommend running everything from the virtual machine.

<ul>

 <li>Please review the slides in the links below to install Mininet on your virtual machine. Typically this will already have python installed.</li>

</ul>

<a href="http://mininet.org/walkthrough/">http://mininet.org/walkthrough/</a>




Submission Instructions

Please work through each of the tasks discussed below. Each task will specify the material you are required to hand in. You will need to cut several snapshots and put them into a document and convert that document (if possible) to a PDF file. For submission please submit the PDF file (with your NetID as its name) via Sakai.

For presenting your answers

<ul>

 <li>Submit <strong>one PDF </strong>document with a summary of all your answers including the images that you have captured.

  <ol>

   <li>(Exclusion of this PDF Summary will result in a reduction in your grade.)</li>

   <li>Convert the word or google doc to a PDF</li>

   <li>DO NOT include the PDF in a zip file. It should be at the top level of your submission</li>

  </ol></li>

 <li>Be sure to include your name and NetID in your submission</li>

 <li>Label or number the answer for each question. For example the answer for 3a should be labeled <strong>3a </strong>or <strong>Question 3 Part a. </strong></li>

 <li>Be sure to answer all questions</li>

 <li>Be sure to include all other files requested by each question</li>

 <li>Provide citations for any references used</li>

 <li><strong>Due date:</strong> August, 7th @ 11:55 PM</li>

</ul>

<strong> </strong>

<h1></h1>

<h1>Assignment</h1>

<h2>1- Networking Setup</h2>

<strong>Note:</strong> The following tasks should be performed in the <strong>terminal</strong> of the VM containing Mininet or the terminal of your local machine. This should NOT be run in mininet

<ul>

 <li>Print the list of network interfaces, their MAC addresses, and their assigned IP addresses, if any. Include a screenshot here. <strong>Hint:</strong> use the ifconfig command.</li>

</ul>







<ul>

 <li>Using the ping command, calculate the latency between mininet VM and the websites for 10 packets. <strong>Hint:</strong> use the following format ping <em>website</em> -c 10</li>

</ul>

<ol>

 <li>Write down the latency for the following websites: <a href="http://www.rutgers.edu">rutgers.edu</a> <a href="http://www.stanford.edu">www.berkley.edu</a>, and <a href="https://www.google.co.in">www.google.co.in</a>.</li>

 <li>Compare the difference in latency.</li>

</ol>




<ul>

 <li>Let’s examine the routers between two servers. <strong>Hint:</strong> use the traceroute command</li>

</ul>

<ol>

 <li>List the routers between mininet VM and <a href="http://www.rutgers.edu">rutgers.edu</a>. Include a screenshot of this.</li>

 <li>Can you explain where the first two routers in the path are located?</li>

</ol>




<ul>

 <li>Go to the website <a href="https://whois.icann.org">https://whois.icann.org</a> and obtain the list of name servers for the domain abc.com. Include a screenshot.</li>

</ul>

<strong> </strong>

<h2></h2>

<h2>2- Mininet</h2>

<strong>Note:</strong> The following tasks should be performed in Mininet

Create a simple two-node network (h1 and h2, with a switch s1 in the middle) using “sudo mn” and do the following exercises.

<ul>

 <li>Print the MAC address of host h1 and include a screenshot of this. Print the MAC addresses of switch s1 and include a screenshot of this.</li>

</ul>

<ol>

 <li>Explain the different interfaces that s1 has.</li>

</ol>

<ul>

 <li>Ping h1 from h2. Include a screenshot.</li>

</ul>

<ol start="2">

 <li>View the ARP entries stored at hosts h1 and h2. Include a screenshot.</li>

</ol>

<ul>

 <li>Throughput is another performance measure in computer networks. <em>You may read about it online</em>.</li>

</ul>




Measure the TCP throughput from h1 to h2 using iperf. Include a screenshot.




<ul>

 <li>Delete the mininet topology by exiting mininet. Recreate a custom topology in which links have a capacity of 10 Mbps and latency of 100 ms. See the example below from <a href="http://mininet.org/walkthrough/#changing-topology-size-and-type">http://mininet.org/walkthrough/#changing-topology-size-and-type</a>:</li>

</ul>

<ol>

 <li>In the new topology, measure the average ping latency for <strong>five</strong> Include a screenshot.</li>

 <li>Some pings will take longer than others. For example the first ping is usually longer than the others. Why does this happen?</li>

</ol>

<ul>

 <li>In the new topology, measure the throughput from h1 to h2 using iperf. Include a screenshot of this.</li>

</ul>

<ol>

 <li>Would the throughput be different if link latencies were 20 ms instead of 100 ms?</li>

</ol>







<h1>Sources</h1>

This assignment was created and modified with permission from the sources below:

<ul>

 <li>Introduction to the Prototyping Project</li>

</ul>

<a href="http://www.winlab.rutgers.edu/comnet2/Projects/documents/intro_proto.pdf">http://www.winlab.rutgers.edu/comnet2/Projects/documents/intro_proto.pdf</a>

<ul>

 <li>Communication Networks II Assignment 1: Networking Set-up</li>

</ul>

<a href="http://www.winlab.rutgers.edu/comnet2/Projects/documents/assignment1_comnets2_2020.pdf">http://www.winlab.rutgers.edu/comnet2/Projects/documents/assignment1_comnets2_2020.pdf</a>











