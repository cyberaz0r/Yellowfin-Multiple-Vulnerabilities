# Yellowfin < 9.6.1 Multiple Vulnerabilities

## Table of contents:
- [Vulnerability 1: Stored XSS](#xss)
- [Vulnerability 3: Profile pics IDOR](#idor1)
- [Vulnerability 3: Images IDOR](#idor2)



## Vulnerability 1: Stored XSS

### Vulnerability
Stored Cross-Site Scripting

### Affected Products and Versions
Yellowfin < 9.6.1

### CVEID:
CVE-2021-36387

### CVSSv3.1 Score
5.4 (Medium)

### CVSSv3.1 Attack Vector
AV:N/AC:L/PR:L/UI:R/S:C/C:L/I:L/A:N

### Short Description
In Yellowfin before 9.6.1 there is a Stored Cross-Site Scripting vulnerability in the video embed functionality exploitable through a specially crafted HTTP POST request to the page "ActivityStreamAjax.i4".

### Remediation
Update Yellowfin to the latest version available

### Discoverer
Michele Di Bonaventura (cyberaz0r)

### Reference
https://wiki.yellowfinbi.com/display/yfcurrent/Release+Notes+for+Yellowfin+9#ReleaseNotesforYellowfin9-Yellowfin9.6

## Vulnerability 2: Profile pics IDOR

### Vulnerability
Insecure Direct Object Reference

### Affected Products and Versions
Yellowfin < 9.6.1

### CVEID
CVE-2021-36388

### CVSSv3.1 Score
7.5 (High)

### CVSSv3.1 Attack Vector
AV:N/AC:L/PR:N/UI:N/S:U/C:H/I:N/A:N

### Short Description
In Yellowfin before 9.6.1 it is possible to enumerate and download users profile pictures through an Insecure Direct Object Reference vulnerability exploitable by sending a specially crafted HTTP GET request to the page "MIIAvatarImage.i4".

### Remediation
Update Yellowfin to the latest version available

### Discoverer
Michele Di Bonaventura (cyberaz0r)

### Reference
https://wiki.yellowfinbi.com/display/yfcurrent/Release+Notes+for+Yellowfin+9#ReleaseNotesforYellowfin9-Yellowfin9.6

## Vulnerability 3: Images IDOR

### Vulnerability
Insecure Direct Object Reference

### Affected Products and Versions
Yellowfin < 9.6.1

### CVEID
CVE-2021-36389

### CVSSv3.1 Score
7.5 (High)

### CVSSv3.1 Attack Vector
AV:N/AC:L/PR:N/UI:N/S:U/C:H/I:N/A:N

### Short Description
In Yellowfin before 9.6.1 it is possible to enumerate and download uploaded images through an Insecure Direct Object Reference vulnerability exploitable by sending a specially crafted HTTP GET request to the page "MIImage.i4".

### Remediation
Update Yellowfin to the latest version available

### Discoverer
Michele Di Bonaventura (cyberaz0r)

### Reference
https://wiki.yellowfinbi.com/display/yfcurrent/Release+Notes+for+Yellowfin+9#ReleaseNotesforYellowfin9-Yellowfin9.6
