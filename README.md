# INTRODUCTION TO JENKINS

## Introduction to CI/CD

Continuous Integration and Continuous Delivery is a set of best practices and methodologies that revolutionize the software development lifecycle by enhancing efficiency, reliability, and speed. CI/CD represents a seamless integration of automation and collaboration throughout the development process, aiming to deliver high-quality software consistently and rapidly.

---

## WHAT IS JENKINS

Jenkins is widely employed as a crucial CI/CD tool for automating software development processes. Teams utilize Jenkins to automate building, testing, and deploying applications, streamlining the development lifecycle. With Jenkins pipelines, developers can execute entire workflows as code, ensuring consistent and reproducible builds.

---

## Getting Started With Jenkins

### SSH into the Jenkins Instance

![Ssh Terminal](/introduction-to-jenkins/img/Ssh-terminal.png)

---

### Update Package Repositories

![sudo-apt-update](/introduction-to-jenkins/img/sudo-apt-update.png)

### Upgrade Package Repositories 

![sudo-apt-upgrade](/introduction-to-jenkins/img/sudo-apt-upgrade.png)

---

### Install JDK

![sudo-apt-install-default-jdk-headless](/introduction-to-jenkins/img/sudo-apt-install-default-jdk-headless.png)

---

### Install Jenkins 

The command below installs Jenkins. It involves importing the Jenkins GPG key for package verification, adding the Jenkins repository to the system's sources, updating package lists, and finally installing Jenkins through the package manager (`apt-get`).

![sudo-apt-get-install-jenkins](/introduction-to-jenkins/img/sudo-apt-get-install-jenkins.png)

---

### Check if Jenkins Has Been Installed, Up, and Running

![sudo-systemctl-status-jenkins](/introduction-to-jenkins/img/sudo-systemctl-status-)
