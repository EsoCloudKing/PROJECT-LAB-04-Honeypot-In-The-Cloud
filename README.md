# DEPLOYING A MULTI HONEYPOT PLATFORM IN THE CLOUD USING T-POT

## Overview

A multi honeypot in the cloud is a security setup that mimics vulnerable systems in cloud environments to attract cyber attackers. This project/Lab involves deploying and configuring a cloud-based honeypot to observe and analyze attackers behavior. By logging their activities, it provides valuable insights into tactics, techniques, and procedures (TTPs) used by attackers. Leveraging platforms like Azure, AWS, GCP, the lab will simulate real-world scenarios, enhancing threat detection and strengthening cloud defenses.

schematic image
 
 ## Objective

- Deploy and configure the T-Pot multi-honeypot platform in a cloud environment.

- Simulate realistic attack scenarios by attracting and logging malicious activities.

- Gain in-depth insights into attacker tactics, techniques, and procedures (TTPs).

- Enable centralized monitoring and analysis of multiple honeypots using T-Pot’s unified interface.

- Test and evaluate the scalability and performance of honeypot deployment in cloud environments.

- Strengthen incident response capabilities by analyzing real-time threat intelligence.

- Develop actionable recommendations to enhance cloud security posture based on captured data.

## Achievements

- Deployed T-Pot on Azure Cloud to fortify security measures and enhance capabilities for advanced threat detection and analysis.
- Analyzed and monitored honeypot activity to enable rapid identification and response to emerging cyber threats.
- Enhanced understanding of cloud-specific and cyber security challenges and honeypot adaptability.
- Contributed to better threat intelligence by integrating findings into broader security measures.

## Tools Used For this Project
  - __Draw.io:__ For diagram mapping
  - __Azure Vm(Ubuntu):__ Honeypot server
  - __PuTTy__  For remote access to ubuntu server
  - __T-Pot__ Multi-Honeypot Integration platform that integrates multiple honeypot (like Dionaea, Cowrie, and Honeytrap)services into a single, unified solution. It includes an intuitive web-based dashboard powered by ELK Stack (Elasticsearch, Logstash, Kibana) for real-time data visualization and analytics
  - __VirusTotal__ For threat intelligence.

## LAB STEPS

**1: Set up Honeypot VM**

- In Azure, an Ubuntu server with the necessary storage and RAM specifications was provisioned and configured. The Network Security Group (NSG) was set up to allow all ports and permit various types of traffic, including HTTPS, HTTP, SSH, RDP, and ICMPv4.

  ![VM2](https://github.com/user-attachments/assets/b9245ad6-8823-4de8-88f2-85e3783d3aac)


**2: Installation of T-Pot**

- PuTTY was utilized to access the Ubuntu server via SSH, to facilite the installation of (T-Pot).

- After accessing the Ubuntu server using PuTTY, the server was updated, upgraded, restarted, the Git repository was cloned, and T-Pot (Hive version) was installed. All these tasks were performed via the Linux command line.

![putty upload](https://github.com/user-attachments/assets/f0f1ca34-3458-468c-b52a-1eaca4afb2a1)  ![putty 4](https://github.com/user-attachments/assets/426ba293-954a-4345-a125-c088211e887b)

**2: Login to T-Pot web interface**

- After completing all the necessary installations, the Azure environment was allowed to run for several hours. The T-Pot web interface was accessed to observe and analyze attacker activities and attack patterns.

- Various tools within T-Pot, such as Kibana, the Attack Map, and SpiderFoot, were utilized and explored to monitor and analyze threats as well as indicators of compromise as seen in the following images below;

  **T-Pot Homepage** ![t-pot homepage 2](https://github.com/user-attachments/assets/57402452-8d33-4dc3-a231-3a8ec10aa0c8)

  **Kibanna for real-time dashboards for monitoring attacker activity, trends, and behaviors across multiple honeypots** ![kibana 22](https://github.com/user-attachments/assets/8032be63-51ba-4a19-80be-e584eedbd2f0)

  **IP geolocation attack map displaying hits and activities from various threat actors.** ![attack map 22](https://github.com/user-attachments/assets/537a23d7-875c-4a9f-be5f-091e597aa0db)

 **Virustotal to Analyze a suspicious IP address with significant activity targeting the honeypot server. Leveraged VirusTotal to study its reputation, associated threats, and malicious behavior patterns, gaining deeper insights into the IP’s role in cyberattacks** ![virustotal 3](https://github.com/user-attachments/assets/04b7ee5a-48a3-45d4-9f29-7fda3f824817)

  ## CONCLUSION

Successfully deployed a multi-honeypot platform in the cloud using T-Pot, demonstrating expertise in cloud-based security solutions and threat analysis. This project provided hands-on experience in provisioning and configuring Azure virtual machines, managing network security groups, and deploying Ubuntu servers. Leveraged tools such as PuTTY for remote server access, Git for repository management, and various integrated T-Pot tools like Kibana, Attack Map, and SpiderFoot for real-time monitoring and analysis of cyber threats. 

Gained practical skills in identifying and analyzing malicious activities, utilizing VirusTotal for threat intelligence, and interpreting indicators of compromise (IOCs).
 
This project/Lab showcased my ability to implement advanced threat detection mechanisms in a cloud environment, contributing to a deeper understanding of attacker behavior and improving incident response strategies."




 




  
