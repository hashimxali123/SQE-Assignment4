
# Security Requirments:

## 1- Secrets management:
Secrets management is the practise of controlling the usage of passwords, keys, APIs, and other confidential information in applications, services, privileged accounts, and other delicate areas of the IT ecosystem.

![secrets-management-overview](https://user-images.githubusercontent.com/105812482/206726750-d8e8702e-9b77-4025-a268-a70a739a09fc.png)

Users can be malicious too for our software or website or can apply some hacking techniques to break into our system. There should be some
way like using `ReCaptcha`. ReCaptcha is also a vital thing to prevent some hacking bot or program to break inton our website or system. So,
we will be using the ReCaptcha. Moreover, we will try to protect our API's if we use, we will try to regenerate the `keys` and `tokens` of 
API's to protect ourselves.

## Requirments:
### 1. System should change the API key and Token after every 10 seconds.
#### 1.1 System must have API key and token ciphered using `Caesar Cipher` algorithm.
#### 1.2 System must have ReCaptcha online whenever someone tries to get to the API page.


## 2- In-Built Security:
We should be using the In-Built security, like implementing the whole protection in the code. Like to prevent the `SQL injection`, which is a
hacking technique.An SQL Injection vulnerability may affect any website or web application that uses an SQL database such as MySQL, Oracle, SQL Server, or others. Criminals may use it to gain unauthorized access to your sensitive data: customer information, personal data, trade secrets, intellectual property, and more. SQL Injection attacks are one of the oldest, most prevalent, and most dangerous web application vulnerabilities. The OWASP organization (Open Web Application Security Project) lists injections in their OWASP Top 10 2017 document as the number one threat to web application security.

![Functioning-of-an-SQL-Injection](https://user-images.githubusercontent.com/105812482/206729120-0a6b05be-4b8b-4542-a69c-f841ed5a934e.png)

### Solution:
Above mentioned image shows the the SQL injection attack on the database of the targeted Software or website, We can use the triggers or input validation and parametrized queries including prepared statements and etc and we can also hire some ethical hackers to secure our software and 
detect and sort out the vulnerabilities of our software or website.


## Requirments:
### 1. System should be able to manage the SQL injections of atleast 100 attacks.
#### 1.1 System should triggers maintained in SQL files to prevent hacking.
#### 1.2 System should have inbuilt login in code to prevent SQL injection.
### 2 System should detect the IP address of malicious codes.
#### 2.1 System should detect SQL injection or any malicious activity IP and block that IP.

