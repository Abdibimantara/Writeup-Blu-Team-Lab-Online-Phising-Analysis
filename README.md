# Writeup BTLO- Phising Analysis
![image](https://user-images.githubusercontent.com/43168046/169974112-384e3611-9d30-4845-8a07-2e35e565e293.png)

Simple Writeup, Bluteam CTF from Blue Team Labs Online 
## Scenario

A user has received a phishing email and forwarded it to the SOC. Can you investigate the email and attachment to collect useful artifacts?

https://blueteamlabs.online/home/challenge/16

![image](https://user-images.githubusercontent.com/43168046/169943650-6de5d8c7-76f7-4b64-b0cc-b5996c66ed2f.png)

## Challenge Submission

### 1. Who is the primary recipient of this email ?
![image](https://user-images.githubusercontent.com/43168046/169944226-2c0e3158-951c-44e6-a10a-ac89fdd4d7cf.png)
### Answer : kinnar1975@yahoo.co.uk

### 2. What is the subject of this email ?
![image](https://user-images.githubusercontent.com/43168046/169953228-bb6f20f1-4eb1-41a4-8481-470532567e8e.png)
### Answer : Undeliverable: Website contact form submission 

### 3. What is the date and time the email was sent ? 
![image](https://user-images.githubusercontent.com/43168046/169953627-292c2ae9-7f76-4978-8842-fafdd0a0b698.png)
### Answer : 18 March 2021 04:14 

### 4. What is the Originating IP? 
![image](https://user-images.githubusercontent.com/43168046/169955201-d279aea1-329d-45a3-a53f-6ce713aa7846.png)
### Answer : 103.9.171.10

### 5. Perform reverse DNS on this IP address, what is the resolved host? (whois.domaintools.com) ?
![image](https://user-images.githubusercontent.com/43168046/169956132-f7d33f9b-5127-487f-9fd6-30cbd06994ea.png)
### Answer : 	c5s2-1e-syd.hosting-services.net.au

### 6. What is the name of the attached file ? 
![image](https://user-images.githubusercontent.com/43168046/169956837-398ce37b-4dbf-4ea0-a16d-52da4821e31f.png)
### Answer : 	Website contact form submission.eml

### 7. What is the URL found inside the attachment ? 
![image](https://user-images.githubusercontent.com/43168046/169972642-443f3948-e15c-4600-b22e-33ed5529a5f9.png)
### Answer : https://35000usdperwwekpodf.blogspot.sg?p=9swghttps://35000usdperwwekpodf.blogspot.co.il?o=0hnd 

### 8. What service is this webpage hosted on ? 
![image](https://user-images.githubusercontent.com/43168046/169972642-443f3948-e15c-4600-b22e-33ed5529a5f9.png)
### Answer : blogspot

### 9. What service is this webpage hosted on ? 
![image](https://user-images.githubusercontent.com/43168046/169973927-a3dda369-f540-4fac-ba72-a9b22a71d35d.png)
### Answer : Blog Has been removed

