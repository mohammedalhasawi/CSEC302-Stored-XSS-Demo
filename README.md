# CSEC302-Stored-XSS-Demo


---Introduction to stored XSS--- 

-Stored cross site scripting is known as presistent XSS and it is the most damaging type of XSS attacks. It happens when the vulnerable application recives data from untrusted source and stores it, then includes it in the http response.

-Stored XSS rely on unsanitized user input points that stores the input scripts premaritally on the targeted server. The attacker uses these input points to inject a malicious payload mostly by using javascript code. For example the attacker might inject the script into a user input form or a comment field. 

-When the victim opens the attacked page the payload will be serverd to the browser as part of the html code  just like a reguler comment. Which means the victim will execute the malicious script just by viewing the affected page on their browser. 


-Here are some Impacts of XSS stored attacks:
 
* Session hijacking attacks
* Privilege escalation
* Disclosure of user files/data
* Installation of malware/Trojan programs
* Redirecting users to trustworthy-looking clone login forms for phishing attempts
* Web content spoofing





https://www.acunetix.com/websitesecurity/xss/

https://crashtest-security.com/stored-xss-attack/

https://portswigger.net/web-security/cross-site-scripting/stored


