# cs6250-project-1--sdn-firewall-with-pox-spring25-solved



**<span style='color:red'>TO GET THIS SOLUTION VISIT:</span>** https://www.ankitcodinghub.com/product/cs6250-omscs-omscy-sdn-firewall-with-pox-solved/

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;126314&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;3&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (3 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CS6250 Project 1- SDN Firewall with POX SPRING25 Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">
            
<div class="kksr-stars">
    
<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">
            

<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">
            

<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">
            

<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">
            

<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">
            

<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
    
<div class="kksr-stars-active" style="width: 138px;">
            <div class="kksr-star" style="padding-right: 4px">
            

<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">
            

<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">
            

<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">
            

<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">
            

<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>
                

<div class="kksr-legend" style="font-size: 19.2px;">
            5/5 - (3 votes)    </div>
    </div>
<h1><a name="_Toc35937"></a>SDN&nbsp; Firewall&nbsp;&nbsp;&nbsp; with POX&nbsp; Project</h1>
&nbsp;

In this project, you will use Software Defined Networking (SDN) principles to create a configurable firewall using an OpenFlow enabled Switch. The Software Defined Networking (OpenFlow) functionality allows you to programmatically control the flow of traffic on the network.

This project has two phases (and one optional phase) as follows:

<ol>
<li>Mininet Tutorial – This phase is a brief overview of Mininet. There are no deliverables for this phase and may be skipped, especially if you completed the Optional Simulating Networks project (Project 0).&nbsp; You will find this information in Appendix D.</li>
<li>Wireshark Tutorial – This phase is a brief introduction to packet capture using Wireshark/tshark. You will examine the packet format for various traffic to learn of the different header values used in Phase 3.&nbsp; There is a deliverable of a simple packet capture file.</li>
<li>SDN Firewall – This phase involves completing code to build a simple traffic blocking firewall using OpenFlow with the POX Controller based on rules passed to it from a configuration file. In addition, you will create a set of rules to test the firewall implementation.</li>
</ol>
<h2><a name="_Toc35938"></a>Part&nbsp;&nbsp; 0:&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Project&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; References</h2>
&nbsp;

You will find the following resources useful in completing this project. It is recommended that you review these resources before starting the project.

<ul>
<li>IP Header Format – <u>https://erg.abdn.ac.uk/users/gorry/course/inet-pages/ip-packet.html</u></li>
<li>TCP Packet Header Format – <u>https://en.wikipedia.org/wiki/Transmission_Control_Protocol</u></li>
<li>UDP Packet Header Format – <u>https://en.wikipedia.org/wiki/User_Datagram_Protocol</u></li>
<li>The ICMP Protocol – <u>https://en.wikipedia.org/wiki/Internet_Control_Message_Protocol</u></li>
<li>IP Protocols – <u>https://en.wikipedia.org/wiki/List_of_IP_protocol_numbers</u></li>
<li>TCP and UDP Service and Port References – <u>https://en.wikipedia.org/wiki/List_of_TCP_and_UDP_port_numbers</u></li>
<li>Wireshark – <u>https://www.wireshark.org/docs/wsug_html/</u></li>
<li>CIDR Calculator – <u>https://account.arin.net/public/cidrCalculator</u></li>
<li>CIDR – <u>https://en.wikipedia.org/wiki/Classless_Inter-Domain_Routing</u> There are a few videos describing various aspects of the project:</li>
<li>Project Description – https://youtu.be/Kl4nRgoeLxw</li>
<li>Wireshark Tutorial – https://youtu.be/AnTi1m0imVk</li>
<li>IP Network Address / Subnets / CIDR – See Edstem</li>
<li>How to Manually Test – <u>https://youtu.be/dj323mdA3sg</u></li>
</ul>
&nbsp;

&nbsp;

<h2><a name="_Toc35939"></a>Part&nbsp;&nbsp; 1:&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Files&nbsp; Layout</h2>
&nbsp;

Unzip the SDNFirewall-Fall2024zip file into your Virtual Machine.&nbsp; You can extract to any folder on your system. Do this by running the following command:

&nbsp;

<h4>unzip SDNFirewall-Fall2024.zip</h4>
This will extract the files for this project into a directory named SDNFirewall at your current path (it is recommended that your use the mininet root directory to aid in troubleshooting (cd ~ ). The following files will be extracted:

<ul>
<li>sh – this file called by using following command line: <strong>./cleanup.sh</strong></li>
</ul>
This file will clean up the Mininet Environment and kill all zombie Python and POX processes.

<ul>
<li>sdn-topology.py – this file creates the Mininet topology used in this assignment. This is like what you created in the Simulating Networks project. When evaluating your code against the ruleset specified in this project, do not change it. However, you are encouraged to make your own topologies (and rules) to test the firewall. Look at the start-topology.sh file to see how to start a different topology.</li>
<li>ws-topology.py – this file is substantially like sdn-topology, but it does not call the POX Controller. You will use this during the <u>Wireshark</u></li>
<li>setup-firewall.py – this file sets up the frameworks used in this project. <strong><u>DO NOT MODIFY THIS FILE</u>. </strong>This file will create the appropriate POX framework and then integrates the rules implemented in sdnpy into the OpenFlow engine. It will also read in the values from the configure.pol file and validate that the entries are valid. If you make changes to this file, the autograder will likely have issues with your final code as the autograder uses the unaltered distribution version of this file.</li>
<li>start-firewall.sh – this is the shell script that starts the firewall. This file must be started before the topology is started. It will copy files to the appropriate directory and then start the POX OpenFlow controller. This file is called by using following command line: <strong>./start-firewall.sh</strong></li>
<li>start-topology.sh – this is the shell script that starts the Mininet topology used in the assignment. All it does is call the sdn-topology.py file with superuser permissions. This file is called by using following command line: <strong>./start-topology.sh</strong></li>
<li>test-client.py – this is a python test client program used to test your firewall. This file is called using the following command line: <strong>python test-client.py PROTO SERVERIP PORT SOURCEPORT</strong> where PROTO is either T for TCP, U for UDP, or G for GRE, SERVERIP is the IP address of the server (destination), PORT is the destination port, and optionally SOURCEPORT allows you to configure the source port that you are using.&nbsp; Example:&nbsp; <strong>python test-client.py T 10.0.1.1 80</strong></li>
<li>test-server.py – this is a python test server program used to test your firewall. This file is called using the following command line: <strong>python test-server.py PROTO SERVERIP PORT</strong> where PROTO is either T for TCP, U for UDP, G for GRE, SERVERIP is the IP address of the server (the server you are running this script on), and PORT is the service port.</li>
</ul>
<h4>Example:&nbsp; python test-server.py T 10.0.1.1 80</h4>
<ul>
<li>test-suite – This is a student developed test script that was developed in 2021 that can be used to test your implementation AFTER YOU FINISH BOTH THE IMPLEMENTATION FILES. The test cases in the main folder will be used to evaluate your implementations for the first run.&nbsp; An alternate configuration and topology will also be used to evaluate your implementations.&nbsp; This will be like, but not identical to what is found in the extra sub-folder.&nbsp; See Appendix A for information on how to use the test suite.</li>
</ul>
Project Deliverables

<ul>
<li>pol – this file is where you will supply the configuration to the firewall that specifies the traffic that should either be blocked or allowed (override blocks). The format of this file will be specified later in this document. <strong>This file is one of the deliverables that must be included in your ZIP submission to </strong></li>
</ul>
<table width="88">
<tbody>
<tr>
<td width="47"><strong>Canvas.</strong></td>
<td width="42"></td>
</tr>
<tr>
<td colspan="2" width="88">sdn-firewall.py</td>
</tr>
</tbody>
</table>
<ul>
<li>–This file implements the firewall using POX and OpenFlow functions. It receives a copy</li>
</ul>
of the contents of the configure.pol file as a python list containing a dictionary for each rule and you will need to implement the code necessary to process these items into POX policies to create the firewall.&nbsp; <strong>This file is one of the deliverables that must be included in your ZIP submission to Canvas.</strong>

<ul>
<li>pcap – This will be the packet capture completed in Part 4.<u> <strong>This file is one of the</strong></u><strong> <u>deliverables that must be included in your ZIP submission to Canvas.</u></strong></li>
</ul>
<h2><a name="_Toc35940"></a>Part&nbsp;&nbsp; 2:&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Mininet</h2>
&nbsp;

If you did not complete the Simulating Networks Optional Project, you may want to review the “Mininet Review” section in Appendix D to learn about the different aspects of how a mininet network is setup, including how to configure the physical topology and assignment of addresses to hosts and switches.

<h2><a name="_Toc35941"></a>Part&nbsp;&nbsp; 3:&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Wireshark</h2>
&nbsp;

Wireshark is a network packet capture program that will allow you to capture a stream of network packets and examine them. Wireshark is used extensively to troubleshoot computer networks and in the field of information security. We will be using Wireshark to examine the packet headers to learn how to use this information to match traffic that will be affected by the firewall we are constructing.

tshark is a command line version of Wireshark that we will be using to capture the packets between mininet hosts and we will use Wireshark for the GUI to examine these packets. However, you will be allowed to use the Wireshark GUI if you would like in doing the packet capture.

Please watch the Wireshark Tutorial Video if you would like to follow along in time for a live packet capture.

<ul>
<li>Step 1: Open up a Terminal Window and change directory to the SDNFirewall directory that was extracted in Part 1.</li>
</ul>
&nbsp;

<ul>
<li>Step 2: The first action is to <u>start up</u> the Mininet topology used for the <u>Wireshark</u> capture exercise. This topology matches the topology that you will be using when creating and testing your firewall. To start this topology, run the following command:</li>
</ul>
&nbsp;

<h4>sudo python ws-topology.py</h4>
&nbsp;

This will startup a Mininet session with all hosts created.&nbsp;&nbsp; If you use sdn-topology.py, you will get a controller error.&nbsp; Ctrl-C and redo step 2 to get the correct topology.

<ul>
<li>Step 3: Start up two xterm windows for hosts us1 and us2. After you start each xterm window, it is recommended that you run the following command in each xterm window as you load them to avoid confusion about which xterm belongs to which host:</li>
</ul>
&nbsp;

<strong>export PS1=”hostname &gt;”</strong><strong>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </strong>replacing hostname with the actual hostname.

&nbsp;

Type in the following commands <u>at the Mininet prompt. </u>This is optional, but helps with identifying which xterm window belongs to which host.

&nbsp;

<table width="292">
<tbody>
<tr>
<td width="75"><strong>us1 xterm &amp;</strong></td>
<td rowspan="2" width="76">&nbsp;&nbsp;&nbsp;&nbsp; (then run

(likewise, run
</td>
<td colspan="2" width="117"><strong>export PS1=”us1 &gt;”</strong></td>
<td width="24"></td>
</tr>
<tr>
<td width="75"><strong>us2 xterm &amp;</strong></td>
<td width="23"></td>
<td colspan="2" width="118"><strong>export PS1=”us2 &gt;”</strong></td>
</tr>
<tr>
<td width="75"></td>
<td width="76"></td>
<td width="23"></td>
<td width="94"></td>
<td width="24"></td>
</tr>
</tbody>
</table>
in the xterm window that pops up)&nbsp; in the second xterm window)

&nbsp;

<ul>
<li>Step 4: In this step, we want to start capturing all the traffic that traverses through the ethernet port on host us1. We do this by running tshark (or alternatively, wireshark) as follows from the mininet prompt:</li>
</ul>
&nbsp;

<h4>us1 sudo tshark -w /tmp/packetcapture.pcap</h4>
&nbsp;

This will start tshark and will output a pcap formatted file to packetcapture.pcap to the tmp directory. Note that this file is created as root, so you will need to change ownership to mininet to use it in future steps – <strong>chown mininet:mininet /tmp/packetcapture.pcap</strong>

<strong>&nbsp;</strong>

If you wish to use the Wireshark GUI instead of tshark, you would call <strong>us1 sudo wireshark</strong><strong> &amp;</strong>. You may use this method, but the TA staff will not provide support for any issues that may occur.

&nbsp;

<strong>YOU WILL SUBMIT THIS FILE AS A PART OF YOUR SUBMITTAL.</strong>

&nbsp;

<ul>
<li>Step 5: Now we need to capture some traffic. Do the following tasks in the appropriate xterm window:</li>
</ul>
&nbsp;

in us1 xterm:&nbsp;&nbsp;&nbsp;&nbsp; <strong>ping 10.0.1.2</strong>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; (hit control C after a few ping requests)

In us2 xterm:&nbsp;&nbsp;&nbsp;&nbsp; <strong>ping 10.0.1.1</strong>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; (likewise hit control C after a few ping requests)

In us1 xterm:&nbsp;&nbsp;&nbsp;&nbsp; <strong>python test-server.py T 10.0.1.1 80&nbsp; </strong>

In us2 xterm:&nbsp;&nbsp;&nbsp;&nbsp; <strong>python test-client.py T 10.0.1.1 80</strong>

After the connection completes, in the us1 xterm, press Control-C to kill theserver.

In us1 xterm:&nbsp;&nbsp;&nbsp;&nbsp; <strong>python test-server.py U 10.0.1.1 8000&nbsp; </strong>

In us2 xterm:&nbsp;&nbsp;&nbsp;&nbsp; <strong>python test-client.py U 10.0.1.1 8000</strong>

In us1 xterm:&nbsp;&nbsp;&nbsp;&nbsp; press Control C to kill the server

In Mininet Terminal:&nbsp; press Control C to stop tshark

&nbsp;

<ul>
<li>Step 6: At the mininet prompt, type in exit and press enter. Next, do the chown command as described in step 4 above to your packet capture. You may also close the two xterm windows as they are finished.&nbsp;&nbsp; Copy the /tmp/packetcapture.pcap to your project directory.&nbsp; This file is the deliverable for this phase of the project.&nbsp; See the instructions in Step 4 that describe how you will need to change ownership of this file in order to change or move it.</li>
</ul>
&nbsp;

<ul>
<li>Step 7: At the bash prompt on the main terminal, run:</li>
</ul>
&nbsp;

<h4>sudo wireshark</h4>
&nbsp;

Go to the File =&gt; Open menu item, browse to the /tmp directory and select the pcap file that you saved using tshark.

&nbsp;

You will get a GUI that looks like the example packet capture. You will have a numbered list of all the captured packets with brief information consisting of source/destination, IP protocol, and a description of the packet. You can click on an individual packet and will get full details including the Layer 2 and Layer 3 packet headers, TCP/UDP/ICMP parameters for packets using those IP protocols, and the data contained in the packet.

<strong><u>Example Packet Capture – Host us1 making web request to Host us2</u></strong>

&nbsp;

Note the highlighted fields. You will be using the information from these fields to help build your firewall implementation and ruleset. Note the separate header information for TCP. This will also be the case for UDP packets.

Also, examine the three-way handshake that is used for TCP. What do you expect to find for UDP?&nbsp; ICMP? <strong><u>Example TCP Three-Way Handshake</u> </strong>

&nbsp;

Please examine the other packets that were captured to help you familiarize yourself with Wireshark.

<h2><a name="_Toc35942"></a>Part&nbsp;&nbsp; 4:&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; SDN&nbsp;&nbsp; Firewall&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Implementation Details</h2>
&nbsp;

Using the information that you learned above in running Wireshark, you will be creating two files – one is a firewall configuration file that will specify different header parameters to match in order to allow or block certain traffic that will define the actions of the firewall and the second is the implementation code to create the OpenFlow Flow Modification objects that will create the firewall using the parameters given in the firewall configuration file.

<h3><a name="_Toc35943"></a>Part&nbsp;&nbsp;&nbsp; 4a:&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Specifications&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; of&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; configure.pol</h3>
&nbsp;

The configure.pol file is used by the firewall implementation code to specify the rules that the firewall will use to govern a connection.&nbsp; You do not need to code this first, but the format of the file is important to understand as your implementation code will need to use these items.&nbsp; The format of the file is a collection of lines that have the proper format:

<strong>Rule Number, Action, Source MAC, Destination MAC, Source IP Network Address, Destination IP </strong>

<strong>Network Address, Protocol, Source Port, Destination Port, Comment/Note </strong>

<ul>
<li><strong>Rule Number</strong> = this is a rule number to help you track a particular rule – it is not to be used at all in your firewall implementation except to help you find rules that cause an error. DO NOT USE FOR PRIORITY.</li>
</ul>
&nbsp;

<ul>
<li><strong>Action</strong> = <strong>Block</strong> or <strong>Allow</strong> <strong>Block</strong> rules will block traffic that matches the remaining parameters of this rule. <strong>Allow</strong> rules will override Block rules to allow specific traffic to pass through the firewall (see below for an example). The entry is a string in (<strong>Block</strong>,<strong>Allow</strong>) and is validated by the parser.</li>
</ul>
&nbsp;

<ul>
<li><strong>Source / Destination MAC</strong> address in form of xx:xx:xx:xx:xx:xx (example: 00:a2:c4:3f:11:09) or a “-“ if you are not matching this item. You may use MAC Addresses to match an individual host. In the real world, you would use it to match a particular piece of hardware. The MAC address of a particular host is defined inside the sdn-topology.py&nbsp;&nbsp; The parser will verify that the MAC Address is in a proper form.&nbsp; If not, an error will be thrown.</li>
</ul>
&nbsp;

<ul>
<li><strong>Source / Destination IP <u>Network Address</u></strong> in form of xxx.xxx.xxx.xxx/xx in CIDR notation or a “-“ if you are not matching this item. <strong><u>IMPORTANT NOTE:&nbsp; THIS MUST BE A VALID NETWORK ADDRESS.&nbsp; Thus, if</u> <u>you specify a subnet mask of /24, it means the first 24 bits will be the network address and the last 8</u> <u>bits will be 0.&nbsp; Thus, for a host 10.0.10.10/24, the NETWORK ADDRESS will be 10.0.10.0/24.&nbsp; If you</u> <u>specify 10.0.10.10/24, you will get an error.&nbsp; If you want to specify a single host, then your netmask</u> <u>will be all 1s for the 32-bits of the address (i.e., a /32). </u></strong>&nbsp;&nbsp;The parser for the file will validate that you have a proper IP Address given, but will not parse to see if it is a valid network address.&nbsp; You will get a POX error if it is not a valid Network Address.</li>
</ul>
&nbsp;

The IP address of a particular host is defined inside the sdn-topology.py file.

&nbsp;

<ul>
<li><strong>Protocol</strong> = integer IP protocol number per IANA (0-254) or a “-“ if you are not matching this item.. An example is ICMP is IP Protocol 1, TCP is IP Protocol 6, etc.</li>
</ul>
&nbsp;

<ul>
<li><strong>Source / Destination Port</strong> = if Protocol is TCP or UDP, this is the Application Port Number per IANA. For example, web traffic is generally TCP Port 80. Do not try to use port numbers to differentiate the different elements of the ICMP protocol. If you are not matching this item or are using an IP Protocol other than TCP or UDP, this field should be a “-“.</li>
</ul>
&nbsp;

<ul>
<li><strong>Comment/Note</strong> = this is for your use in tracking rules.</li>
</ul>
<strong>Special Notes About Firewall Configurations: </strong>

<ul>
<li>Any field not being used for a match should have a ‘-‘ character as its entry. A ‘-‘ means that the item is not being used for matching traffic.&nbsp;&nbsp; <strong><u>It is valid for any rule element except for Action, Rulnenum, or</u> <u>Comment to have a ‘-‘ specified.</u></strong>&nbsp; Note that if you pass a “-“ to one of the match items in your code, you will crash POX.</li>
<li>All fields are passed as a string, so you must do type conversions as necessary.</li>
<li>You should not use a subnet mask smaller than /24. Using a /16 to cover all the subnets is not allowed. o Do not use 0.0.0.0/0 to address the internet as a whole.&nbsp; This may have unexpected behavior in POX.</li>
</ul>
There is an easier way to match the world than using 0.0.0.0.&nbsp; Hint:&nbsp; Think about what a “-“ means. o When should I use MAC vs IP Addresses?&nbsp; You will want to interchange them in this file to test the robustness of your implementation. It is valid to specify a Source MAC address and a Destination IP Address.

<strong>Example Rules (included in the project files: </strong>

<strong>1,Block,-,-,10.0.0.1/32,10.0.1.0/24,6,-,80,Block 10.0.0.1 host from accessing a web server on the 10.0.1.0/24 network</strong><strong> 2,Allow,-,-,10.0.0.1/32,10.0.1.125/32,6,-,80,Allow 10.0.0.1 host to access a web server on 10.0.1.125 overriding rule&nbsp; What do these rules do? </strong>

The first rule basically blocks host hq1 (IP Address 10.0.0.1/32) from accessing a web server on any host on the us network (the subnet 10.0.1.0/24 network). The web server is running on the TCP IP Protocol (6) and uses TCP Port 80.

The second rule overrides the initial rule to allow hq1 (IP Address 10.0.0.1/32) to access a web server running on us5 (IP Address 10.0.1.125/32)

By definition – from the sdn-topology.py file:

This class defines the Mininet Topology for the network used in this project. This network consists of the following hosts/networks:

Headquarters Network (hq1-hq5). Subnet 10.0.0.0/24

US Network (us1-us5). Subnet 10.0.1.0/24

India Network (in1-in5). Subnet 10.0.20.0/24

China Network (cn1-cn5). Subnet 10.0.30.0/24

UK Network (uk1-uk5). Subnet 10.0.40.0/24

&nbsp;

In Part 5, you will be given a set of firewall conditions that you will need to create the configure.pol needed for your submission.&nbsp; <strong>&nbsp;</strong>

You may create temporary rulesets to help you complete Part 5b below.

<h3><a name="_Toc35944"></a>Part&nbsp;&nbsp;&nbsp; 4b:&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Implementing&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; the&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Firewall&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; in&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Code</h3>
&nbsp;

After reviewing the format of the configure.pol file, you will now code a generic implementation of a firewall that will use the values provided from the configuration file (passed to you as dictionary items).&nbsp; As it is provided, the firewall implementation code blocks no traffic.&nbsp; You must implement code that does the following:

<ul>
<li><strong>Create a</strong><strong><u>n</u></strong><strong> OpenFlow Flow Modification object </strong></li>
<li><strong>Create a POX Packet Matching object that will integrate the elements from a single entry in the firewall configuration rule file (which is passed in the policy dictionary) to match the different IP and TCP/UDP headers if there is anything to match (i.e., no “-“ should be passed to the match object, nor should None be passed to a match object if a “-“ is provided). </strong></li>
<li><strong>Create a POX Output Action, if needed, to specify what to do with the traffic. </strong></li>
</ul>
Please reference code examples in Appendix C, or you may refer to the POX API documentation (WARNING, this is long and the API is confusing).

You will need to rewrite the rule = None to reference your Flow Modification object.

Your code will go into a section that will repeat itself for every line in the firewall configuration file that is passed to it. The “rule” item that is added to the “rules” list is an OpenFlow Modification object. The process of injecting this rule into the POX controller is handled automatically for you in the start-firewall.py file.

<strong><u>TIP:&nbsp; If your implementation code segment is more than 25-30 lines, you are making it too difficult.&nbsp; The POX</u></strong><strong> <u>API&nbsp; can provide many features that are not used in this project.&nbsp; The Appendix provides all of the information</u> <u>that you will need to code the project.</u> </strong>

<strong>Key Information:</strong>

<ul>
<li><u>policies</u> is a python list that contains one entry for each rule line contained in your configure.pol file. Each individual line of the configure.pol file is represented as a dictionary object named policy. This dictionary has the following keys:</li>
<li><strong>policy[‘mac-src’] = Source MAC Address (00:00:00:00:00:00) or “-“ </strong>o <strong>policy[‘mac-dst’] = Destination MAC Address (00:00:00:00:00:00) ) or “-“ </strong>o <strong>policy[‘ip-src’] = Source IP Address (10.0.1.1/32) in CIDR notation ) or “-“ </strong>o <strong>policy[‘ip-dst’] = Destination IP Address (10.0.1.1/32) ) or “-“ </strong>o <strong>policy[‘ipprotocol’] = IP Protocol (6 for TCP) ) or “-“ </strong></li>
<li><strong>policy[‘port-src’] = Source Port for TCP/UDP (12000) ) or “-“ </strong>o <strong>policy[‘port-dst’] = Destination Port for TCP/UDP (80) ) or “-“ </strong></li>
<li><strong>policy[‘rulenum’] = Rule Number (1) </strong>o <strong>policy[‘comment’] = Comment (Example Rule) </strong>o <strong>policy[‘action’] = Allow or Block </strong></li>
</ul>
Use these to match traffic. <strong>Please note that all fields are strings and may contain a ‘-‘ character</strong>. You may either use policy[‘ip-dst’] or the split policy[‘ip-dst-address’]/[policy[‘ip-dst-subnet’] in your implementation (the split was requested by prior semesters), but realize that if you use the ip-dstaddress and ip-dst-subnet, you will need to carefully check your implementation to ensure that it is blocking the addresses you intend to block.

<ul>
<li>You will need to assume that all traffic is IPV4. It is acceptable to hardcode this value. <strong>Do not hardcode other values.&nbsp; Your code should be generic enough to handle any possible configuration. </strong></li>
</ul>
<strong>&nbsp;</strong>

<ul>
<li>Hints: o The difference between an Allow or a Block is dependent on an Action and the Priority.</li>
<li>You don’t necessarily need an action. See Appendix C for a discussion of what happens to a packet after it is matched.</li>
<li>There should be two priorities – one for ALLOW and one for BLOCK. Separate them sufficiently to override any exact matching behavior that the POX controller implements).&nbsp; It is suggested one priority be 0 or 1 and the other one above 10000.&nbsp; The reasoning for this is discussed in Appendix C.</li>
</ul>
&nbsp;

<ul>
<li>Outputting extra print debug lines will not adversely impact the autograder. o Remember, you may be tested with IP Protocols outside of 1, 6, and 17. Don’t hardcode.</li>
</ul>
<strong>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </strong>

<h2><a name="_Toc35945"></a>Part&nbsp;&nbsp; 5:&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Configuration&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Rules</h2>
&nbsp;

You will need to submit a <strong>configure.pol</strong> file to create policies that implement the following scenarios. You may implement your rules in any manner that you want, but it is recommended using this step as an opportunity to check your firewall code implementation. The purpose of these rules is to test your firewall and to help determine how traffic flows across the network (source vs destination, protocols, etc).

&nbsp;

DO NOT block all traffic by default and only allow traffic specified.&nbsp; You will lose many points because the firewall is open by default and only blocks the traffic that is specified.

&nbsp;

Firewall Rules for Fall 2024:

&nbsp;

<ul>
<li><strong>Task 1: Host cn4 has a TCP-based worm virus.&nbsp; Block cn4 from initiating network communications to any host on the internet (world) over the TCP Internet Protocol.&nbsp; You need not block ICMP or UDP. (one rule max) </strong></li>
<li><strong>Task 2: Host cn5 has had a security incident and needs to be completely isolated from the network so it has no connectivity (incoming or outgoing) to any other host on the internet (world). (two rules max)&nbsp; </strong></li>
<li><strong>Task 3: Allow the hosts on the Headquarters network to be reachable via an ICMP ping from the world (including all but the China subnet (to avoid conflicts with Tasks 1 and 2 above).&nbsp; In addition, the corporate subnets should not be pingable from the internet (world).&nbsp; However, to satisfy the first half of this task, you must allow the Headquarters network to be able to ping the US, UK, and India subnets.&nbsp; Can you explain why this must happen?&nbsp; (six rules typically) </strong></li>
</ul>
<strong>&nbsp;</strong>

<strong>The China network is exempted from this rule because any overrides that you may do here will override aspects of Task 1 or Task 2 above. </strong>

<ul>
<li><strong>Task 4: Do not allow any response back from a TCP web server (http and https) from host cn3 to any other host on the internet (world). (two rules max) </strong></li>
<li><strong>Task 5: (CIDR Notation Rule)&nbsp; The servers located on hosts us3 and us4 run a micro webservice on TCP Port <span style="text-decoration: line-through;"><u>9250</u></span> 9520 that processes financial information. Access to this service should be blocked from hosts uk2, uk3, uk4, uk5, in4, in5, us5, and hq5. Please use the minimal CIDR notation that will bracket the subset of hosts for each rule (it should NOT be broader than /28). (four rules typical) </strong></li>
<li><strong>Task 6: A rogue Raspberry Pi has been found on the network that has cloned the Network Address of host us1.&nbsp; Block this device from accessing any other hosts on the internet (world) on the UDP Internet Protocol. (one rule max) </strong></li>
</ul>
<strong>&nbsp;</strong>

<strong>Note that when testing this rule, the IP address for host us1 may differ from the published topology.&nbsp; In this case, you want to address the particular hardware device. </strong>

<ul>
<li><strong>Task 7: Block the internet (world) from accessing TCP Port 25 on any corporate subnets.&nbsp; The behavior of access to TCP Port 25 amongst members of the corporate subnets is undefined and you may handle it as you wish. (five rules max) </strong></li>
</ul>
<h1><a name="_Toc35946"></a>What&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; to&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Turn&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; In</h1>
You need to submit your copy of packetcapture.pcap, sdn-firewall.py and configure.pol from your project directory using the instructions from the Piazza Post “How to Submit / Zip Our Projects. To recap, zip up the two files using the following command, replacing gtlogin with your GT Login that you use to log into Canvas:

&nbsp;

<strong>zip gtlogin_sdn.zip packetcapture.pcap configure.pol sdn-firewall.py</strong>

The key to properly zipping the project is to NOT zip up the directory.&nbsp; ZIP only the files you are included.

&nbsp;

You may also include an additional text file if you have comments, criticisms, or suggestions for improvement for this project. If you wish to provide this information, add it to your ZIP file with the name comments.txt. This is completely optional.

&nbsp;

<strong>Please check your submission after uploading. </strong>As usual, we do not accept resubmissions past the stated deadlines.

<h1><a name="_Toc35947"></a>What&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; you&nbsp; can&nbsp;&nbsp; and&nbsp; cannot&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; share</h1>
Do not share the content of your sdn-firewall.py, configure.pol, or packetcapture.pcap with your fellow students, on Ed Discussions, or elsewhere publicly. You may share any new topologies, testing rulesets, or testing frameworks, as well as packet captures that do not address the requirements of Part 4b.

<strong>&nbsp;</strong>

Rubric

For the Summer 2024 Semester, this project is worth a total of 100 points which is distributed in the following fashion:

<ul>
<li>5 points for submitting a version of sdn-firewall.py that indicates effort was done.</li>
<li>5 points for submitting a version of configure.pol that indicates effort was done.</li>
<li>15 points for submitting a version of packetcapture.pcap that indicates effort was done.</li>
<li>25 points for testing your configure.pol file with a known-good implementation.</li>
<li>25 points for testing your configure.pol with your implementation.</li>
<li>25 points for testing your implementation with a known-good configure.pol.</li>
</ul>
<h1><a name="_Toc35948"></a>Appendix&nbsp;&nbsp;&nbsp; A:&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; How&nbsp; to&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Test&nbsp;&nbsp; Host&nbsp; Connectivity</h1>
&nbsp;

<h3><a name="_Toc35949"></a>Part&nbsp;&nbsp;&nbsp; A:&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; How&nbsp;&nbsp;&nbsp; to&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Test&nbsp;&nbsp;&nbsp;&nbsp; Manually</h3>
When you are developing your implementation or troubleshooting a firewall rule, you will want to test by hand.&nbsp; Unfortunately this process is a bit difficult.

&nbsp;

<strong>1,Block,-,-,10.0.0.1/32,10.0.1.0/24,6,-,80,Block 10.0.0.1 from accessing a web server on the</strong>

<strong>10.0.1.0/32 network</strong>

<strong>Startup Procedure: </strong>

<ul>
<li>Step 1: Open two terminal windows or tabs on the VM and change to the SDNFirewall directory.</li>
</ul>
&nbsp;

<ul>
<li>Step 2: In the first terminal window, type in:&nbsp; <strong>./start-firewall.sh configure.pol</strong></li>
</ul>
<strong>&nbsp;</strong>

<h6>If you get the following error, run chmod +x start-firewall.sh and chmod +x start-topology.sh</h6>
&nbsp;

&nbsp;

This should start up POX, read in your rules, and start up an OpenFlow Controller. You will see something like this in your terminal window:

&nbsp;

<table width="596">
<tbody>
<tr>
<td colspan="2" width="596">TA Note:&nbsp; Note that you will not see the “List of Policy Objects imported from configure.pol” and the</td>
</tr>
<tr>
<td width="343">“Added Rule” lines until after you complete Step 3 below.</td>
<td width="253"></td>
</tr>
</tbody>
</table>
&nbsp;

<ul>
<li>Step 3: In the second terminal window, type in:&nbsp; <strong>./start-topology.sh</strong></li>
</ul>
&nbsp;

This should start up mininet and load the topology. You should see the following:

&nbsp;

&nbsp;

This will start the firewall and set the topology.&nbsp; You do not need to repeat Steps 1-3 unless you are

done testing, need to restart the firewall, or need to restart mininet.&nbsp; When you are done with testing all of the rules you intend to use, type in “quit” in the mininet window, close all of the extraneous xterm windows generated, and run the mininet cleanup script&nbsp; <strong>./cleanup.sh</strong> <strong>How to test connectivity between two hosts: </strong>

<ul>
<li>Step 1: To test the rule shown above, we want to use host us1 as server/destination and host hq1 as the client.&nbsp; The rule we are testing involves the hq1 host attempting to connect to the web server port (TCP Port 80) on host us1. At the mininet prompt, type in the following two commands on two different lines:</li>
</ul>
&nbsp;

<table width="76">
<tbody>
<tr>
<td width="76"><strong>hq1 xterm &amp;</strong></td>
</tr>
<tr>
<td width="76"><strong>us1 xterm &amp;</strong></td>
</tr>
</tbody>
</table>
&nbsp;

Two windows should have popped up. You can always identify which xterm is which by running the command:&nbsp; <strong>ip address</strong> from the bash shell. This will give you the IP address for the xterm window, which will then let you discover which xterm window belongs to which host.

&nbsp;

<ul>
<li>Step 2: In the xterm window for us1 (which is the destination host of the rule – remember that the destination is always the server), type in the following command:</li>
</ul>
&nbsp;

<h6>python test-server.py T 10.0.1.1 80</h6>
&nbsp;

This sets up the test server for us1 that will be listening on TCP port 80. The IP Address specified is always the IP address of the machine you are running it on.<strong> If you attempt to start the test-server on a machine that does not have the IP address that is specified in the command, you will get the following error:&nbsp; OSError:&nbsp; [Errno 99] Cannot assign requested address.&nbsp; </strong>

&nbsp;

o Step 6:&nbsp; In the xterm window for hq1 (which is the source host of the rule – remember that the source is always the client), type in the following command:

&nbsp;

<h6>python test-client.py T 10.0.1.1 80</h6>
&nbsp;

This will start up a client that will connect to the TCP Port 80 on the server 10.0.1.1 (destination IP address) and will send a message string to the server. However, if the firewall is set to block this connection, you will never see the message pass on either of the client or the server.

Examples of Connection Status:

<ul>
<li>The two windows below depict a successful un-blocked connection between the client and the server.</li>
</ul>
&nbsp;

&nbsp;

&nbsp;

&nbsp;

<ul>
<li>A blocked connection will look like this (note that the client may take a while to timeout):</li>
</ul>
&nbsp;

&nbsp;

You may hit Control C to kill both the server and the client.

&nbsp;

<ul>
<li>A timed out connection is shown below. The difference between a timed-out connection on how the connection was blocked or if it was blocked on a different side of the connection.</li>
</ul>
&nbsp;

&nbsp;

&nbsp;

<ul>
<li>If you get an error that says “No route to destination”, you have blocked the routing protocol.</li>
</ul>
Ensure that you do not have a Unspecified Prerequisite Error

Repeat this process for every rule you wish to test.&nbsp; If you feel that after some initial testing that your implementation and ruleset is good, you may then proceed to using the automated test suite.

<h3><a name="_Toc35950"></a>Part&nbsp;&nbsp;&nbsp; B:&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Automated&nbsp;&nbsp;&nbsp; Testing&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Suite</h3>
The automated Test Suit was developed by a student in Summer 2021 (htian66) and has been updated to match the current version of this project.&nbsp; There are two test suites – one that tests your implementation with the configure.pol you created that matches the rules in Part 5, and the second that is a generic test of your implementation with a different topology and provided configuration policy.&nbsp; The first test suite will be the exact same one used in the autograder that will be used after you turn the project into Canvas.

<strong>How&nbsp;&nbsp;&nbsp; to&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; test&nbsp;&nbsp;&nbsp;&nbsp; normal&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; cases: </strong>

&nbsp;

<ol>
<li>Change to the test-scripts directory</li>
<li>Copy your `sdn-firewall.py` and `configure.pol` into this directory.</li>
<li>Run <strong>./start-firewall.sh configure.pol</strong> as usual.</li>
<li>Open a new window, run <strong>sudo python test_all.py</strong>.</li>
<li>Total passed cases are calculated. Wrong cases will be displayed. For example, `2: us1 -&gt; hq1 with U at 53, should be True, current False` means the connection from client us1 to host hq1 using UDP at hq1 53 port is failed, which should be successful. The first number is the index (0-based) of testcases.</li>
</ol>
True indicates that a connection was made or was expected.&nbsp; False indicates the opposite condition.

&nbsp;

<strong>How&nbsp;&nbsp;&nbsp; to&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; test&nbsp;&nbsp;&nbsp;&nbsp; alternte&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; cases: </strong>

&nbsp;

<ol>
<li>Change to the test-scripts directory</li>
<li>Copy your `sdn-firewall.py` file into the alt folder. Change to the alt directory.</li>
<li>Run <strong>./start-firewall.sh</strong> (you do not need to specify your configure.pol file 4. Open a new window, run <strong>sudo python test_all.py</strong> in the test-suite/alt folder.</li>
<li>Total passed cases are calculated. Wrong cases will be displayed. For example, `2: us1 -&gt; hq1 with U at 53, should be True, current False` means the connection from client us1 to host hq1 using UDP at hq1 53 port is failed, which should be successful. The first number is the index (0-based) of testcases.</li>
</ol>
True indicates that a connection was made or was expected.&nbsp; False indicates the opposite condition.

<h1><a name="_Toc35951"></a>Appendix&nbsp;&nbsp;&nbsp; B:&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Troubleshooting Information</h1>
&nbsp;

<h3><a name="_Toc35952"></a>General&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Coding&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Issues</h3>
<ul>
<li>Watch for type mismatches.</li>
<li><strong><u>Do not run “pip3 install pox”. The pox module installed by pip is not the library used in this project.</u> </strong></li>
<li>This project is virtually impossible to use the Debug utilities inside of VSCode or Pycharm since it requires running under the mininet framework. For debugging, it is suggested that you use print statements in your code to help determine where issues may be occurring.</li>
<li>You do NOT need to reparse or revalidate any of the data provided in the dictionary other than possibly changing the type from strings.</li>
<li>If you use Visual Studio code, add the following to your workspace settings:</li>
</ul>
“python.autoComplete.extraPaths”: [&nbsp;&nbsp;&nbsp;&nbsp; “/home/mininet/pox/”&nbsp;&nbsp; ],

Also, with Visual Studio code, it sometimes “recommends” _dl_type and other names prepended with a _.&nbsp; Note that this is incorrect – the name is dl_type, not _dl_type.

<h3><a name="_Toc35953"></a>Firewall&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Implementation&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; (sdn-firewall.py)&nbsp;&nbsp;&nbsp;&nbsp; Errors and&nbsp;&nbsp;&nbsp;&nbsp; Issues</h3>
<ul>
<li>Pay attention to the Fields ignored due to unspecified prerequisites warning. Do not ignore this message or your firewall will overblock (i.e., it ignores the field specified). Remember that there are items required when you specify TCP or UDP, and when you specify IPV4.</li>
<li>If you get a struct.pack or struct.unpack error message, take a look at https://github.com/att/pox/blob/7f76c9e3c9bc999fcc97961d408ab0b71cbc186d/pox/OpenFlo w/libOpenFlow_01.py for more information. Also, the struct.pack error might reference how to fix (i.e., not an integer, EthAddr(), etc).</li>
<li>The following error means that you should check your output action: “TypeError: ord() expected string of length 1, but int found”</li>
<li>If you find that all traffic is blocked, double check the unspecified prerequisite warning. o Note that you may have issues with certain rules that don’t seem to work when you first start the firewall. This is typically caused by starting the Spanning Tree.&nbsp; You may run “pingall” to overcome this before testing.&nbsp; This can be enabled in the autograder utility.</li>
</ul>
<h3><a name="_Toc35954"></a>Mininet/Topology&nbsp;&nbsp; Issues</h3>
<ul>
<li>On the topology terminal window, if you get an error message that states “Unable to contact Remote Controller”, it means that the POX controller had crashed and normally shows that there is a bug in your implementation code. Look at the windows where you started the firewall.</li>
<li>If you get the following error message, please run the cleanup.sh utility: “Exception: Error creating interface pair (s1-eth0,hq1-eth0): RTNETLINK answers: File exists”</li>
</ul>
<strong>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </strong>

<h1><a name="_Toc35955"></a>Appendix&nbsp;&nbsp;&nbsp; C:&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; POX&nbsp;&nbsp; API&nbsp;&nbsp;&nbsp; Excerpt</h1>
&nbsp;

This section contains a highly modified excerpt from the POX Manual (modified to remove extraneous features not used in this project and to provide clarifications). You should not need to use any other POX objects for this project. TA Comments are highlighted. Everything on these pages is important to complete the project.

Excerpted and modified from:&nbsp; <u>https://noxrepo.github.io/pox-doc/html/</u> <strong>Object Definitions: </strong>

<h2><a name="_Toc35956"></a>Flow&nbsp; Modification&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Object</h2>
&nbsp;

The main object used for this project is a “Flow Modification” object.&nbsp; This adds a rule to the OpenFlow controller that will affect a modification to the traffic flow based on priority, packet characteristic matchin, and an action that will be done to the traffic that is matched.&nbsp; IF AN OBJECT is matched, it is pulled from the network stream and will only be forwarded, modified, or redirected if you do an action.&nbsp; If you do not specify an action and the packet is matched, the packet will basically be dropped.

&nbsp;

The following class descriptor describes the contents of a flow modification object.&nbsp; You need to define the match, priority, and actions for the object.

<strong>class</strong> <strong>ofp_flow_mod</strong> (ofp_header):&nbsp;&nbsp; <strong>def</strong> __init__ (self, **kw):&nbsp;&nbsp;&nbsp;&nbsp; ofp_header.__init__(self)&nbsp;&nbsp;&nbsp;&nbsp; self.header_type = OFPT_FLOW_MOD&nbsp;&nbsp;&nbsp;&nbsp; self.match = ofp_match()

self.priority = OFP_DEFAULT_PRIORITY&nbsp;&nbsp;&nbsp;&nbsp; self.actions = []

<strong>&nbsp;</strong>

<h2><a name="_Toc35957"></a>Match&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Structure</h2>
OpenFlow defines a match structure – ofp_match – which enables you to define a set of headers for packets to match against.

&nbsp;

The match structure is defined in pox/OpenFlow/libOpenFlow_01.py in class ofp_match. Its attributes are derived from the members listed in the OpenFlow specification, so refer to that for more information, though they are summarized in the table below.

&nbsp;

You should create a match object and attach it to the flow modification object.

&nbsp;

<strong>Attribute Meaning </strong>dl_src Ethernet/MAC source address&nbsp; (Type of EthAddr) dl_dst Ethernet/MAC destination address (Type of EthAddr) dl_type Ethertype / length (e.g. 0x0800 = IPv4) (Type of Integer) nw_proto IP protocol (e.g., 6 = TCP) or lower 8 bits of ARP opcode (Type of integer) nw_src IP source NETWORK address (Type of String) nw_dst IP destination NETWORK address (Type of String) tp_src TCP/UDP source application port (Type of Integer) tp_dst TCP/UDP destination application port (Type of Integer)

&nbsp;

&nbsp;

<strong><u>TA Note: (IMPORTANT_</u></strong>

<strong><u>If you use VSCode or Pycharm, it may make the recommendation to use _dl_src and _dl_dst.&nbsp; These are not</u></strong><strong> <u>valid.&nbsp; Please use what is specified above.</u> </strong>

&nbsp;

Attributes may be specified either on a match object or during its initialization. That is, the following are equivalent:

matchobj = of.ofp_match(tp_src = 5, dl_type = 0x800,dl_dst = EthAddr(“01:02:03:04:05:06”))

<em>#.. or ..</em>

matchobj = of.ofp_match() matchobj.tp_src = 5 matchobj.dl_type = 0x800

matchobj.dl_dst = EthAddr(“01:02:03:04:05:06”)

&nbsp;

IMPORTANT NOTE ABOUT IP ADDRESSES

&nbsp;

TA Note:&nbsp; What isn’t very clear by this documentation is that nw_* is expecting a network address. If you are calling out an IP Address like 10.0.1.1/32, it is an acceptable response to nw_*. However, if you are calling out a subnet like 10.0.1.0/24, the IP address portion of the response MUST BE the Network Address.

&nbsp;

From Wikipedia:&nbsp; IP addresses are described as consisting of two groups of bits in the address: the most significant bits are the network prefix, which identifies a whole network or subnet, and the least significant set forms the host identifier, which specifies a particular interface of a host on that network. This division is used as the basis of traffic routing between IP networks and for address allocation policies. (https://en.wikipedia.org/wiki/Classless_Inter-Domain_Routing)

&nbsp;

Thus for a /24 network, the first 24 bits of the address comprises the network address. Thus, it would be 10.0.1.0. For a /25 network, there would be two networks in the 10.0.1.x space – a 10.0.1.0/25 and a 10.0.1.128/25.

&nbsp;

Your implementation code does NOT need to convert the given IP Address into a network – you can assume that any given address in a possible configuration file must be valid. However, your configure.pol file MUST be using the proper form if you are using a CIDR notation other than /32. Why would you do this?&nbsp; To reduce the number of rules needed. You may use this for the 5th rule from Part

<ol start="6">
<li></li>
</ol>
&nbsp;

Note that some fields have prerequisites. Basically this means that you can’t specify higher-layer fields without specifying the corresponding lower-layer fields also. For example, you can not create a match on a TCP port without also specifying that you wish to match TCP traffic. And in order to match TCP traffic, you must specify that you wish to match IP traffic. Thus, a match with only tp_dst=80, for example, is invalid. You must also specify nw_proto=6 (TCP), and dl_type=0x800 (IPv4). If you violate this, you should get the warning message ‘Fields ignored due to unspecified prerequisites‘.

&nbsp;

This question also presents itself as “What does the Fields ignored due to unspecified prerequisites warning mean?”

&nbsp;

Basically this means that you specified some higher-layer field without specifying the corresponding lower-layer fields also.&nbsp; For example, you may have tried to create a match in which you specified only tp_dst=80, intending to capture HTTP traffic.&nbsp; You can’t do this.&nbsp; To match TCP port 80, you must also specify that you intend to match TCP (nw_proto=6).&nbsp; And to match on the TCP protocol, you must also match on IPV4 type (dl_type=0x800).

&nbsp;

<h2><a name="_Toc35958"></a>OpenFlow&nbsp;&nbsp; Actions</h2>
&nbsp;

The final aspect needed to fully implement a flow modification object is the action.&nbsp; With this, you specify what you want done to a port.&nbsp; This can include forwarding, dropping, duplicating and redirecting, or modify the header parameters.&nbsp; For the purposes of this project, we are only dealing with forwarding of match traffic to its destination.&nbsp; But please note that for a Software Defined Network system, you can do all sorts of actions including round robin server, DDOS blocking, and many other possible options.

&nbsp;

&nbsp;

Output

Forward packets out of a physical or virtual port. Physical ports are referenced to by their integral value, while virtual ports have symbolic names. Physical ports should have port numbers less than 0xFF00.

&nbsp;

<strong>port (int) the output port for this packet</strong>.&nbsp;&nbsp;&nbsp; This is a bit misleading because it can confuse you with the application “port” for TCP/UDP.&nbsp; For openflow, this port represents the physical swith port that the host is plugged into.&nbsp; However, you do NOT know which physical port on which switch a host is connected to.&nbsp; Thus, you will need to use one of the virtual ports to define what you want to happen:

<ul>
<li>OFPP_IN_PORT – This action will send the port back to the sender (i.e., the port it came into the network on)</li>
<li>OFPP_NORMAL – Process the packet and handle via a normal L2/L3 legacy switch configuration (i.e., send traffic to its destination without modification) – See <u>https://studyccna.com/layer-3-switch/</u> for information on how normal L2/L3 legacy switches work.</li>
<li>OFPP_FLOOD – This action will cause the traffic to be sent out to all ports except the source (IN_PORT) and any ports that have flooding turned off. This is very chatty and can be used to do network based attacks (see UDP Amplifications).&nbsp; This should be avoided.</li>
<li>OFPP_ALL – output all OpenFlow ports except the source (IN_PORT).&nbsp; This is the same as FLOOD but it includes ports that have had flood turned off.</li>
<li>OFPP_CONTROLLER – This action sends the packet to the switch controller. What happens with the port depends on the state of the switch controller.&nbsp; Thus it may work, but also may not work, based on the current state of the switch.</li>
</ul>
&nbsp;

Think carefully about the definitions given above for output actions. <strong>Remember that if you match a packet, no action (i.e., packet will be dropped) will be done unless you set an output action as the packet is pulled from the stream until it is resolved</strong>.

<strong>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </strong>

<h2><a name="_Toc35959"></a>Example:&nbsp;&nbsp;&nbsp; Sending&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; a&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; FlowMod&nbsp;&nbsp;&nbsp; Object</h2>
The following example describes how to create a flow modification object including matching a destination IP Address, IP Type, and Destination IP Port, and setting an action that would redirect the matching packet out to physical switch port number 4 (note that you generally DO NO KNOW what physical switch port to use.

&nbsp;

&nbsp;

&nbsp;

Flow Modification Objects work as thus:

<ol>
<li>Packet enters the system and is examined by the Flow Modification Objects (1 for each rule in your configuration ruleset)</li>
<li>The packet will then be examined to see if the different header items match the items specified for that rule.</li>
<li>If the packet matches all the applicable items, it is pulled from the stream for you to program an action for it (forward it, readdress it, change it). If you don’t do an action for it, the package is essentially dropped.&nbsp; If the packet does not match all the applicable header items, it continues to the next Flow Modification rule to test it.&nbsp; If it isn’t matched by any rules, it is passed on to the specific destination.</li>
</ol>
&nbsp;

For this project, you are making a flow modification object and action while using a matching pattern that can match any or all of the different parameters&nbsp; of the header.&nbsp; Make your implementation generic.

&nbsp;

<h1><a name="_Toc35960"></a>Appendix&nbsp;&nbsp;&nbsp; D:&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Review&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; of&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Mininet</h1>
<strong>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </strong>

&nbsp;

Mininet is a network simulator that allows you to explore SDN techniques by allowing you to create a network topology including virtual switches, links, hosts/nodes, and controllers. It will also allow you to set the parameters for each of these virtual devices and will allow you to simulate real-world applications on the different hosts/nodes.

The following code sets up a basic Mininet topology similar to what is used for this project:

#!/usr/bin/python

&nbsp;

from mininet.topo import Topo from mininet.net&nbsp; import Mininet

from mininet.node import CPULimitedHost, RemoteController from mininet.util import custom from mininet.link import TCLink

from mininet.cli&nbsp; import CLI

&nbsp;

class FirewallTopo(Topo):&nbsp;&nbsp;&nbsp;&nbsp; def __init__(self, cpu=.1, bw=10, delay=None, **params):

super(FirewallTopo,self).__init__()

&nbsp;

# Host in link configuration&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; hconfig = {‘cpu’: cpu}

lconfig = {‘bw’: bw, ‘delay’: delay}

&nbsp;

# Create the firewall switch&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; s1 = self.addSwitch(‘s1’)

&nbsp;

hq1 = self.addHost(‘hq1′,ip=’10.0.0.1′,mac=’00:00:00:00:00:1e’, **hconfig)&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; self.addLink(s1,hq1)

&nbsp;

&nbsp;

us1 = self.addHost( ‘us1′, ip=’10.0.1.1′, mac=’00:00:00:01:00:1e’, **hconfig)&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; self.addLink(s1,us1)

&nbsp;

This code defines the following virtual objects:

<ul>
<li>Switch s1 – this is a single virtual switch with the label ‘s1’. In Mininet, you may have as many virtual ports as you need – for Mininet, “ports” are considered to be a virtual ethernet jack, not an application port that you would use in building your firewall.</li>
<li>Hosts hq1 and us1 – these are individual virtual hosts that you can access via xterm and other means. You can define the IP Address, MAC/Hardware Addresses, and configuration parameters that can define cpu speed and other parameters using the hconfig dictionary.</li>
<li>Links between s1 and hq1 and s1 and us1 – consider these like an ethernet cable that you would run between a computer and the switch port. You can define individual port numbers on each side (i.e., port on the host and port on the virtual switch), but it is advised to let Mininet automatically wire the network. Like hosts, you can define configuration parameters to set link speed, bandwidth, and latency.</li>
</ul>
<strong><u>REMINDER – PORTS MENTIONED IN MININET TOPOLOGIES ARE WIRING PORTS ON THE VIRTUAL</u> <u>SWITCH, NOT APPLICATION PORT NUMBERS.</u></strong>

Useful Mininet Commands:

<ul>
<li>For this project, you can start Mininet and load the firewall topology by running the <strong>./start-topology.sh</strong> from the project directory. You can quit Mininet by typing in the <strong>exit</strong></li>
<li>After you are done running Mininet, it is recommended that you cleanup Mininet. There are two ways of doing this. The first is to run the <strong>sudo mn -c</strong> command from the terminal and the second is to use the <strong>./cleanup.sh</strong> script provided in the project directory. Do this after every run to minimize any problems that might hang or crash Mininet.</li>
<li>You can use the xterm command to start an xterm window for one of the virtual hosts. This command is run from the mininet&gt; prompt. For example, you can type in <strong>us1 xterm &amp;</strong> to open a xterm window for the virtual host us1. The &amp; causes the window to open and run in the background. In this project, you will run the test-*-client.py and test-*-server.py in each host to test connectivity.</li>
<li>The <strong>pingall</strong> command that is run from the mininet&gt; prompt will cause all hosts to ping all other hosts. Note that this may take a long time. To run a ping between two hosts, you can specify <strong>host1 ping host2</strong> (for example, <strong>us1 ping hq1</strong> which will show the result of host us1 pinging hq1).</li>
<li>The <strong>help </strong>command will show all Mininet commands and <strong>dump</strong> will show information about all hosts in the topology.</li>
</ul>
&nbsp;
