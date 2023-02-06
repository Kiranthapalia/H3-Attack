# H3-Attack
Week 3 assignments.
## X) Read and summarize
  ### € Costa-Gazcón 2021: Practical Threat Intelligence and Data-Driven Threat Hunting Chapter 4: Mapping the Adversary
    - Mapping the adversary refers to gathering information about potential attackers, their techniques, procedures (TTPs), and the tools that are used by them to carry out attacks.
    - The chapter covers following topics: The ATT&CK Framework, Mapping with ATT&CK and Testing yourself. 
    - The ATTCK Framework is a descriptive model that is employed to categorize and research the actions that a threat actor is capable of taking to establish a foothold and conduct business inside an enterprise environment, a cloud environment, smartphones, or even industrial control systems.
    - The ATTCK Framework's beauty is that it gives the cybersecurity community a common taxonomy to describe adversary activities.
    - There are 14 ATT&CK enterprise's tactics and  they are as follows: Reconnaissance, Initial Access, Execution, Persistence, Privilege Escalation , Defense Evasion ,Credential Access ,Discovery, Lateral Movement ,Collection, Command and Control, Exfiltration, Impact.
    - A framework for comprehending and following cyberattacks is the ATT&CK matrix. It is a matrix of attack strategies and methods arranged in accordance with the stages of the assault life cycle.
    - The matrix gives defenders a thorough understanding of the methods attackers can use to infiltrate systems and enables them to organize their defense and mitigation efforts according to priority. Security professionals and companies frequently use the matrix to enhance their threat intelligence and incident response capacities.
    - This ATT&CK Navigator is an excellent tool for visualizing a threat actor's methodology, the actions of a specific tool, or to create a security exercise. Go to https://mitre-attack.github.io/attack-navigator/enterprise/ to view the Navigator.
    
    In my opinion MITRE ATT&CK framework is one of the most recognized and respected in the cybersecurity industry as they provide a thorough and systematic method of describing and classifying the methods, tactics, and techniques employed by attackers which can aid organizations in better preparing for and defending against cyberattacks.
    
## Y) Write an answer with references  
  ### Define tactic and give an example.
      An ATT&CK technique or sub-"why" technique's is represented by its tactics. 
      The intention behind a move is the tactical objective of the enemy. An opponent might want to obtain credential access. 
      For eg :- financial harm, such as from fraudulent transactions or being demanded to pay money in order to gain access to systems, Data theft or loss, such as the removal of data from the system. 
  ### Define technique and subtechnique, and give an example of each.
      According to the MITRE ATT&CK framework, a technique is a practical method allowing attackers to carry out a tactic's primary objective 
      whereas a sub technique is a particular application or variation of a technique that is more detailed and specific than a technique itself. 
      An example of a technique is Exploitation of Vulnerability. 
      An example of sub-technique is Vulnerability exploitation through client-side exploitation, the use of malicious files or links delivered to users in order to take advantage of software flaws and access their systems. 
  ### Define procedure, and give an example of each. 
      The procedure is the precise way a threat actor utilizes a certain technique or sub-technique. 
      AN example of procedure is initial access procedure where it outlines the steps an attacker follows to get their first look at a target system or network. 
      ANother example MITRE ATT&CK lists how APT19 (G0073) uses a watering hole attack to perform a drive-by compromise (T1189) and gain initial access (TA0001) of forbes.com in 2014.(https://www.cybereason.com/blog/what-is-the-mitre-attck-framework#:~:text=Procedure%3A%20A%20procedure%20is%20the,of%20forbes.com%20in%202014.) 

## Webgoat: A3 Sensitive data exposure.
  - First I had to install the wireshark using the command `$ sudo apt install wireshark -y`
  - AFter the installaion I open the wireshark using the command `sudo wireshark`.
   <img width="440" alt="wireshark" src="https://user-images.githubusercontent.com/102954934/217107317-4b2f1678-c303-4f73-82af-f5349c1476ec.png">
  - I followed the instruction but where i had to press login 1st , go back to wireshark and then choose 'oopback:lo' but for some reason the image down below poped out.
<img width="421" alt="wireshark2" src="https://user-images.githubusercontent.com/102954934/217107648-b21023e0-3e55-4fa3-91e8-279df0ed46c7.png">


## List of sources:
  - https://attack.mitre.org/tactics/enterprise/ [Define tactic and give an example]
  - https://attack.mitre.org/techniques/enterprise/ [Define technique and subtechnique, and give an example of each.]
  - https://www.cybereason.com/blog/what-is-the-mitre-attck-framework#:~:text=Procedure%3A%20A%20procedure%20is%20the,of%20forbes.com%20in%202014. [Define procedure, and give an example of each.]
  - https://attack.mitre.org/groups/G0073/ [Define procedure, and give an example of each.]
  - https://learning.oreilly.com/library/view/practical-threat-intelligence/9781838556372/B13376_04_Final_SK_ePub.xhtml#_idParaDest-73
  - https://www.arbexam.blog/webgoat-a3-sensitive-data-exposure-walkthrough/
  
