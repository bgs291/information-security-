# h2 Spiderwebs

OWSAP: OWSAP 10 2021

Summary of: A05:2021-Security Misconfiguration, A06:2021-Vulnereable and outdated Components, A03:2021-Injection.

•	A05:2021-Security Misconfiguration

Overview:

90% of apps tested for misconfigurations; 4% incidence rate.
208K+ Common Weakness Enumeration (CWE) occurrences.
Notable CWEs: CWE-16 Configuration, CWE-611 XML External Entity Reference.

Description:
Vulnerabilities due to poor security hardening, permissions, outdated software.
Risks include enabling unnecessary features, default accounts, and insecure error handling.
A repeatable security configuration process is crucial.

Prevention:
•	Implement secure, repeatable installation processes.
•	Use a minimal platform, update configurations, employ segmentation.
•	Send security directives, automate verification.

Attack Scenarios:
•	Attackers exploit sample apps, unpatched servers, or cloud storage misconfigurations.
•	Directory listing enables code access.
•	Detailed error messages expose sensitive info.
•	Default sharing permissions leak data.


•	A06:2021-Vulnereable and outdated Components

Overview:

Ranked #2 in the Top 10 community survey, and data confirms its significance.
Vulnerable Components category lacks Common Vulnerability and Exposures (CVEs) mappings to included CWEs, thus defaulting to an impact weight of 5.0.
Notable CWEs include CWE-1104: Use of Unmaintained Third-Party Components and two from Top 10 lists of 2013 and 2017.

Description:
Vulnerable if unaware of component versions (client-side and server-side), including direct and nested dependencies.
Vulnerabilities arise from using unsupported, outdated software, including OS, web servers, databases, APIs, and all components, environments, and libraries.
Lack of regular vulnerability scanning and security bulletin subscriptions.
Delayed or infrequent patching leaves systems exposed to known vulnerabilities.
Incompatibility testing of updated libraries is skipped.
Security misconfigurations contribute to the risk.

How to Prevent:
•	Implement a patch management process:
•	Remove unused dependencies, features, components, files, and documentation.
•	Continuously track component versions and their dependencies using tools like OWASP Dependency Check.
•	Monitor sources like CVE and NVD for vulnerabilities.
•	Obtain components from official, secure sources.
•	Monitor unmaintained components and apply virtual patches if necessary.
•	Maintain a plan for ongoing updates and configuration changes.

Example Attack Scenarios:
o	Components run with the same privileges as the application, making flaws in any component potentially impactful.
o	Example: CVE-2017-5638, a Struts 2 remote code execution vulnerability, has led to significant breaches.
o	IoT devices, challenging to patch, remain vulnerable.
o	Example: Exploitation of unpatched IoT devices.
o	Automated tools help attackers find unpatched or misconfigured systems.
o	Example: Shodan IoT search engine identifies devices susceptible to Heartbleed vulnerability.


•	A03:2021-Injection

Overview:

Injection vulnerability drops to third place.
94% of applications tested for injection, with an incidence rate maxing at 19% and averaging 3%.
274,000 occurrences of injection vulnerabilities.
Notable CWEs: CWE-79 (Cross-site Scripting), CWE-89 (SQL Injection), CWE-73 (External Control of File Name or Path).

Description:
Vulnerabilities occur when:
User-supplied data isn't validated, filtered, or sanitized.
Dynamic queries or non-parameterized calls lack context-aware escaping.
Hostile data impacts object-relational mapping (ORM) searches.
Malicious data is used or concatenated in dynamic queries, commands, or stored procedures.
Common injections: SQL, NoSQL, OS command, ORM, LDAP, and Expression Language (EL) injection.
Source code review and automated testing are crucial for detection.
Tools like SAST, DAST, and IAST should be integrated into the CI/CD pipeline.

How to Prevent:
•	Keep data separate from commands and queries:
•	Prefer safe APIs, parameterized interfaces, or ORM tools.
•	Be cautious with stored procedures that concatenate queries and data.
•	Implement server-side input validation.
•	Escape special characters in dynamic queries.
•	Use SQL controls like LIMIT to prevent mass data disclosure during SQL injection.

Example Attack Scenarios:
•	Application constructs a vulnerable SQL call with untrusted data.
SQL query: "SELECT * FROM accounts WHERE custID='" + request.getParameter("id") + "'"
Attacker modifies 'id' parameter to: ' UNION SLEEP(10);--
Changes query meaning to return all records from 'accounts' table.
More severe attacks could manipulate or delete data or invoke stored procedures.

•	Application blindly trusts frameworks, leading to vulnerable queries (e.g., Hibernate Query Language - HQL).
HQL query: Query HQLQuery = session.createQuery("FROM accounts WHERE custID='" + request.getParameter("id") + "'")
Attacker manipulates 'id' parameter: ' UNION SELECT SLEEP(10);--
Alters query to retrieve all 'accounts' table records.
More malicious attacks may involve data manipulation, deletion, or stored procedure invocation.

•	webgoat.


![IMG_2234](https://github.com/bgs291/information-security-/assets/142784195/d04a3ac7-91e2-42ce-9b7b-4e3941818a08)











