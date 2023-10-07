# h1- First homework h1


EP 6: The Beirut Bank Job 

Testing Bank Security

Jason E. Street, an InfoSec expert, specializes in testing physical security.
He conducts Security Awareness Engagements to expose vulnerabilities.
These engagements involve real-world scenarios to educate companies about security.

The Beirut Bank Job.
Jason recounts his experience of conducting a security engagement in a bank in Beirut.
He explains his approach of walking into a bank and gaining access to computers.
The objective is to test physical security, not steal cash.

First Bank Break-In
Jason bluffed his way into the first bank, used a USB rubber ducky to assess vulnerability, and gained full access.

Second Bank Break-In
Jason entered the wrong bank, posed as a Microsoft representative to compromise computers, and accidentally entered an unrelated bank.

Third Bank Break-In
Jason, searching for a restroom, plugged in a USB rubber ducky, faced employee questions, and attempted to bluff with a forged email, but it didn't work.  


Hutchins et al 2011: Intelligence-Driven Computer Network Defense Informed by Analysis of Adversary Campaigns and Intrusion Kill Chains, chapters Abstract,
3.2 Intrusion Kill Chain and 3.3 Courses of Action  

3.2 Intrusion Kill Chain introduces the concept of the Intrusion Kill Chain, which is a systematic process for engaging cyber adversaries. 
It's based on the U.S. military's F2T2EA model: find, fix, track, target, engage, assess. The Intrusion Kill Chain for cyber-attacks consists of these phases:

Reconnaissance: Research and identification of targets.
Weaponization: Combining malware with an exploit.
Delivery: Transmitting the weapon to the target, often via email or websites.
Exploitation: Triggering the weapon on the victim's system.
Installation: Installing remote access tools for persistence.
Command and Control (C2): Establishing a channel for remote control.
Actions on Objectives: Achieving the attacker's goals, often involving data theft or system compromise


3.3 Courses of Action underscores the value of the intrusion kill chain as a model for actionable intelligence in cybersecurity. 
Defenders can enhance their security measures by aligning them with the specific phases of an adversary's attack process. 
This approach enables measurement of performance and effectiveness, facilitating the development of investment plans to address any gaps in defensive capabilities.
It's essentially about intelligence-driven Cyber Network Defense (CND) - making security decisions based on a deep understanding of the adversary.

# h1- Install Debian 12-Bullseye virtual machine in VirtualBox.
(updated in 7.10.2023)
Installation of Debian 12:

I visited the Debian website and downloaded the Debian 12 ISO image for the amd64 architecture (64-bit).

I set up a Virtual Machine using VirtualBox 6 to create a new virtual machine. During the setup, I allocated resources such as CPU cores, RAM, and storage.

I mounted the Debian ISO by attaching the Debian 12 ISO image to the virtual machine's virtual CD/DVD drive in my VirtualBox.

I started the virtual machine, selecting the "Install" option from the Debian boot menu.

I followed the installation steps, configuring language, location, keyboard layout, hostname, and network settings as per the on-screen instructions.

The installation process began, and I was prompted to set up a root password and create a regular user account.

Afterward, I logged in with the user credentials I had created during the installation process.

For post-installation configuration, I updated the system, installed additional software, and adjusted specific settings as needed.

I encountered an issue when attempting to download Debian 12 on VirtualBox 7, so I had to remove the "7" and try with VirtualBox 6, which proved successful.

My Debian 12 installation in the virtual machine was now ready for use. (updated in 7.10.2023)

<img width="1436" alt="Untitled" src="https://github.com/bgs291/information-security-/assets/142784195/03cc054a-4518-4c74-9fed-bbcc5033544e">

