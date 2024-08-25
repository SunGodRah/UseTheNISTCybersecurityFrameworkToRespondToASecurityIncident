# Use the NIST Cybersecurity Framework to respond to a security incident

## Scenario

You are a cybersecurity analyst working for a multimedia company that offers web design services, graphic design, and social media marketing solutions to small businesses. Your organization recently experienced a DDoS attack, which compromised the internal network for two hours until it was resolved.

During the attack, your organization’s network services suddenly stopped responding due to an incoming flood of ICMP packets. Normal internal network traffic could not access any network resources. The incident management team responded by blocking incoming ICMP packets, stopping all non-critical network services offline, and restoring critical network services.

The company’s cybersecurity team then investigated the security event. They found that a malicious actor had sent a flood of ICMP pings into the company’s network through an unconfigured firewall. This vulnerability allowed the malicious attacker to overwhelm the company’s network through a distributed denial of service (DDoS) attack.

To address this security event, the network security team implemented the following measures:

- **A new firewall rule** to limit the rate of incoming ICMP packets.
- **Source IP address verification** on the firewall to check for spoofed IP addresses on incoming ICMP packets.
- **Network monitoring software** to detect abnormal traffic patterns.
- **An IDS/IPS system** to filter out some ICMP traffic based on suspicious characteristics.

## Task

Use this security event to create a plan to improve your company’s network security, following the National Institute of Standards and Technology (NIST) Cybersecurity Framework (CSF). 

## My Incident Report Analysis

<p align="center">
  <img src="https://github.com/user-attachments/assets/e11ea8a5-6d34-4514-b4f3-3486c6b72606" height="80%" width="80%" alt=""/>
</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/47731222-4fc1-4d7d-8aa3-0ca7611a73d3" height="80%" width="80%" alt="" />
</p>

