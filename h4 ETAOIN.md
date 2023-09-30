

h4 ETAOIN

x) 

1.1 TERMINOLOGY
Introduces basic cryptography terminology.
Defines key concepts like plaintext, ciphertext, encryption, and decryption.
Establishes a foundation for understanding cryptographic principles.

1.2 STEGANOGRAPHY
Discusses steganography as a technique for hiding information within other data.
Highlights the covert nature of steganographic methods.
Lays the groundwork for understanding how data can be concealed.

1.3 SUBSTITUTION CIPHERS AND TRANSPOSITION CIPHERS
Explores the fundamentals of substitution ciphers, where one symbol is replaced with another.
Examines transposition ciphers, which involve rearranging the order of symbols in a message.
Provides insight into early encryption techniques.

1.4 SIMPLE XOR
Introduces XOR (exclusive OR) operation as a basic cryptographic tool.
Demonstrates how XOR can be used for simple encryption.
Illustrates the concept of bitwise operations in cryptography.

1.5 ONE-TIME PADS
Discusses the concept of one-time pads as a theoretically unbreakable encryption method.
Emphasizes the importance of truly random keys in one-time pad encryption.
Highlights the limitations and challenges of implementing one-time pads in practice.

1.6 COMPUTER ALGORITHMS
Addresses the role of computer algorithms in modern cryptography.
Discusses how algorithms can be used to automate encryption and decryption processes.
Establishes the connection between mathematics and cryptography.


1.7 LARGE NUMBERS
Explores the significance of large numbers in cryptography.
Emphasizes the difficulty of factoring large composite numbers.
Introduces the concept of key length and its impact on security in cryptographic systems.


y) This is the frequency distribution of letters in the Arabic language, along with the six most common letters:

                                                                                                                                                                 ا (Alif) - 28%
                                                                                                                                                                  	ي (Ya) - 11%
                                                                                                                                                                	م (Meem) - 8%
                                                                                                                                                                 	و (Waw) - 7%
                                                                                                                                                                 	ل (Lam) - 6%
                                                                                                                                                                	ن (Noon) - 5%






              Z) LastPass password manager.

Threats it Protects Against:

•	Password Reuse: It encourages the use of strong, unique passwords for each online account, reducing the risk of password reuse.
•	Password Theft: LastPass encrypts and securely stores passwords, reducing the likelihood of passwords being stolen.
•	Phishing: It can automatically fill in login credentials only on legitimate websites, helping users avoid phishing scams.
•	Brute Force Attacks: LastPass employs encryption and strong security measures to guard against unauthorized access, including brute force attacks.



Information Encryption:

LastPass encrypts sensitive information such as passwords, notes, and payment card details using strong encryption algorithms. This information is securely stored in a user's vault.
What's not encrypted are the user's master password and certain non-sensitive account information that is required for LastPass functionality, like the names of websites and usernames.

License:

LastPass offers both a free and a paid version. The paid version is known as LastPass Premium.
The license categorizes users based on their subscription type (e.g., Free, Premium, Family) and the associated features and capabilities.






Data Storage:

LastPass provides users with the option to store their data either locally or in the cloud.
When stored in the cloud, LastPass servers are used, but the specific location of these servers may vary. LastPass has servers in multiple regions, including the United States and Europe.
The choice of data storage location may also depend on the user's selected server region or data center.

Data Protection:

LastPass employs robust encryption and hashing techniques to protect user data.
Data is encrypted on the user's device before it's sent to LastPass servers, and only the user has the decryption key (master password).
Multi-factor authentication (MFA) is available for added security.
LastPass has a strong security track record and undergoes regular security audits.





b) Demonstrate the use of a password manager.

All Items: This page serves as a central repository for all your stored information, including passwords, notes, addresses, payment cards, and bank accounts. It allows you to view and manage all your saved data in one place.




<img width="1188" alt="Untitled" src="https://github.com/bgs291/information-security-/assets/142784195/18373fbe-4128-4f36-85c6-6acdef686dc2">





Sharing Center: The Sharing Center is where you can securely share passwords and other sensitive information with trusted individuals or team members. It provides controlled access to shared items without revealing the actual data.





<img width="1402" alt="Untitled 2" src="https://github.com/bgs291/information-security-/assets/142784195/822505de-99a9-4d92-b108-388533d88494">






Passwords: This section allows you to manage and organize your passwords. You can create, edit, and delete password entries, and LastPass can generate strong, unique passwords fo  you.



<img width="370" alt="image" src="https://github.com/bgs291/information-security-/assets/142784195/fa0989c2-4e01-4990-be29-c8c7f1ce9deb">

 


Payment Cards: You can store your credit/debit card information here for quick access during online shopping. LastPass helps autofill payment details, making the checkout process more efficient.



<img width="396" alt="image" src="https://github.com/bgs291/information-security-/assets/142784195/5ff91d35-0738-4485-9c5f-79f616033e2f">
 


Security Dashboard: This feature provides an overview of your online security, including the strength of your passwords, security challenges, and suggestions for improving your digital security posture.



<img width="402" alt="image" src="https://github.com/bgs291/information-security-/assets/142784195/786986e0-cf19-478c-8ebb-5e3112c6308e">

 




Emergency Access: This page allows you to designate trusted individuals who can request access to your LastPass vault in case of an emergency or if you're locked out. It ensures a secure way to share vital information when needed.



<img width="414" alt="image" src="https://github.com/bgs291/information-security-/assets/142784195/3524ce2a-ee0b-44f2-86f1-b9ad952e5855">























h4 September2023

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

 


LastPass simplifies and enhances digital security by offering a centralized platform for managing passwords and sensitive information, while also providing tools to share securely and monitor overall security health.
