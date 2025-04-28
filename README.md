# LetsDefend-SOC-Fundamentals-Training
Welcome to the world of SOC Fundamentals! Get ready to dive into the dynamic realm of Security Operations Centers (SOCs). 
In this blog, we’ll explore the structure, operations, and essential tools that empower SOC Analysts in their battle against cyber threats. 
Join me on this interactive journey as we uncover quick tips, real-world examples, and thought-provoking quizzes to enhance your skills and propel your career in cyber security.
Let’s unlock the power of SOC Fundamentals together and stay one step ahead in the ever-evolving threat landscape.

Link: https://app.letsdefend.io/training/lessons/soc-fundamentals

![image](https://github.com/user-attachments/assets/4ee9a606-b2ef-4c6c-85a9-b54ef8c5381f)

 Introduction to SOC
Welcome to the first step of your career as a SOC analyst. In this first lesson, the structure of SOC and SOC tools will be explained.
The lesson will also discuss why a SOC analyst needs these SOC (Security Operations Center) tools and how to use them effectively.


**What will you learn in this course?**

•	The structure of a SOC

•	Operation of a SOC

•	SOC Tools/Products

•	How a SOC Analyst should use his tools

•	Common mistakes made by SOC Analysts


If you need a playlist to accompany you on your learning journey, check out our SOC Analyst Spotify playlist.

# SOC Types and Roles

What is a SOC?
A Security Operation Center (SOC) is a facility where the information security team continuously monitors and analyzes the security of an organization. 
The primary purpose of the SOC team is to detect, analyze, and respond to cybersecurity incidents using technology, people, and processes.


**Types of SOC Models**

Depending on your security needs and budget, there are several types of SOCs:


![image](https://github.com/user-attachments/assets/c0c4b4f2-1401-460f-9845-f030b1fc6559)

 



1) In-house SOC:  This team is formed when an organization builds its cybersecurity team. Organizations considering an internal SOC should have a budget to support its continuity.

2) Virtual SOC:   This type of SOC team does not have a permanent facility and often works remotely in various locations.

3) Co-Managed SOC:  The Co-Managed SOC consists of internal SOC staff working with an external Managed Security Service Provider (MSSP). Coordination is key in this type of model.

4) Command SOC:  This SOC team oversees smaller SOCs across a large region. Organizations using this model include large telecommunications providers and defense agencies.

**People, Process, and Technology**

Building a successful SOC requires serious coordination. Most importantly, there should be a strong relationship between people, processes, and technology.
Simply put, we will discuss the people, processes, and technologies required for SOC.

**People :-**  A strong SOC team requires highly trained personnel who are familiar with security alerts and attack scenarios. Because attack types are constantly changing, you need team members who can easily adapt to new attack types and are willing to conduct research.

**Processes :-**  To further develop your SOC structure, you need to align it with many different types of security requirements, such as NIST, PCI, and HIPAA. All processes require extreme standardization of actions to ensure nothing is left out.

**Technology :-**  The team needs to have different products for many tasks, such as penetration testing, detection, prevention, and analysis, and they need to follow the market and technology closely to find the best solution for the organization. Sometimes the best product on the market may not be the best product for your team. Remember to consider other factors such as the organization's budget.


# SOC Roles
**1)SOC Analyst :**  This role can be categorized as Level 1, 2, and 3 according to the SOC structure. A security analyst classifies the alert, looks for the cause, and advises on remediation.

**2)Incident Responder :**  An Incident Response Officer is an individual responsible for threat detection. This role performs the initial assessment of security breaches.

**3)Threat Hunter :**  A Threat Hunter is a cybersecurity professional who proactively seeks out and investigates potential threats and vulnerabilities within an organization's network or system. They use a combination of manual and automated techniques to detect, isolate, and mitigate advanced persistent threats (APTs) and other sophisticated attacks that may evade traditional security measures. Threat hunters typically have a deep understanding of the organization's IT infrastructure and security posture, as well as knowledge of emerging threats and attack tactics. They aim to find and eliminate threats before they can damage or disrupt the business.

**4)Security Engineer :**  Security engineers are responsible for maintaining the security infrastructure of Security Information and Event Management (SIEM) solutions and security operations center (SOC) products. For example, a security engineer builds the connection between SIEM and Security Orchestration, Automation, and Response (SOAR) products.

**5)SOC Manager :**  A SOC manager takes on management responsibilities such as budgeting, strategizing, managing staff, and coordinating operations. They deal with operational rather than technical issues.

# SOC Analyst and Their Responsibilities

In this section, we will discuss what a SOC Analyst is, where they fit into the SOC team, and the general responsibilities of the role. It is important to review these sections carefully before learning about the technical side of the role. In this way, aspiring SOC Analyst candidates can get an idea of what their future career might look like. A SOC Analyst is the first person to investigate threats to a system. If the situation demands it, they escalate incidents to their supervisors so they can mitigate threats. The SOC Analyst plays an important role on the SOC team because they are the first person to respond to a threat.

Throughout the day, a SOC analyst typically reviews alerts in the SIEM and determines which ones are real threats. To reach a conclusion, they use various security and protection products such as Endpoint Detection and Response (EDR), Log Management, and SOAR. We will explain in detail why and how these products are used later in the training program.

To be a successful SOC analyst who is not dependent on security products and can correctly analyze SIEM alerts, you must have the following skills and abilities.

**Operating Systems :-**
To determine what is abnormal in a system, you first need to know what is accepted as normal. For example, there are many services within the Windows operating system, and it is difficult to know which ones are suspicious without knowing which ones are or could be considered normal Windows services. Therefore, you should be familiar with how Windows/Linux operating systems work.

**Network :-**
First and foremost, in this role, you will be dealing with a lot of malicious IPs and URLs, so you need to confirm that there are no devices on the network trying to connect to those addresses. Once you accomplish that, it will set the direction of the analysis. This step is a bit more complicated because you may have to find a potential data leak on the network. To perform all of these functions, you need to understand the basics of networking.

**Malware Analysis :-**
When dealing with most threats, you are likely to encounter some type of malicious software. To understand the real purpose of these malicious programs (they sometimes display different behaviors to fool analysts), you need to have malware analysis skills. It is important to at least determine what the command and control center of the malicious file is and whether or not there is a device communicating with that address.

# SIEM and Analyst Relationship
**What is SIEM ?**
SIEM is a security solution that combines security information and event management, which involves real-time logging of events in an environment. The ultimate purpose of event logging is to detect security threats. Overall, SIEM products have a lot of features. The ones that interest us most as SOC analysts are those that collect and filter data and provide alerts for suspicious events.

**Example alert:** If someone on a Windows operating system tries to enter 20 incorrect passwords in 10 seconds, this is suspicious activity. It is unlikely that someone who has forgotten their password would try to re-enter it that many times in such a short period of time. So we create a SIEM rule/filter to detect such activity that exceeds the threshold. Based on this SIEM rule, an alert will be generated when such a situation occurs.



 ![image](https://github.com/user-attachments/assets/72a6ccb2-50b7-4def-bf9a-355e267002fe)




Some popular SIEM solutions: IBM QRadar, ArcSight ESM, FortiSIEM, Splunk, etc. To get a better picture, you can visit the “Monitoring” page on LetsDefend.

![image](https://github.com/user-attachments/assets/1a1eb494-6724-4ee3-b7f3-d2a62850c270)

You can view newly created alerts in the "Main Channel" and think of this channel as a shared channel. Your teammates are not visible in this simulation, but in a real work scenario, your teammates will be able to see this panel. After you select the alert you want to work on, click the Take Ownership button in the Action area to take ownership of the alert and direct it to the Investigation Channel. This way, your teammates can see which alert you are actively working on. At the same time, this will help them see which alerts you are already working on so they can select other alerts. This way, your team can quickly review all alerts.

When you click on the alert, you can see the details of the alert. This allows you to gather the information (hostname, IP address, file hash information, etc.) required to investigate.


# Log Management
As a SOC Analyst, you will perform a lot of log analysis. For this reason, it is important to be familiar with "Log Management" systems/solutions. It doesn't matter what product you use, it's about knowing what to look for and where to look for it. The remainder of this lesson discusses how "Log Management" solutions can be used effectively by SOC analysts.

**What is Log Management ?**
As the name implies, Log Management provides access to all logs in an environment (web logs, OS logs, firewall, proxy, EDR, etc.) and allows you to manage them in one place. This increases efficiency and saves time.

If you can't access the logs from one place, then the same request (e.g., the goal is to determine all users on letsdefend.io) would have to be sent to different devices. This would increase your margin for error and the amount of time you would need to spend.

If you go to the “Log Management” page in LetsDefend, you will see various log sources such as Proxy, Exchange, and Firewall listed as “Type”. This means that all these log sources have been collected in one place and log output from sources like Proxy, FW, etc. can be seen with just one query.

![image](https://github.com/user-attachments/assets/e24c06e7-5cc7-4578-90f3-42db98fb8f4c)




**Purpose of Log Management**

SOC analysts typically rely on Log Management to determine if there is any communication with a particular address and to view the details of that communication. Let's say you came across a piece of malware and after running it, you found that it was communicating with and executing commands from the "letsdefend.io" address. In this situation, the command&control center is "letsdefend.io", you can search for "letsdefend.io" in your company's log management to see if any devices have attempted to communicate with the command&control center.

This leaves us with a second situation: You see a SIEM alert indicating that a LetsDefendHost device on your network is leaking data to IP address 122[.]194[.]229[.]59. You have conducted an investigation, isolated the device from the network, performed the necessary processes, and now you are in control. But there's still something you haven't addressed: are there any other devices sending data to the suspicious IP address (122[.]194[.]229[.]59)? The alert may have only included LetsDefendHost, but you should still search for the suspicious address in Log Management to see if there is anything the system may not have detected and try to find any connections.

# EDR - Endpoint Detection and Response
A SOC analyst must spend a significant amount of time using EDR when performing analysis on an endpoint device. The following sections discuss why EDR is beneficial to SOC analysts and how to use it effectively.

**What is EDR ?**
Endpoint Detection and Response (EDR), also known as Endpoint Threat Detection and Response (ETDR), is an integrated endpoint security solution that combines continuous, real-time monitoring and collection of endpoint data with rules-based automated response and analysis capabilities. (Definition source: mcafee.com)

Analysis with EDR
Some EDR solutions commonly used in the workplace: CarbonBlack, SentinelOne, and FireEye HX.

To understand what you can do with EDR as an analyst, let's take a look at "Endpoint Security" on LetsDefend.

![image](https://github.com/user-attachments/assets/a12fd490-b29a-423e-8b63-0c52aa5eda64)


As you can see in the image, the accessible endpoint devices are listed on the left. You can search for endpoints in the search bar, or if there is an IOC (an IP address, file hash, process name, etc.), we can perform a search across all hosts.

The right side displays general information about the device and shows sections such as Browser History, Network Connections, and Process List.

![image](https://github.com/user-attachments/assets/5589b47b-d726-43e2-ba24-1f505660d68b)



![image](https://github.com/user-attachments/assets/e78d0a07-3c9b-48b1-84d3-317092bd711c)

