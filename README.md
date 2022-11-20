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



#Demo

I am going to use dvwa to demonstrate this vulnerability 

--vulnrable code--

<img width="1724" alt="Screen Shot 2022-11-20 at 3 46 03 AM" src="https://user-images.githubusercontent.com/70083913/202893652-e235d997-2525-4b54-bd84-d93f2271e26e.png">

<img width="1728" alt="Screen Shot 2022-11-20 at 3 46 24 AM" src="https://user-images.githubusercontent.com/70083913/202893662-199660b3-85b6-43dc-8990-680b8dddbbf4.png">



--fixed code--

<img width="1728" alt="Screen Shot 2022-11-20 at 3 46 42 AM" src="https://user-images.githubusercontent.com/70083913/202893674-bcbe91af-29b1-4652-86b8-2a61d3c72518.png">




https://www.acunetix.com/websitesecurity/xss/

https://crashtest-security.com/stored-xss-attack/

https://portswigger.net/web-security/cross-site-scripting/stored


