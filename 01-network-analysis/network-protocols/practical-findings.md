Network Protocols Practical Lab Report

Objective

To understand how network protocols work and observe network traffic using Windows Command Prompt and Wireshark.

Tools Used
	•	Windows Command Prompt
	•	Wireshark

Practical Exercises

Exercise 1: DNS Lookup

Command used:

nslookup google.com

Purpose:
To observe how a domain name is translated into an IP address.

Observation:
  1. The DNS server contacted was 192.168.43.1.
	2.	The first DNS request timed out after two seconds.
	3.	The lookup subsequently returned a successful non-authoritative answer.
	4.	The domain google.com resolved to multiple IPv4 and IPv6 addresses.
	5.	This demonstrates how DNS helps computers locate websites using their domain names.

Exercise 2: HTTPS Connection

Command used:

curl.exe https://example.com

Purpose:
To establish an HTTPS connection to a website.

Observation:
	1.	The command executed successfully.
	2.	The website returned HTML content.
	3.	The response contained the page title “Example Domain”.
	4.	The website content was returned to the Command Prompt rather than displayed as a formatted webpage.

Exercise 3: TCP Traffic

Wireshark display filter:

tcp

Purpose:
To observe TCP communication.

Observation:
[Describe the TCP packets you observed.]

Exercise 4: HTTPS Traffic

Wireshark display filter:

tcp.port == 443

Purpose:
To identify TCP traffic using port 443.

Observation:
[Describe what you observed.]

Conclusion

This practical exercise helped me understand DNS resolution, TCP communication, and HTTPS connections.
