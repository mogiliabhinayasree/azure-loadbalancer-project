# Azure Load Balancer Project (Public & Private)

## 📌 Project Overview
This project demonstrates the complete implementation of **Azure Load Balancers** to efficiently distribute traffic across multiple virtual machines.  
Both **Public Load Balancer** and **Private Load Balancer** are configured to show real-world enterprise architecture.

The project covers:
- Resource Group & VNet design
- Subnet segregation
- Web VM and App VM deployment
- NGINX and Tomcat installation
- Public and Private Load Balancer configuration
- Traffic flow and connectivity testing

## 🛠️ Technologies & Services Used
- Microsoft Azure
- Azure Virtual Network (VNet)
- Azure Virtual Machines
- Azure Public Load Balancer
- Azure Private Load Balancer
- NGINX Web Server
- Apache Tomcat
- SSH Connectivity
 
 ## 🏗️ Architecture Overview
- One Virtual Network with multiple subnets
- Web Tier hosted on Web VM (NGINX)
- Application Tier hosted on App VM (Tomcat)
- Public Load Balancer for internet traffic
- Private Load Balancer for internal communication

## 🚀 Step-by-Step Implementation

### 1️⃣ Resource Group Creation
![Resource Group](images/01RGcreation.png)

### 2️⃣ Virtual Network Creation
![VNet Creation](images/02Vnetcreation.png)

### 3️⃣ Subnets Creation
![Subnets](images/03subnetscreation.png)


### 4️⃣ Virtual Machine Creation
![VM Creation](images/04VMcreation.png)


### 5️⃣ Web VM Configuration
![Web VM](images/05WebVM.png)


### 6️⃣ NGINX Installation on Web VM
![Install NGINX](images/06installnginx.png)


### 7️⃣ NGINX Welcome Page Verification
![NGINX Output](images/07nginxwelcomepage.png)


### 8️⃣ Application VM Creation
![App VM Creation](images/08appvmcreation.png)


### 9️⃣ App VM Configuration
![App VM](images/09AppVM.png)


### 🔟 Tomcat Installation on App VM
![Install Tomcat](images/10installtomcat.png)


## 🌐 Public Load Balancer Configuration

### 1️⃣1️⃣ Public Load Balancer Creation
![Public LB Creation](images/11LBcreation.png)


### 1️⃣2️⃣ Public Load Balancer Frontend IP
![Public LB](images/12publicLB.png)


### 1️⃣3️⃣ Backend Pool Configuration
![Public LB Backend Pool](images/13publicLBbackendpool.png)


### 1️⃣4️⃣ Health Probe Configuration
![Public LB Health Probe](images/14PublicLBhealthprobe.png)


### 1️⃣5️⃣ Load Balancing Rules
![Public LB Rules](images/15publicLBrules.png)


### 1️⃣6️⃣ Public Load Balancer Overview
![Public LB Overview](images/16publicLBoverview.png)


## 🔐 Private Load Balancer Configuration

### 1️⃣7️⃣ Private Load Balancer Creation
![Private LB](images/17privateLB.png)


### 1️⃣8️⃣ Private LB Frontend IP
![Private LB Frontend IP](images/18privateLBfrontIP.png)


### 1️⃣9️⃣ Backend Pool Configuration
![Private LB Backend Pool](images/19privateLBbackendpool.png)


### 2️⃣0️⃣ Health Probe Configuration
![Private LB Health Probe](images/20privateLBhealthprobes.png)


### 2️⃣1️⃣ Load Balancing Rules
![Private LB Rules](images/21privateLBrules.png)


### 2️⃣2️⃣ Private Load Balancer Overview
![Private LB Overview](images/22privateLBoverview.png)


## 🔗 Connectivity & Testing

### 2️⃣3️⃣ SSH Connectivity
![SSH Connection](images/23connectionssh.png)


### 2️⃣4️⃣ Connectivity Testing
![Connectivity Testing](images/24connectivitytesting.png)


## ✅ Project Outcome
- Successfully deployed Web and Application tiers
- Public Load Balancer distributes internet traffic efficiently
- Private Load Balancer enables secure internal communication
- Health probes ensure high availability
- Application is accessible and fault-tolerant


## 🎯 Conclusion
This project provides hands-on experience with **Azure Load Balancer architecture** and demonstrates how traffic distribution, high availability, and secure internal communication are achieved in real-world cloud environments.

It reflects practical cloud engineering skills including networking, VM management, load balancing, and troubleshooting, making it suitable for **real-time enterprise use cases**.


## 🔗 Author
**Abhinayasree**  
