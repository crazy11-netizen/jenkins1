Here i have created a jenkins file. 
Jenkins pipeline requires a pom.xml (file with all dependencies required to run java file-> refer net for now).   
pom.xml file is added. 
Java file is added at src/main/java/com/example.                       
A jsp file is also added at src/main/webpage/ inorder to see the webpage as output.
---
Clear steps of working of this CI/CD project:

## 🎯  Key Learnings

* CI/CD automation using Jenkins
* Maven build lifecycle
* WAR packaging for Java web apps
* Artifact management in Jenkins
---

## 📌J Pipeline Summary

```text
GitHub → Jenkins → Maven Build → WAR File → Artifact Storage
```
--- 

## 🚀} Future Improvements

* Deploy WAR automatically to Tomcat
* Add Docker containerization
* Integrate with Kubernetes
* Add unit testing stage (JUnit)
--


war file is present but not deployed yet. can be deployed from ec2-server DevServer
