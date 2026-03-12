An ethical hacker follows processes similar to those of a malicious hacker. The steps to gain
and maintain entry into a computer system are similar no matter what the hacker’s intentions are.
Figure 1.2 illustrates the five phases that hackers generally follow in hacking a system. The
following sections cover these five phases.
![[Pasted image 20251231093426.png]]
## Phase 1: **Passive and Active Reconnaissance**
Passive reconnaissance involves gathering information regarding a potential target without
the targeted individual’s or company’s knowledge. Passive reconnaissance can be as simple as
watching a building to identify what time employees enter the building and when they leave.
However, it’s usually done using Internet searches or by Googling an individual or company
to gain information. This process is generally called information gathering. Social engineering
and dumpster diving are also considered passive information-gathering methods.
* Sniffing the network is another means of passive reconnaissance and can yield useful infor-mation such as IP address ranges, naming conventions, hidden servers or networks, and other available services on the system or network. 
* Sniffing network traffic is similar to building monitoring: A hacker watches the flow of data to see what time certain transactions take place and where the traffic is going.
Active reconnaissance involves probing the network to discover individual hosts, IP addresses,
and services on the network. This usually involves more risk of detection than passive reconnaissance and is sometimes called rattling the doorknobs. Active reconnaissance can give a hacker an indication of security measures in place (is the front door locked?), but the process also increases the chance of being caught or at least raising suspicion.
* Both passive and active reconnaissance can lead to the discovery of useful information to
use in an attack.
For example, it’s usually easy to find the type of web server and the operating
system (OS) version number that a company is using. This information may enable a hacker
to find a vulnerability in that OS version and exploit the vulnerability to gain more access.
## Phase 2: **Scanning**
Scanning involves taking the information discovered during reconnaissance and using it to
examine the network. Tools that a hacker may employ during the scanning phase can include
dialers, port scanners, network mappers, sweepers, and vulnerability scanners. Hackers are
seeking any information that can help them perpetrate attack such as computer names, IP
addresses, and user accounts.
## Phase 3: **Gaining Access**
This is the phase where the real hacking takes place. Vulnerabilities discovered during the
reconnaissance and scanning phase are now exploited to gain access. The method of connection the hacker uses for an exploit can be a local area network (LAN, either wired or wireless),local access to a PC, the Internet, or offline. Examples include stack-based buffer overflows,denial of service (DoS), and session hijacking. These topics will be discussed in later chapters.
Gaining access is known in the hacker world as owning the system.

## Phase 4: Maintaining Access
Once a hacker has gained access, they want to keep that access for future exploitation and
attacks.
Sometimes, hackers harden the system from other hackers or security personnel by
securing their exclusive access with backdoors, rootkits, and Trojans. Once the hacker owns
the system, they can use it as a base to launch additional attacks. In this case, the owned system is sometimes referred to as a zombie system.

## Phase 5: **Covering Tracks**
Once hackers have been able to gain and maintain access, they cover their tracks to avoid
detection by security personnel, to continue to use the owned system, to remove evidence of
hacking, or to avoid legal action. Hackers try to remove all traces of the attack, such as log files or intrusion detection system (IDS) alarms. Examples of activities during this phase of the attack include steganography, the use of tunneling protocols, and altering log files. Steganography and use of tunneling for purposes of hacking will be discussed in later chapters.

## What Is Hacktivism?
Hacktivism refers to hacking for a cause. These hackers usually have a social or political
agenda. Their intent is to send a message through their hacking activity while gaining visibility
for their cause and themselves.
Many of these hackers participate in activities such as defacing websites, creating viruses,
DoS, or other disruptive attacks to gain notoriety for their cause. Hacktivism commonly tar-
gets government agencies, political groups, and any other entities these groups or individuals perceive as “bad” or “wrong.”
### Listing Different Types of Hacker Classes
Hackers can be divided into three groups: white hats, black hats, and grey hats. Ethical hackers usually fall into the white-hat category, but sometimes they’re former grey hats who have become security professionals and who use their skills in an ethical manner.
#### **White hats** 
White Hats are the good guys, the ethical hackers who use their hacking skills for
defensive purposes. White-hat hackers are usually security professionals with knowledge of
hacking and the hacker tool set and who use this knowledge to locate weaknesses and implement countermeasures.
In an ideal world, security professionals would like to have the highest level of security on
all systems; however, sometimes this isn’t possible. Too many security barriers make it diffi-
cult for users to use the system and impede the system’s functionality. Suppose that in order
to gain entry to your office at work, you had to first pass through a guard checkpoint at the
entrance to the parking lot to verify your license plate number, then show a badge as you
entered the building, then use a pass code to gain entry to the elevator, and finally use a key to unlock your office door. You might feel the security checks were too stringent! Any one of
those checks could cause you to be detained and consequently miss an important meeting—
for example, if your car was in the repair shop and you had a rental car, or you forgot your
key or badge to access the building, elevator, or office door.
### Defining the Skills Required to Become an Ethical Hacker
Ethical hackers who stay a step ahead of malicious hackers must be computer systems experts 
who are very knowledgeable about computer programming, networking and operating systems.
In-depth knowledge about highly targeted platforms (such as Windows, Unix, and Linux) is also a requirement. Patience, persistence, and immense perseverance are important qualities that many hackers possess because of the length of time and level of concentration required for most attacks/compromises to pay off.
Most ethical hackers are knowledgeable about security areas and related issues but don’t
necessarily have a strong command of the countermeasure that can prevent attacks. The fol-
lowing chapters of this book will address both the vulnerabilities and the countermeasures to
prevent certain types of attacks.
### What Is Vulnerability Research?
Vulnerability research is the process of discovering vulnerabilities and design weaknesses that could lead to an attack on a system. Several websites and tools exist to aid the ethical hacker in maintaining a current list of vulnerabilities and possible exploits for their systems or networks. It’s essential that a systems administrator keep current on the latest viruses, Trojans,and other common exploits in order to adequately protect their systems and network. Also, by becoming familiar with the newest threats, an administrator can learn how to detect, prevent, and recover from an attack.
### Describing the Ways to Conduct Ethical Hacking
Ethical hacking is usually conducted in a structured and organized manner, usually as part of
a penetration test or security audit. The depth and breadth of the systems and applications to be tested are usually determined by the needs and concerns of the client. Many ethical hackers are members of a tiger team.
### The following steps are a framework for performing a security audit of an organization:
1. Talk to the client, and discuss the needs to be addressed during the testing.
2. Prepare and sign nondisclosure agreement (NDA) documents with the client.
3. Organize an ethical hacking team, and prepare a schedule for testing.
4. Conduct the test.
5. Analyze the results of the testing, and prepare a report.
6. Present the report to the client.
## Creating a Security Evaluation Plan
Many ethical hackers acting in the role of security professionals use their skills to perform
security evaluations or penetration tests. These tests and evaluations have three phases,
generally ordered as follows:
![[Pasted image 20260104143212.png]]
The Preparation phase involves a formal agreement between the ethical hacker and the
organization. This agreement should include the full scope of the test, the types of attacks
(inside or outside) to be used, and the testing types: white, black, or grey box. (These types are defined later, in the section “Testing Types.”)
During the Conduct Security Evaluation phase, the tests are conducted, after which the
tester prepares a formal report of vulnerabilities and other findings. The findings are pre-
sented to the organization in the Conclusion phase along with any recommendations to
improve security.
