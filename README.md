# SOC-Home-Lab
In this project, I designed and deployed a fully functional SOC home lab using open-source tools: Wazuh, ELK Stack, TheHive, and Cortex.

𝐎𝐛𝐣𝐞𝐜𝐭𝐢𝐯𝐞𝐬 :
Ensure proactive monitoring and efficient incident management.
Simulate attack scenarios to test detection and response capabilities.

𝐓𝐡𝐞 𝐖𝐨𝐫𝐤𝐟𝐥𝐨𝐰 :
Wazuh Agents: Collect security data from various systems (Linux and Windows) and send it to the Wazuh Manager.

Wazuh (SIEM): Transfers data via Filebeat to Elasticsearch for storage and analysis.

Kibana: Visualizes data through dashboards with the Wazuh plugin for real-time monitoring.

TheHive (Incident Management Platform): Manages incidents using data from the Wazuh Manager.

Cortex (Automated Analysis Engine): Automates analyses and integrates with VirusTotal for suspicious file evaluation.

SOC Analyst: Utilizes these tools collectively to monitor systems, analyze incidents, and respond effectively to security threats.

𝐓𝐞𝐬𝐭𝐢𝐧𝐠 𝐚𝐧𝐝 𝐑𝐞𝐬𝐮𝐥𝐭𝐬 :
To validate the lab's performance, I executed multiple attack scenarios to ensure the tools could detect, analyze, and respond effectively. Example scenarios include:
+ Malware detection: Identifying malicious files and responding appropriately.
+ SQL injection attack detection: Detecting and mitigating database attack attempts.

![image](https://github.com/user-attachments/assets/15e30627-7f5c-4bfe-8761-1469c1468c74)

https://imgur.com/D56F639
https://imgur.com/vbMg3bO
https://imgur.com/agPwTh2
https://imgur.com/EmlYERM
https://imgur.com/ipReHoC
https://imgur.com/4RLmqtf
https://imgur.com/a6f7l5t
https://imgur.com/DrXIysW
https://imgur.com/omCuA1p
https://imgur.com/TN5x5Y4
https://imgur.com/t5bYZhy
