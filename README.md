# AWS DevOps Engineer Intern Assignment

## Candidate Details

- **Name:** Subiksha Ramesh
- **College:** St. Joseph's College of Engineering
- **Branch:** Artificial Intelligence and Machine Learning
- **Email:** subiksharamesh.2005@gmail.com
- **GitHub:** https://github.com/SubikshaRamesh

---

# Objective

The objective of this assignment is to deploy a simple static HTML website on an AWS EC2 Ubuntu instance using the Nginx web server. The assignment also demonstrates fundamental AWS, Linux, Docker, GitHub, and networking concepts.

---

# Task 1: AWS EC2 Instance Setup

Successfully launched an Ubuntu 24.04 LTS EC2 instance on AWS.

### Steps Performed

- Created an EC2 Ubuntu 24.04 LTS instance.
- Selected the t3.micro instance type.
- Created a new SSH key pair.
- Configured Security Groups.
- Allowed inbound traffic on:
  - SSH (Port 22)
  - HTTP (Port 80)
- Connected to the instance using EC2 Instance Connect.

---

# Task 2: Linux Administration

Performed basic Linux administration tasks on the EC2 instance.

### Commands Executed

```bash
sudo apt update
sudo apt upgrade -y
sudo apt install nginx -y
sudo systemctl status nginx
sudo systemctl restart nginx
df -h
free -h
ps -ef
```

### Purpose of Commands

| Command | Description |
|----------|-------------|
| `sudo apt update` | Updates the package repository |
| `sudo apt upgrade -y` | Upgrades installed packages |
| `sudo apt install nginx -y` | Installs Nginx Web Server |
| `sudo systemctl status nginx` | Checks Nginx service status |
| `sudo systemctl restart nginx` | Restarts Nginx service |
| `df -h` | Displays disk usage |
| `free -h` | Displays memory usage |
| `ps -ef` | Lists all running processes |

---

# Task 3: Website Deployment

Created and deployed a static HTML webpage using the Nginx web server.

### Website Contains

- Name
- College
- Branch
- Email
- Current Date

The default Nginx page was replaced with the custom webpage.

The website was successfully accessed using the EC2 Public IP address.

---

# Task 4: Git & GitHub

Created a public GitHub repository and uploaded the project files.

### Repository Contents

- index.html
- README.md
- Screenshots

Repository Link:

**https://github.com/SubikshaRamesh/aws-devops-intern-assignment**

---

# Bonus Task 1: Docker Installation

Installed Docker on the EC2 instance and verified the installation.

### Commands Used

```bash
sudo apt install docker.io -y
sudo systemctl start docker
sudo systemctl enable docker
docker --version
sudo docker run hello-world
```

### Result

Successfully installed Docker and verified the installation using the **Hello World** container.

---

# Bonus Task 2: Elastic IP Association

Allocated and associated an Elastic IP address with the EC2 instance.

### Benefits

- Provides a static public IP address.
- Public IP remains unchanged even after stopping and starting the instance.
- Commonly used for production servers and web applications.

Result:

Successfully allocated and associated an Elastic IP with the EC2 instance.

---

# AWS Services Used

- Amazon EC2
- Elastic IP
- Security Groups
- EC2 Instance Connect

---

# Software Used

- Ubuntu Server 24.04 LTS
- Nginx
- Docker
- Git
- GitHub
- Google Chrome

---

# Project Structure

```text
aws-devops-intern-assignment/
│
├── index.html
├── README.md
└── Screenshots/
    ├── 01-ec2-instance-summary.png
    ├── 02-security-group.png
    ├── 03-ssh-login.png
    ├── 04-nginx-status.png
    ├── 05-website-hosted.png
    ├── 06-disk-usage.png
    ├── 07-memory-usage.png
    ├── 08-running-processes.png
    ├── 09-docker-hello-world.png
    └── 10-elastic-ip.png
```

---

# Screenshots Included

- EC2 Instance Summary
- Security Group Configuration
- EC2 Instance Connect
- Nginx Installation
- Nginx Running Status
- Hosted Website
- Disk Usage
- Memory Usage
- Running Processes
- Docker Hello World
- Elastic IP Association

---

# Learnings

Through this assignment, I learned:

- Launching and managing AWS EC2 instances.
- Configuring Security Groups.
- Connecting to EC2 using EC2 Instance Connect.
- Basic Linux administration.
- Installing and managing the Nginx web server.
- Hosting a static website on AWS.
- Installing and using Docker.
- Allocating and associating an Elastic IP.
- Managing project documentation using GitHub.
- Understanding the fundamentals of DevOps and cloud deployment.

---

# Challenges Faced

- Understanding AWS Security Group configuration.
- Learning Linux commands.
- Installing and configuring Nginx.
- Hosting a custom HTML webpage.
- Installing Docker.
- Managing GitHub repository structure.

---

# Outcome

Successfully deployed a static HTML website on an AWS EC2 Ubuntu instance using the Nginx web server.

Additionally:

- Completed Linux administration tasks.
- Installed Docker and verified its functionality.
- Configured an Elastic IP for the EC2 instance.
- Uploaded the complete project to GitHub with documentation and screenshots.

---

# Conclusion

This assignment provided hands-on experience with AWS cloud infrastructure, Linux system administration, Nginx web server deployment, Docker containerization, Elastic IP configuration, and GitHub version control. It strengthened my understanding of cloud computing and DevOps fundamentals through practical implementation.

---

# Author

**Subiksha Ramesh**
