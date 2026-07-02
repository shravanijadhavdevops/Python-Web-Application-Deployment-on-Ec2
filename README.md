# Python Web Application Deployment on Ec2
## Introduction
This project demonstrates how to deploy a Python web application on a cloud server using Amazon EC2. It covers the complete process from launching a virtual server to running the application successfully.



The goal of this project is to gain hands-on experience with cloud computing, Linux commands, and Python environment setup.

## Architecture Diagram
![alt text](<imgs/architecture diagarm.jpeg>)
## Steps I Followed
## 1.launching an ec2 instance 
 ![alt text](<imgs/lunching ec2.png>)
 ## 2.Connect using ssh
 ssh -i your-key.pem ec2-user@your-public-ip
 ![alt text](<imgs/connect through ssh.png>)
 ## 3.Installation of PYTHON
 sudo yum update -y<br>
 sudo yum install python3 -y
 ![alt text](<imgs/installation of python.png>)
 * verify version:<br>
 python3 --version
 ## 4.Installation of pip
 sudo yum install python3-pip -y
 ![alt text](<imgs/instalation of pip.png>)
 * Verify pip:<br>
 pip3 --version
 ## 5.Clone the Repository
 git clone url<br>
 ![alt text](<imgs/clone from github.png>)
cd pythonapp![alt text](<imgs/goes inside pythoneapp through cd.png>)
 ## 6.Create Virtual Environment
 python3 -m venv myenv 
 ![alt text](<imgs/create virtual environment.png>)
 ## 7.Activate virtual environment
 bash myenv/bin/activates
 ![alt text](<imgs/run virtual environment.png>)
 ## 8.Install dependencies
 pip install -r requirements.txt<br>
 python3 app.py
  ![alt text](<imgs/install dependency.png>)
  ## 9.Access the Application
  public ip : port<br>
  port no -> 5000
  ![alt text](<imgs/access of web.png>)
  ## Key Features
* Deployment on AWS EC2
* Complete setup from scratch
* Virtual environment usage
* Dependency management with pip
## Challenges Faced
* Connecting securely using SSH
* Managing Linux commands
* Setting up Python environment correctly
# Project Summary
This project successfully demonstrates the deployment of a Python web application on a cloud platform. Starting from launching an EC2 instance, the process includes installing required tools, configuring the environment, and running the application.
It provides practical experience in cloud computing, server management, and backend deployment, making it a strong foundation for real-world DevOps and backend development tasks.