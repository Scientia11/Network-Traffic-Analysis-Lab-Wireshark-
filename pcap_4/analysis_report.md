## 2026-02-28 - TRAFFIC ANALYSIS EXERCISE
Link to the exercise: https://www.malware-traffic-analysis.net/2025/06/13/index.html

## ENVIRONMENT:
- LAN segment range:  10.6.13[.]0/24   (10.6.13[.]0 through 10.6.13[.]255)
- Domain:  massfriction[.]com
- Active Directory (AD) domain controller:  10.6.13[.]3 - WIN-DQL4WFWJXQ4
- AD environment name:  MASSFRICTION
- LAN segment gateway:  10.6.13[.]1
- LAN segment broadcast address:  10.6.13[.]255
 

## YOUR TASK
For this exercise, answer the following questions for your incident report:
- What is the IP address of the infected Windows client?
- What is the mac address of the infected Windows client?
- What is the host name of the infected Windows client?
- What is the user account name from the infected Windows client?


## Incident Report
- The IP address of the infected Windows client is 10.2.28.88
- The MAC address of the infected Windows client is 00:19:d1:b2:4d:ad
- The host name of the infected Windows client is DESKTOP-TEYQ2NR
- The user account name from the infected Windows client is brolf
- The full user account name from the infected Windows client is Becka Rolf

## Further Analysis
- The was a communication between the infected client and the host at 45.131.214[.]85 using http(unencrypted protocol) over port 443(encrypted port)
- There was a POST request from the infected client to the host at  45.131.214[.]85 using the URL hxxp[://]45[.]131[.]214[.]85/fakeurl[.]htm  which has an IP address as the domain name.
- There POST request from the infected client to the host at 45.131.214[.]85 exfiltrated an encoded file with the name fakeurl.htm
- file hash: 2b69346572041eefe558a82b58d654237e087ce9ab4e0876254a40a8954279a9




