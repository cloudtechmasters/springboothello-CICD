# Pre-Requisites
    Ansible Setup (Install Jenkins in Master)
# Step1:
  Provide sudo permission for jenkins at below path
  vi /etc/sudoers
  
    jenkins ALL=(ALL)       NOPASSWD: ALL
  ![image](https://user-images.githubusercontent.com/58024415/100513792-d5b18080-3195-11eb-9703-ad3f28479b22.png)
# Step2:
  Create new job with Jenkinsfile-DockerCD content
# Step3: To create Container:
  Click on Build by providing action as "Create" and image tag
  
  ![image](https://user-images.githubusercontent.com/58024415/100516985-92fba280-31ad-11eb-85de-aaed802772c4.png)
# Step4: To remove container
  Click on Build by providing action as "Remove" and image tag
  
  ![image](https://user-images.githubusercontent.com/58024415/100517035-fa195700-31ad-11eb-9d0c-1b1360ddb421.png)
