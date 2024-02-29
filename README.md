<h1>Incident Response(NIST-CSF)</h1>


<h2>Description</h2>
In this project, I created an incident report based on one of the Google Cybersecurity Certificate example scenarios: 

You are a cybersecurity analyst working for a multimedia company that offers web design services, graphic design, and social media marketing solutions to small businesses. Your organization recently experienced a DDoS attack, which compromised the internal network for two hours until it was resolved.

During the attack, your organization’s network services suddenly stopped responding due to an incoming flood of ICMP packets. Normal internal network traffic could not access any network resources. The incident management team responded by blocking incoming ICMP packets, stopping all non-critical network services offline, and restoring critical network services. 

The company’s cybersecurity team then investigated the security event. They found that a malicious actor had sent a flood of ICMP pings into the company’s network through an unconfigured firewall. This vulnerability allowed the malicious attacker to overwhelm the company’s network through a distributed denial of service (DDoS) attack. 

To address this security event, the network security team implemented: 

A new firewall rule to limit the rate of incoming ICMP packets

Source IP address verification on the firewall to check for spoofed IP addresses on incoming ICMP packets

Network monitoring software to detect abnormal traffic patterns

An IDS/IPS system to filter out some ICMP traffic based on suspicious characteristics 
<br />


<h2>Utilities Used</h2>

- <b>Google Docs</b>
- <b>NIST-CSF Framework</b>
<h2>Project walk-through:</h2>

<p align="center">
ICMP packets recieved during the packet sniffing process: <br/>
<img src="https://i.imgur.com/aEabzxs.png"/>
<br />
<br />
Incident response:  <br/>
<img src="https://i.imgur.com/FKe5vcB.png"/>
<br />
