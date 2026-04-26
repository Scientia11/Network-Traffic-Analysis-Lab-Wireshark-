Infected Host Details:


## Indicators Of Compromise
1. The domain name in the http request URL  hxxp[://]128[.]254[.]207[.]55/86607[.]dat
  is an  IP address.       from 10.0.0.149 to

2. The GET request was made to a dat file

3. In the HTTP stream of the GET request, the  User-Agent is "curl". Typically an end user will never have "curl" as thier User-Agent unless they execute some script either knowingly or unknowingly.

4. In the body of the HTTP stream of the GET request, the victim downloaded a windows executable file with the file signataure MZ.
- File name: 86607.dat
- Hash: 713207d9d9875ec88d2f3a53377bf8c2d620147a4199eb183c13a7e957056432

5. 55 virustotal security vendors flagged the dat file as malicious

6. Malwarebazaar idenfied the file hash to be associated with the Quakbot malware family'.

7. In the arp requests filter there was several arp broadcasts to IP addresses in descending order which is a clear indication of arp scanning.

8. In the SMTP http stream body decode there's a potentially compromised user credentials with following details
- Username: arthit@macnels.co.th
- Password: Art123456

