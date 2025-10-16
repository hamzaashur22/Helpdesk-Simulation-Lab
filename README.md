# Helpdesk-Simulation-Lab 
Simulated real-world IT helpdesk workflow. Diagnosed and resolved high CPU usage on a Linux system, documented findings in osTicket, and demonstrated full incident lifecycle management. 

## Overview
This project simulates a real helpdesk environment from start to finish. Within the lab I cover system monitoring, incident troubleshooting, ticket documentation, and resolution within osTicket, while also demonstrating proficiency in virtual machine management and using the full LAMP stack deployment. This lab covers various skills such as Linux system administration, web server configuration, and end-to-end application setup, reflecting my solid foundation in both support operations and backend infrastructure management. 

## Process & Screenshots

### 1. VM Setup
 
  *Set up a virtual machine network and an ubuntu server to work on. Installed system monitoring tools (`htop`, `sysstat`) on the Ubuntu VM.*  
  

   <img width="1910" height="1074" alt="image" src="https://github.com/user-attachments/assets/e84feadb-e913-44bf-8112-2031949cf0be" /> 

 ### 2. osTicket Setup

*Installed and configured osTicket using the LAMP stack (Linux, Apache2, MariaDB, PHP 8.2). Verified access to the web installer and completed setup successfully.* 

 
<img width="1719" height="900" alt="image" src="https://github.com/user-attachments/assets/f6212779-9192-4ee9-97a9-fbca3e489f41" /> <img width="951" height="746" alt="image" src="https://github.com/user-attachments/assets/875f9114-b142-4f69-bbf5-93ef6c7cdeac" />


### 2. Baseline Monitoring

*Verified system resource usage under normal load using `htop`. (quick test before we begin the lab)* 

<img width="1711" height="896" alt="image" src="https://github.com/user-attachments/assets/a986bfd3-7f7b-4806-aad8-8191ee509eb0" /> 

### 3. High CPU Simulation 

*Created a CPU spike using `yes > /dev/null &` on the "client" device to create a 99% CPU load scenario.*

<img width="1710" height="918" alt="image" src="https://github.com/user-attachments/assets/31c60dfc-f05f-4cda-9497-e9f4f87e9377" /> <img width="1721" height="922" alt="image" src="https://github.com/user-attachments/assets/a335f802-c11b-4dd7-8623-503ff5411aed" />

### 7. User Ticket Submission

*Simulated a client report of system lag through osTicket portal.*

<img width="1651" height="938" alt="image" src="https://github.com/user-attachments/assets/7c0a6e58-5d03-41b0-812e-e3738fb1d9f1" />  

### 8. Technician Response

*Diagnosed CPU saturation via `htop`, terminated process, restored and verified performance. Resolved ticket.*  

<img width="1720" height="940" alt="image" src="https://github.com/user-attachments/assets/3461eedb-3b06-4e29-a405-261d51953644" />  <img width="1704" height="914" alt="image" src="https://github.com/user-attachments/assets/82b820c8-2224-4d49-ac1b-097db03b97d7" /> <img width="1646" height="939" alt="image" src="https://github.com/user-attachments/assets/6aa6fc4c-3030-48a0-9766-a9dd8689bff1" />  


### 9. Internal Notes
 
*Documented incident summary, tools used, and resolution for escalation. 

<img width="1642" height="963" alt="image" src="https://github.com/user-attachments/assets/d4d5a0ea-2a2d-4c7f-b00d-2c3db51aa8ad" />  

## Key Takeaways
- Practiced real-time **monitoring and troubleshooting** in Linux.  
- Demonstrated **incident documentation and escalation** using osTicket.  
- Strengthened **LAMP stack deployment** and system diagnostic skills.  
- Reinforced professional **helpdesk communication and workflow**

## Author
**Hamze Ashur**  
Cyber Defense & Analysis Student | Aspiring IT Support & Security Professional  
 [GitHub](https://github.com/hamzaashur22)













 


