# 🚀 LAMP Stack Setup

## 📖 Overview
This guide provides step-by-step instructions for setting up a **LAMP (Linux, Apache, MySQL, PHP) stack** on an **AWS EC2 Ubuntu instance**. Each section includes commands, configurations, and verification steps with images.

---

## 🛠️ Part 1: Setting Up LAMP Stack

### 🔹 IAM User and Group Setup
- Created an **IAM user**.
- Created a **user group** and granted **admin access** permissions.
- Added the **IAM user** to the group.

📸 **Screenshot:**  
![User group and permission creation](images/image-01.png)

---

### 🔹 EC2 Instance Creation
- Launched an **EC2 instance** using **Ubuntu**.
- Created a **key pair** during instance setup.

📸 **Screenshot:**  
![Key pair creation](images/image-02.png)

- Created a **security group** and configured necessary rules.

📸 **Screenshots:**  
![Security group creation](images/image-03.png)  
![Instance created](images/image-04.png)

- Successfully launched and connected to the instance using **MobaXterm**.

📸 **Screenshots:**  
![Connected to instance using MobaXterm](images/image-05.png)  
![Connected](images/image-06.png)

---

### 🔹 System Preparation
- Updated and upgraded system packages.

📸 **Screenshot:**  
![Updated and upgraded system packages](images/image-07.png)

---

### 🔹 Apache Installation and Setup
- Installed **Apache**.

📸 **Screenshot:**  
![Installed Apache](images/image-08.png)

- Started, enabled, and checked the **Apache service status**.

📸 **Screenshot:**  
![Started, enabled, and checked Apache status](images/image-09.png)

- Verified that **Apache is running** using the public IP address.

📸 **Screenshot:**  
![Apache running](images/image-10.png)

---

### 🔹 MySQL Installation
- Installed **MySQL**.

📸 **Screenshot:**  
![Installed MySQL](images/image-11.png)

---

### 🔹 PHP Installation and Configuration
- Installed **PHP**.

📸 **Screenshot:**  
![Installed PHP](images/image-12.png)

- Verified the **PHP installation**.

📸 **Screenshot:**  
![Verified PHP](images/image-13.png)

- Created a **PHP info file**.

📸 **Screenshot:**  
![Created a PHP info file](images/image-14.png)

- Verified the **stack operation** by accessing the PHP info file in the browser.

📸 **Screenshot:**  
![Verified stack operation](images/image-15.png)

---

## 🎯 Conclusion
This guide provides a **fully functional LAMP stack** on AWS EC2 with proper configurations. The included screenshots help visualize each step for easy verification.

💡 **Next Steps:** Explore **LEMP stack setup** by following the [LEMP Guide](LEMP_Setup.md).

