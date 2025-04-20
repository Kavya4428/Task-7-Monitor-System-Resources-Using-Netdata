# Task-7-Monitor-System-Resources-Using-Netdata
📌 Objective
Install and run Netdata on an EC2 instance using Docker to visualize system and application performance metrics through a real-time web dashboard.

🛠 Tools Used
Netdata – Open-source system monitoring tool
Docker – Containerization platform to run Netdata
Amazon EC2 – Virtual Machine instance on AWS
⚙ Setup Instructions
Step 1: Connect to EC2 via SSH
Step 2: Install Docker (if not already installed)
![Screenshot (148)](https://github.com/user-attachments/assets/20a88a62-3aea-42e2-ad25-e7f8cc06c7f4)

Step 3: Run Netdata Containe
![Screenshot (149)](https://github.com/user-attachments/assets/39dbb9fc-40c8-4c23-8aff-7ea8ba628110)
Step 4: Configure EC2 Security Group
Update your EC2 security group to allow TCP traffic on port 19999:

Type: Custom TCP

Port: 19999

Source: Your IP (for security)

Step 5: Access Netdata Dashboard
Open a browser and visit: http://13.201.132.218:19999
Results:
![Screenshot (150)](https://github.com/user-attachments/assets/6252acb0-d042-442a-a312-a3c285003df9)
![Screenshot (151)](https://github.com/user-attachments/assets/556b096a-0922-4c22-849e-3f1a4569a48b)
![Screenshot (152)](https://github.com/user-attachments/assets/16833e05-aa78-4213-89cf-cb02bd5e98fa)
![Screenshot (154)](https://github.com/user-attachments/assets/5bd461aa-8b8b-4356-9af5-e0abf9549b9a)
![Screenshot (152)](https://github.com/user-attachments/assets/3d27a945-d66f-4f6e-b3be-67bc21473ffc)
![Screenshot (156)](https://github.com/user-attachments/assets/96849bd1-8268-4bc2-b6f8-d8e626998018)
![Screenshot (158)](https://github.com/user-attachments/assets/ab6909d8-5fda-4c28-8f63-239db3252d20)
![netdatalogs](https://github.com/user-attachments/assets/a973a394-9940-4db7-944a-bb50006fde01)








