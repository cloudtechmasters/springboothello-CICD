# Active Parameters in Jenkins build

# Pre-Requisites:
    - Jenkins
    - docker images with tags in dockerhub
# Install Active parameter plugin in jenkins
  ![image](https://user-images.githubusercontent.com/58024415/102330032-150e0880-3faf-11eb-9d4b-5ef26c2cfa76.png)
# Create new pipeline job and select Active choice parameter
  ![image](https://user-images.githubusercontent.com/58024415/102330295-5ef6ee80-3faf-11eb-87db-8a535642ca29.png)
# Give Name for Parameter as "ImagTag" and Select redio button of Groovy script
  ![image](https://user-images.githubusercontent.com/58024415/102330548-b1d0a600-3faf-11eb-90d2-821a11685644.png)

  Also provide jenkins pipeline script in side pipeline section and click on save
# Check Jenkins job by clicking on Build with parameter
  ![image](https://user-images.githubusercontent.com/68885738/102331998-88b11500-3fb1-11eb-9dd9-f747e5c3dc7e.png)
# Open Port number: 8888 in security group and check output in web UI
  http://3.238.177.67:8888/hello
  
  ![image](https://user-images.githubusercontent.com/68885738/102332130-b5652c80-3fb1-11eb-9765-e14a6024540f.png)
