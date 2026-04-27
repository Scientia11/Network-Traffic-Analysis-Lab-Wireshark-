## 2026-02-28 - TRAFFIC ANALYSIS EXERCISE

Link to the exercise: 
https://www.malware-traffic-analysis.net/2026/02/28/index.html

## ENVIRONMENT:
- LAN segment range: 10.2.28[.]0/24 (10.2.28[.]0 through 10.2.28[.]255)
- Domain: easyas123[.]tech
- AD environment name: EASYAS123
- Domain Controller: 10.2.28[.]2 – EASYAS123-DC
- LAN segment gateway: 10.2.28[.]1
- LAN segment broadcast address: 10.2.28[.]255

## BACKGROUND:
As dynamic go-getter at a Security Operations Center (SOC), you check the Security
Information and Event Management (SIEM) system and find several signature hits for
NetSupport Manager RAT from 45.131.214[.]85 over TCP port 443. The activity started
on 2026-02-28 at 19:55 UTC..

Using this information, you quickly retrieve a packet capture (pcap) of the traffic from the
internal IP address that triggered these alerts. It's all on you now! You're expected to write
up an incident report, so someone can track down the infected computer and put a stop to
this nonsense!

Armed with pcap, you intend to find that infected host.

## TASK:
For this exercise, answer the following questions for your incident report:
- What is the IP address of the infected Windows client?
- What is the MAC address of the infected Windows client?
- What is the host name of the infected Windows client?
- What is the user account name from the infected Windows client?
- What is the full name of the user from the user account?


## Incident Report
 Victim Details:
- IP address: 10.1.28[.]88
- Host name: DESKTOP-TEYQ2NR
- MAC address: 00:19:d1:b2:4d:ad
- Windows user account name: brolf
- Full name of the user: Becka Rolf

## Further Analysis
- the attacker is usig http over port 443
- the url is using an ip address instead of a domain name
- There was a post request to the url hxxp[://]45[.]131[.]214[.]85/fakeurl[.]htm  which has been flagged by 14 security vendors on virus total as malicious
