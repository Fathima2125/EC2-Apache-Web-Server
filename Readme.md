# EC2 Apache Web Server Project

This project demonstrates the setup of a web server using **AWS EC2** and **Apache HTTP Server**. It includes creating an EC2 instance, configuring security groups, connecting via EC2 Connect, and hosting a simple website.

---

## Project Overview

- **EC2 Instance**: Linux instance running on AWS.
- **Web Server**: Apache HTTP Server installed and configured.
- **Access**: Website accessible via browser on port 80.
- **Security**: SSH access via port 22, HTTP access via port 80.

---

## Steps Completed

1. Launched an **EC2 instance** on AWS.
2. Configured **Security Group** to allow:
   - Port 22 (SSH)
   - Port 80 (HTTP)
3. Connected to the instance using **EC2 Connect** terminal.
4. Installed and started **Apache HTTP Server**.
5. Hosted a sample website and verified access through the browser(using the public ipv$ address in instance).
6. Documented all **Apache commands** used in a separate file.

---

## Screenshots

1. ![EC2 Instance Running](<screenshots/EC2 Instance Running.png>)
2. ![Security Group Added](<screenshots/Security Group added.png>)
3. ![EC2 Connect Terminal](<screenshots/EC2 Connect Terminal.png>)
4. ![Start and enable apache commands](<screenshots/start and enable apache-commands.png>)
5. ![Final website running in browser](<screenshots/Final website in browser.png>)

> Screenshots are included in the `screenshots/` folder.

---

## Commands Reference

All commands used to set up and configure Apache are stored in `apache-commands.txt`.

---

## Conclusion:

I have successfully deployed an EC2 based web server running Apache. This setup is commonly used for hosting websites, web applications or acting as reverse proxy.

## Notes

- This setup is for learning and demonstration purposes.  
- Ensure security best practices when deploying in production.
- deleted all the resources after the completion of the project to prevent incurring charges.

---

**Author:** Fathima Yosra Ajeeb  