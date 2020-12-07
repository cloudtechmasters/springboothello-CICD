# spring-boot-hello

# Pre-requisites:
  - Install Java
  - Install GIT
  - Install Maven
  - Jenkins setup
# Make Less secure app access: ON
  Login to Gmail.
  Access the URL as https://www.google.com/settings/security/lesssecureapps
  
  ![image](https://user-images.githubusercontent.com/58024415/100221905-53c81a00-2f3f-11eb-8edd-2e7f6c1e218c.png)
# DisplayUnlockCaptcha need to be continue
  URL: https://accounts.google.com/DisplayUnlockCaptcha
  Before:
  
  ![image](https://user-images.githubusercontent.com/58024415/100222050-8d992080-2f3f-11eb-8db1-f47c39f172e4.png)

  After:
  
  ![image](https://user-images.githubusercontent.com/58024415/100222121-a3a6e100-2f3f-11eb-8d52-9b8f1c8a9b23.png)

# Integrate Email  with Jenkins:
  Goto Manage Jenkins -->  Configure System  -->  E-mail Notification
  
  ![image](https://user-images.githubusercontent.com/58024415/100221627-f16f1980-2f3e-11eb-8aa1-98aff71081e9.png)

# Integrate GIT with Jenkins:
  Goto Manage Jenkins -->  Global Tool Configuration
  
  ![image](https://user-images.githubusercontent.com/58024415/100222325-f1234e00-2f3f-11eb-948a-725756cc08b2.png)

# Integrate Maven with Jenkins:
  Goto Manage Jenkins -->  Global Tool Configuration
  
  ![image](https://user-images.githubusercontent.com/58024415/100222435-13b56700-2f40-11eb-9c09-46e5a434f539.png)

# Create docker credentials
  Goto Manage Jenkins -->  Manage Credentials
  
  ![image](https://user-images.githubusercontent.com/58024415/100224041-4b251300-2f42-11eb-82bd-f07e7fbb3aca.png)
# Build Pipeline job and keep Jenkins pipeline data and click on build
  ![image](https://user-images.githubusercontent.com/58024415/100222656-6abb3c00-2f40-11eb-915e-d54b2c80c3b7.png)
# Check Mail will get mail as shown below:
  ![image](https://user-images.githubusercontent.com/58024415/100222760-93433600-2f40-11eb-8efa-5d5ac4b035fd.png)
