
# learn-build-
# Week - 1 fundamentals of azure 

# Week -2 azure virtual machine spin out, networking features

# Week-3 Azure firewall, network security group, network traffic and sentinel

# Week-4 Wazuh deployment in ubuntu azure machine and adding azure virtual machine as agents

# fundamantals of azure 
![c7bae5ec-f078-4324-a4c9-99e90eaad020](https://github.com/Madzx007/learn-build-/assets/140810195/7baf4d8c-e14b-4769-8448-738c9beb3530)

# coumpute serivce
The hosting model for the computing resources that power apps is referred to as a compute service4. "Compute" refers to ideas and items associated with software computation in cloud computing. Processing power, memory, networking, storage, and other resources necessary for each program's computational success are collectively referred to by this general term2.

Cloud providers such as Azure¹⁴ and Amazon Web capabilities (AWS) provide a variety of computational capabilities. Here are a few instances from AWS:

- Instances (virtual machines): Amazon Elastic computation Cloud (Amazon EC2) offers scalable and secure computation resources (virtual servers) in the cloud1.
*Containers*: To run containers, use Amazon Elastic Container Service (Amazon ECS), which provides a very dependable, scalable, and safe solution1. 
*Serverless*: You can run code without a server using AWS Lambda.
![208a8ee6-dea2-4580-a27f-b28a0e7b1f02](https://github.com/Madzx007/learn-build-/assets/140810195/b7d41613-d1de-4019-8281-e878e144062f)

# networking serivce 
Applications that function at the network application layer are known as network services. They provide users with access to data and applications across a network2. Usually, servers6 are used to run these services. Examples of network services include the following:

*Online gaming* - *Printing* - *File server* - *Directory services* - *Email* - *File sharing* - *Instant messaging* - *Video on demand* - *Video telephony*¹

Some categories of network services consist of:

- *Branch office and campus connectivity* - *Internet and cloud connectivity* - *Secure cloud-connectivity services* - *Virtual network services* 

Additionally, certain network designs and services exist, like:

SASE (Secure Access Service Edge): This network design blends cloud-native security features with software-defined wide-area network (SD-WAN) capabilities. Users can access protected applications from any location with its help.
![c4a6b52f-331e-4946-8702-b7c0830e5921](https://github.com/Madzx007/learn-build-/assets/140810195/b101a538-0a41-4516-89b4-6a46a66fea3b)
# Inbounded and outbounded rule creations
Rules are designed to regulate traffic to and from your computer, both inbound and outgoing. 

If you are hosting a web server on your computer, for instance, you can use *inbound rules* to enable external connections to your system1. 

Certain programs are allowed to access the internet while others are blocked by *outbound rules*. Outbound policies by default permit all traffic on all protocols2.

By selecting the New rule option from the pick list under Inbound Rules or Outbound Rules, respectively, you can create new inbound and outbound rules. Either a bespoke rule or a pre-established protocol can be used. 

You can use the following steps, for example, to establish an inbound rule in Windows Defender:1. Open the Group Policy Management Console to Windows Defender Firewall with Advanced Security.
![48902300-c052-470a-80f8-9ccb759b04ef](https://github.com/Madzx007/learn-build-/assets/140810195/2e618b82-a128-49fa-9641-b25785018c43)
# IAM and security monitering
The protection of an organization's data and resources is facilitated by Identity and Access Management (IAM), a critical component of contemporary IT1. It controls access to ensure that the proper persons, such as hackers, are prevented from entering and that the correct people can carry out their duties1. Verified entities have secure access to company resources, including databases, emails, data, and applications, thanks to IAM1.

IAM consists of two components: access management and identity management.A login attempt is verified by identity management using an identity management database, which is a running list of all authorized users1. As individuals join or leave the company, their responsibilities and projects change, and the organization's scope changes, this data has to be updated on a regular basis1.

Monitoring security is crucial to preserving the dependability, accessibility, and efficiency of IAM.
![5ad71541-5e9c-4382-9e3b-f892de986957](https://github.com/Madzx007/learn-build-/assets/140810195/971eb4b2-9e9d-4560-9a3c-e1cab7885c87)
![6e7d611d-fa51-473d-8871-cede4094b194](https://github.com/Madzx007/learn-build-/assets/140810195/b44930fc-807c-4a5c-a428-0a5648c94a14)
# Role base access management
Role-based access control (RBAC)* is a security feature that limits authorized users' access to a system according to their position within an organization. It is a method for putting in place either discretionary access control (DAC) or mandatory access control (MAC). ². RBAC allows access based on a user's requirements specific to their role. *. 

Built on top of Azure Resource Manager, *Azure role-based access control (Azure RBAC)* in Azure offers fine-grained access management to Azure resources. ³. You can control who can access Azure resources, what they can do with them, and which locations they can reach with its assistance ¹. Any user, group, service principal, or managed identity wanting access to Azure resources can have a role assigned to them.
![6e8828ba-3464-4ecb-9754-2c4aa540145b](https://github.com/Madzx007/learn-build-/assets/140810195/5d8dae97-ad4f-4eae-8605-4bc7f6eb329d)
# SIEM tool
![24fd2116-d4b2-458d-a952-1f614d78db13](https://github.com/Madzx007/learn-build-/assets/140810195/7a8192f8-48b2-4ecf-a41e-ed9a23d71492)
splunk
![451a6bd8-0779-4d60-829c-e356f7f4f4c5](https://github.com/Madzx007/learn-build-/assets/140810195/254aaffd-cce8-4848-bd1b-5fc0720b4910)

ibm Qradar

![image](https://github.com/Madzx007/learn-build-/assets/140810195/c1bb69d8-8a41-4114-a620-446e82b6fa84)

Arcsight

![image](https://github.com/Madzx007/learn-build-/assets/140810195/bcc2e0e5-ca5b-442e-a077-81c88f1aced7)

wazuh

![image](https://github.com/Madzx007/learn-build-/assets/140810195/2ecc3462-4cb2-4550-902e-f7b8aca7e581)

# AZURE SENTINEL
Azure Sentinel is a cloud-based service that delivers security orchestration, automation, and response (SOAR) capabilities as well as security information and event management (SIEM). It assists businesses in detecting, investigating, and responding to threats across their IT environment 123.

Azure Sentinel collects and analyzes data from a variety of sources, including Microsoft solutions, Azure services, and third-party apps, utilizing artificial intelligence and threat intelligence. Users can also produce interactive reports, correlate alerts into incidents, automate and orchestrate routine processes, and search for suspicious behaviors at scale 145.

Azure Sentinel is a scalable, cloud-native solution that requires no infrastructure or upkeep. It can be rapidly and easily installed, and it can be connected with other Azure services like Log Analytics and Logic Apps. The Azure Sentinel also supports Azure Lighthouse, which enables service providers to manage their customers' security from their own tenant ¹⁵.

If you want to learn more about Azure Sentinel, you can visit the official website ⁵ or check out some of the online courses and tutorials ¹²³. You can also try Azure Sentinel for free for the first 31 days.
![image](https://github.com/Madzx007/learn-build-/assets/140810195/f1fcbd21-1b72-406f-93db-89bf29ce965c)

# AlERt sYstem 
An alert system alerts people to potential or imminent threats such as natural disasters, terrorist attacks, or health emergencies. To deliver urgent messages and instructions to the public, alert systems can use various channels such as broadcast media, mobile devices, sirens, or loudspeakers.

Depending on their needs and capabilities, different countries may have different alert systems. The United Kingdom, for example, recently launched the Emergency Alerts service, which can send alerts to compatible mobile phones and tablets in a specific area 1. The Emergency Alert System (EAS) in the United States can interrupt regular programming on television and radio stations to broadcast emergency information 3.

During an emergency, alert systems are intended to keep people safe and informed. They can provide valuable informations can also send alerts to mobile devices, as well as the Emergency Alert System, which can broadcast alerts on radio and television ³ .

Alert systems are important tools for enhancing public safety and preparedness, especially in times of crisis. They can help save lives, reduce damages, and coordinate responses. However, alert systems also have some challenges, such as ensuring accuracy, timeliness, accessibility, and reliability of the messages, as well as avoiding false alarms, panic, or confusion among the recipients  . Therefore, alert systems need to be carefully designed, tested, and maintained, and follow best practices and standards.
# KQL quary 
KQL is a simple text-based query language used for filtering data. It is used to filter documents where a value for a field exists, matches a given value, or is within a given range. KQL only filters data, and has no role in aggregating, transforming, or sorting data. You can use range syntax for string values, IP addresses, and timestamps. For more information on how to use KQL, please refer to the official documentation provided by *Elastic* ¹.
# mitre attack framework
The *MITRE ATTACK®* framework is a globally-accessible knowledge base of adversary tactics and techniques based on real-world observations ¹. It is used as a foundation for the development of specific threat models and methodologies in the private sector, in government, and in the cybersecurity product and service community ¹. The framework is curated and tracks cyber adversary tactics and techniques used by threat actors across the entire attack lifecycle ². It is intended to be used as a tool to strengthen an organization's security posture ².
![image](https://github.com/Madzx007/learn-build-/assets/140810195/56a30495-23d7-4931-9c6f-b9253fa88816)

# real time tracking on threats
Real time tracking on threats is a process of monitoring and analyzing the cyberattacks that are happening around the world in real time. It can help to identify the sources, targets, types, and impacts of these attacks, as well as to provide countermeasures and solutions.

There are several online tools that offer real time tracking on threats, such as:

 *Radware Live Threat Map*: This tool shows the web attackers, DDoS attackers, intruders, scanners, and anonymizers that are attacking different countries and regions. It also provides statistics on the top attackers, attacked, application violations, and scanned ports ¹.
- *Kaspersky Cyberthreat Real-Time Map*: This tool displays the cyberattacks that are detected by Kaspersky's network of sensors and products. It also provides statistics on the attack types, targets, sources, and rankings of countries and regions ²³.
- *Check Point Live Cyber Threat Map*: This tool visualizes the cyberattacks that are blocked by Check Point's security solutions. It also provides statistics on the attack types, targets, sources, and rankings of countries and regions ⁴.

These tools can help you to stay informed and aware of the cyberthreats that are affecting the world. However, they are not a substitute for having a robust and comprehensive cybersecurity strategy and protection.

![image](https://github.com/Madzx007/learn-build-/assets/140810195/5831d05c-ee16-4d28-862f-a9e00542e88c)
![image](https://github.com/Madzx007/learn-build-/assets/140810195/958c482b-de5b-4ff1-9638-03d0927b44ad)

# real time protection 
Real-time protection is a security feature that *prevents cyberattacks* by scanning your device for malware and other threats in the background ⁵. It is an important component of any good antivirus program, as it can help you avoid getting infected by malicious software.

However, some users may want to disable real-time protection for various reasons, such as improving performance, installing certain programs, or testing their own security. If you are one of them, you should be aware of the risks and consequences of turning off real-time protection. You will be more vulnerable to cyberattacks and may compromise your data and privacy.

If you still want to disable real-time protection, you can follow the steps shown in these videos ¹²³. They will guide you through different methods of turning off real-time protection on Windows 10, such as using the settings, the registry editor, or the group policy editor. Please note that these methods may not work for all versions of Windows 10, and you may need administrative privileges to perform them.
![image](https://github.com/Madzx007/learn-build-/assets/140810195/b9e48cb0-41ba-42b0-8b40-60ea7bdf5bbd)
![image](https://github.com/Madzx007/learn-build-/assets/140810195/e6446cdd-10ba-494e-96ed-a370ef702ed3)

# BLUE TEAM
In cybersecurity, a *blue team* is a group of security professionals responsible for *defending* an organization's information systems by maintaining its security posture against a group of mock attackers ¹⁵. The blue team is expected to detect, oppose, and weaken the red team, which is made up of offensive security experts who try to attack an organization's cybersecurity defenses ¹. The blue team is typically composed of incident response consultants who provide guidance to the IT security team on where to make improvements to stop sophisticated types of cyberattacks and threats.

# attack stmulation
Attack simulation is a technique used to simulate cyberattacks and breaches in an organization. It can help identify potential vulnerabilities in security systems and test out the detection and prevention capabilities ¹². 

Microsoft Defender for Office 365 Plan 2 provides an *Attack simulation training* feature that allows you to run realistic attack scenarios in your organization. These simulated attacks can help you identify and find vulnerable users before a real attack impacts your bottom line ¹. 

There are also other *Breach and Attack Simulation (BAS) tools* available in the market that can help you gain a deeper understanding of security posture vulnerabilities by automating testing of threat vectors such as external and insider, lateral movement, and data exfiltration. These tools can validate an organization's security posture by testing its ability to detect a portfolio of simulated attacks performed by SaaS platforms, software agents, and virtual machines. They can also generate detailed reports about security gaps and prioritize remediation efforts based on the risk level .
k








