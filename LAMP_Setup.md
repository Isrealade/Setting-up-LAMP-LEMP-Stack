Part 1: Setting Up LAMP Stack

- IAM User and Group Setup

    > Created an IAM user.
    > Created a user group and granted admin access permissions to that group
    > Added the IAM user to the group.
![User group and permission creation](images/image-01.png)

- EC2 Instance Creation

    > Launched an EC2 instance using Ubuntu.
    > Created a key pair during instance setup.
![Key pair creation](images/image-02.png)

    > Created a security group and configured necessary rules.
![Security group creation](images/image-03.png)
![Instance created](images/image-04.png)
    >Successfully launched and connected to the instance using MobaXterm.
![connected to instance using Mobaxterm](images/image-05.png)
![connected](images/image-06.png)


-System Preparation

    > Updated and upgraded system packages.
![updated and upgraded system packages](images/image-07.png)
    > Apache Installation and Setup

    > Installed Apache.
![Installed Apache](images/image-08.png)

    > Started, enabled, and checked the Apache service status.
![started, enabled and checked Apache status](images/image-09.png)

    > Verified that Apache is running using the public IP address.
![started, enabled and checked Apache status](images/image-10.png)


- MySQL Installation

    > Installed MySQL.
![Installed SQL](images/image-11.png)

- PHP Installation and Configuration
    > Installed PHP.
![Installed PHP](images/image-12.png)

    >Verified the PHP installation.
![Verified PHP](images/image-13.png)

    > Created a PHP info file.
![Created a PHP info file](images/image-14.png)

    > Verified the stack operation by accessing the PHP info file in the browser.
![Installed SQL](images/image-15.png)

