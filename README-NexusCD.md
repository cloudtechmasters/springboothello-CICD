# Pre-Requisites
    - Upload artifact into Nexus server
    - Setup Ansible Environment
# Provide sudo permission for jenkins at below path
  vi /etc/sudoers
  
    jenkins ALL=(ALL)       NOPASSWD: ALL
  ![image](https://user-images.githubusercontent.com/58024415/100513792-d5b18080-3195-11eb-9703-ad3f28479b22.png)
# Create New job with 'Jenkinsfile-NexusCD' file content
# Click on Build to download artifact using ansible
