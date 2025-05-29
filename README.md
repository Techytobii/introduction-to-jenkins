## INTRODUCTION TO JENKINS

# Introduction to CI/CD

Continuous Integration and Continuous Delivery is a set of best practices and methodologies that revolutionize the software development lifecycle by enhancing efficiency, reliabilty and speed. CI/CD represents a seamless integration of automation and collaboration throughout the devlopment process, aiming to deliver high-quality software consistently and rapidly.

****************************************************


# WHAT IS JENKINS

Jenkins is widely employed as a crucial CI/CD tool for automating software development processes. Teams utilize Jenkins to automate building, testing, and deploying applications, streamlining the development lifecycle. With Jenkins popelines, developers can execute entire workflows as code, ensuring consistent and reproducible builds.

# Getting Started With Jenkins

>> SSH into the Jenkins Instance

![ssh-terminal](Ssh-terminal.png)


*************************************


>> Update package repositories

 ![sudo-apt-update](./img/sudo-apt-update.png)


>> Upgrade package repositories 

![sudo-apt-upgrade](sudo-apt-upgrade.png)


*******************************************

>> Install JDK

![sudo-apt-install-default-jdk-headless](./img/sudo-apt-install-default-jdk-headless.png)


****************************************************


>> Install Jenkins 

The command below installs Jenkins, it involves importing the jenkins GPG key for package verification, adding the Jenkins repository to the system's sources, updating lists,and finally, installing Jenkins through the package manager (apt-get)

![sudo-apt-get-install-jenkins](./img/sudo-apt-get-install-jenkins.png)


****************************************************


>> Checked if Jenkins has been installed, Up and Running

![sudo-systemctl-status-jenkins](sudo-systemctl-status-jenkins.png)


**************************************************


# Created On the Jenkins instance New Inbound rules for port 8080 in the security group

![port-8080](./img/port-8080.png)


***************************************************

# ADDED JENKINS KEY 

![added-jkns-key](./img/added-jkns-key.png)


****************************************************

# Added Jenkins Repo to Sys

![added-jkns-repo-2-sys](./img/added-jkns-repo-2-sys.png)

## JENKINS

![jenkins](./img/jenkins.png)