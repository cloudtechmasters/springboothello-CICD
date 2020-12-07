# Pre-Requisites:
    - Nexus server
    - Install GIT
    - Install Maven
# Integrate GIT and Maven with Jenkins
# Install 'pipeline-utility-steps' plugin
# Keep below line inside our scripts
  Manage Jenkins --> In-Process-Script-Approval
  
    method org.apache.maven.model.Model getPackaging
  ![image](https://user-images.githubusercontent.com/58024415/100500936-8701e780-3191-11eb-993f-6b694f09c35d.png)
# Create job with content of 'Jenkinsfile-Nexus' file content and then click on Build
