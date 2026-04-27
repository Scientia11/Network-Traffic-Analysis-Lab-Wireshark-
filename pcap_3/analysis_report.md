## 2026-01-31 - TRAFFIC ANALYSIS EXERCISE
Link to the exercise:
- https://www.malware-traffic-analysis.net/2026/01/31/index.html

## ENVIRONMENT:
- LAN segment range: 10.1.21[.]0/24 (10.1.21[.]0 through 10.1.21[.]255)
- Domain: win11office[.]com
- AD environment name: WIN11OFFICE
- Domain Controller: 10.1.21[.]2 – WIN-LU4L24X3UB7
- LAN segment gateway: 10.1.21[.]1
- LAN segment broadcast address: 10.1.21[.]255

## BACKGROUND:
As an analyst at a Security Operations Center (SOC), you check alerts for the past week
and find a signature hit for ET MALWARE Lumma Stealer Victim Fingerprinting
Activity that triggered on traffic from 153.92.1[.]49 over TCP port 80. The alert
triggered on 2026-01-27 at 23:05 UTC.
Using the information, you retrieve a packet capture (pcap) of the traffic from the internal IP
address that triggered the alert. Based on the pcap, you write up an incident report, so the
incident responders can track down the computer and associated user.

## TASK:
For this exercise, answer the following questions for your incident report:
- What is the IP address of the infected Windows client?
- What is the MAC address of the infected Windows client?
- What is the host name of the infected Windows client?
- What is the user account name from the infected Windows client?
- What is the full name of the user from the user account?
- What is the domain from 153.92.1[.]49 that triggered the alert for Lumma
Stealer?


## Incident Report

- The IP address of the infected Windows client is 10.1.21.58

- The MAC address of the infected Windows client is 00:21:5d:c8:0e:f2

- The host name of the infected Windows client is DESKTOP-ES9F3ML

- The user account name from the infected client is gwyatt

- The full name of the user from the user account is Gabriel Wyatt

- The domain from 153.92.1[.]49 that triggered the alert for Lumma Stealer is whitepepper.su

## Further Analysis
