# 🚀 LEMP Stack Setup

## 📖 Overview
This guide provides step-by-step instructions for setting up a **LEMP (Linux, Nginx, MySQL, PHP) stack** on an **AWS EC2 Ubuntu instance**. Each section includes commands, configurations, and verification steps with images.

---

## 🛠️ Part 2: Setting Up LEMP Stack

### 🔹 Instance Setup
- Created a **new EC2 instance** and connected via SSH.

📸 **Screenshot:**  
![Instance creation and connection](images/image-16.png)

---

### 🔹 Nginx Installation and Setup
- Installed **Nginx**.

📸 **Screenshot:**  
![Installed Nginx](images/image-17.png)

- Started, enabled, and checked the **Nginx service status**.

📸 **Screenshot:**  
![Started, enabled, and checked status](images/image-18.png)

---

### 🔹 MySQL Installation
- Installed **MySQL**.

📸 **Screenshot:**  
![Installed MySQL](images/image-19.png)

- Started and enabled the **MySQL service**.

📸 **Screenshot:**  
![Started and enabled MySQL](images/image-20.png)

---

### 🔹 PHP Installation and Configuration
- Installed **PHP**.

📸 **Screenshot:**  
![Installed PHP](images/image-21.png)

- Started and enabled the **PHP service**.
- Encountered an issue where PHP didn't start automatically. Resolved it by fetching the **specific PHP version** and manually starting it.

📸 **Screenshot:**  
![Started and enabled PHP](images/image-22.png)

---

### 🔹 Nginx and PHP Integration
- Configured **Nginx** to support **PHP processing**.
- Created a **PHP info file** and confirmed a successful stack setup by accessing the PHP info file in the browser.

📸 **Screenshot:**  
![Successful stack operation](images/image-23.png)

---

## 🎯 Conclusion
This guide provides a **fully functional LEMP stack** on AWS EC2 with proper configurations. The included screenshots help visualize each step for easy verification.

💡 **Next Steps:** Explore more about **Nginx configurations** or check the [LAMP Guide](LAMP_Setup.md) if you need an Apache-based setup.

