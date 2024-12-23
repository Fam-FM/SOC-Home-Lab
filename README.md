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
![image](https://github.com/user-attachments/assets/a9e2744a-8b00-480d-993b-122344f28957)
![image](https://github.com/user-attachments/assets/c97bcfa6-622c-49c8-b5c6-8096e1aef006)
![image](https://github.com/user-attachments/assets/8afa37ad-568a-4864-909f-d0b9e29457c8)
![image](https://github.com/user-attachments/assets/9afcad2f-2609-4e61-9595-8ee0357a7e49)
![image](https://github.com/user-attachments/assets/da0b78e6-571f-4041-85a2-867f0cb2488e)
![image](https://github.com/user-attachments/assets/6eecd4d8-2162-4ca4-95ab-d5a2b6453636)
![image](https://github.com/user-attachments/assets/ea8b9765-c15e-486f-8166-c660b33ed857)
![image](https://github.com/user-attachments/assets/17465cc2-8622-454b-9fe5-38dc1bc959fe)
![image](https://github.com/user-attachments/assets/b48cc1fc-91b4-4a0f-bc73-d984e6cb0311)
![image](https://github.com/user-attachments/assets/1918f302-d29c-40b4-8afa-ada9a78c49a2)
