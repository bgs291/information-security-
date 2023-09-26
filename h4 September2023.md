

X)   2.3 ONE-WAY FUNCTIONS

One-Way Functions: These are essential in computer security. They're like puzzles that are easy to solve in one direction but hard to solve in reverse.

Example: Breaking a plate into pieces is simple, but putting it back together is tough.
Existence Uncertainty: We're not entirely sure if these functions truly exist or how to create them. But some math problems seem like they might be one-way functions.
Limited Use: One-way functions can't be used for straightforward encryption because you can't easily decrypt the message.
Trapdoor One-Way Functions: These are special one-way functions with a secret trick. They're still easy to use one way, hard to reverse, but if you know the secret, you can go backward easily.
Example: Taking a watch apart is like a trapdoor one-way function. It's hard to put it back together, but if you have the instructions, it's much easier.


2.4 ONE-WAY HASH FUNCTIONS

One-Way Hash Functions: These are like digital fingerprints for data. Easy to create, almost impossible to reverse.

How They Work: They take data and turn it into a unique code. Even a tiny change in data gives a completely different code.
No Secrets: Everyone knows how they work. Security comes from the difficulty of reversing the code.
Practical Use: Great for checking if files are the same and ensuring secure transactions.
Message Authentication Codes (MACs): Like digital fingerprints with a secret key for extra security. Only those with the key can check the code.

•	Särökaari 2018: Phishing trough email (video, 33 min)
What is phishing?
•	It is practice of sending e-mails that appear to be from reputable sources 
•	Goal is to influence or gain personal information
•	E-mail may contain malicious attachment or link to illegitimate site, which is designed to trick the victim to provide PII or login credentials.

Why Do People Click Phishing Links?
Through an experiment conducted at a university in Germany during Blackhat 2016, researchers explored the factors that lead individuals to click on dangerous links despite security concerns. They sent a non-existent link from a fictitious sender to 1200 students and observed the following 

results: 
Curiosity (34%) 
Message Alignment with Expectations (27%)
Perceived Familiarity with the Sender (16%)

Goals of engagement 
It’s important to define the goals of the social engineering engagements
For example, fishing campaign goal is to steal credential or to track and measure number of clicks. 
Protecting yourself legally by ensuring that customers clearly understand that you can only providing anonymize data.
Protecting mechanisms and how to bypass them.
Sender Policy Framework (SPF): Specifies authorized mail servers for a domain, reducing email spoofing and improving deliverability.
DomainKeys Identified Mail (DKIM): Adds digital signatures to emails, ensuring their authenticity and integrity during transmission.
Domain-based Message Authentication, Reporting, and Conformance (DMARC): Sets email authentication policies, enhances security, and provides reporting on email delivery and authentication results to protect against email spoofing and phishing attacks. 
Using SPF and DKIM records makes your domain more reputable and legitimate.

Filtering 

Malware/Spam Filtering: Identifies and blocks malicious software and unwanted email messages, reducing security threats and inbox clutter.

URL Whitelisting/Web Filtering: Permits or restricts access to specific websites or web content, enhancing security and controlling internet usage.

Greylisting: Delays email delivery from unknown sources, forcing legitimate senders to retry, while blocking spam and unauthorized emails.

Site Cloning: Illegally duplicates websites, often for fraudulent purposes like phishing or deception.





IDN Homograph attack.

Exploits the visual similarity of characters from different scripts to deceive users into thinking they're interacting with a legitimate website, potentially leading to phishing or fraud.
Unicode chars are very hard to distinguish from common ASCII chars 
Issue fixed in chrome is configurable in Firefox to detect the attacks.

What usually work in phishing?

Package delivery message 
Mail from ServiceDesk / IT department
LinkedIn, Gmail, Dropbox etc.
Something relevant to recipient environment.


Simply clicking a link is not usually enough…
Some message in emails mentioning that password has been leaked pleas click this link and follow the restrictions usually works.


What to do?

Implement SPF, DKIM and DMARC
Keep your domains safe
Educate and train users 
Secure your infrastructure 

 
a)	![IMG_2300](https://github.com/bgs291/information-security-/assets/142784195/5f79a5ec-57c2-4072-a051-ca7a4b4a13b3)

b)	![IMG_2301](https://github.com/bgs291/information-security-/assets/142784195/befa9fba-00ea-43c5-96f7-68a02deb7454)
