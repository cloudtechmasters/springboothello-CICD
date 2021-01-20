# Pre-Requisites:
    - Install GIT and Maven
    - Install Jenkins
    - Configure GIT and Maven with Jenkins
    - Create SMTP Credentials in SES
    - Verify Emails Address in SES
    - Create SSM Parameters
# Install Java
    yum install java-1.8.0-openjdk -y
# Install Jenkins:
    sudo wget -O /etc/yum.repos.d/jenkins.repo http://pkg.jenkins.io/redhat-stable/jenkins.repo
    sudo rpm --import http://pkg.jenkins.io/redhat-stable/jenkins.io.key
    sudo yum install jenkins -y
    service jenkins start
# Create SMTP Credentials in SES and Verify Emails Address in SES
  [SMTP Credentials and Verifying Email Address](https://github.com/Naresh240/AWS-Document/blob/main/Simple%20Email%20Service.md)
# Create SSM Parameters
  [Create SSM Parameters](https://github.com/Naresh240/AWS-Document/blob/main/SSM.md)
# Configure SES with Jenkins
  Goto Jenkins --> Manage Jenkins --> Configure System
  
  1. Please check "System Admin e-mail address" provided or not

  ![image](https://user-images.githubusercontent.com/58024415/102684258-f9983d00-41fc-11eb-8cc6-086ccea78fde.png)

  2. Provide SES details with jenkins
  
  ![image](https://user-images.githubusercontent.com/58024415/102684282-319f8000-41fd-11eb-8601-77a0b7debe96.png)
  
  Click on Test Configuration
  
  ![image](https://user-images.githubusercontent.com/58024415/102684332-83e0a100-41fd-11eb-9c40-4851620213aa.png)

# Create jenkins job with Jenkins-SSM and Build
  ![image](https://user-images.githubusercontent.com/58024415/102685042-a2e23180-4203-11eb-8e6b-2942f3d38ef9.png)

  Go and Check whether you get mail or not
# Note:
  If we provide other Email ID's which not varified with in SES, jenkins build will fail
  
