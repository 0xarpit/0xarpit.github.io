---
title: "DevSecOps from Zero to Hero..!!"
date: 2022-12-31T17:37:09+05:30
draft: false
# github_link: "https://github.com/0xarpit"
author: "Arpit Mittal"
tags:
  - DevSecOps
  - CI/CD
  - Jenkis
  - JIRA
  - Automation
  - SSDLC
  - AGile
  - Vulnerability Assessment
  - SAST
  - DAST
  - IAST
  - Secret Scanning
  - SCA
image: /devsecops.jpeg
---

Day by day we are learning different security approaches to minimize an improve the security gaps and for that we have to apply best possible security at all the levels. Now if we will talk about specifically for Application Security we can go with most preferred approaches which is SAST/DAST but do you think it is sufficient to secure your application as well as minimize the cost? The answer will be a big NO because while managing the whole application security domain we need to be ensured from the scratch and for this we have to start applying security best practices at the development level hence SSDLC (Secure Software Development Life Cycle) comes into the picture when we can train our developers to do the secure coding thus we can reduce the vulnerabilities count at the SAST and DAST level and then go for secure code review and dynamic security assessment process

<center><strong><h2>BUT</h2></strong></center>

### What if we can automate this process?

Yes here we go with the DevSecOps process to use a secure code practice along with the best security solutions to innovate and ensure the data security and maintain the privacy. We cannot just rely on the scanners and reports to check the loopholes and check the weaknesses. We are already aware with the DevOps approach since a long time and now we need to add 'Security' in between Development and Operation.

> DevSecOps integrate security seamlessly into Agile environment along with the different development and security solutions.

DevSecOps is mostly in use to automate your CI/CD process along with the security. In this stage you'll define how you'll automate your process, how many stages you will be required for better CI/CD, what solutions you'll use in each stages to improve the security posture. These solutions can be open source or enterprise it's all depends upon your budget but in most of the stages you can use open source solutions to reduce the cost. I've created below architecture as per my understanding with the each stages of DevSecOps:

<!-- ![No alt text provided for this image](https://media.licdn.com/dms/image/D4D12AQEAVLSxDBkIag/article-inline_image-shrink_1500_2232/0/1672429719028?e=1684972800&v=beta&t=SE1GSIrRy7UWqndSAp43h7V3g2UTckMuytI5pcTO6rs) -->

<!-- <img src="/devsecops1.png" style="height:300px; width:930px"> -->

DevSecOps process include the development and operations posture of your organisation so that you can analyse and place the security. I'll recommend to create an architecture overview like what you're going to implement, define the stages of CI/CD, define what will be the processes involve in each stages, how you'll deploy the code, how you'll test your code, how you'll monitor the environment. For an example i've created below architecture, this flow includes each stages along with the process/services:

<!-- ![No alt text provided for this image](https://media.licdn.com/dms/image/D4D12AQEOfeo4yc036g/article-inline_image-shrink_1000_1488/0/1672429754201?e=1684972800&v=beta&t=xICAvwiAWTnAZQMDAxwX56XfrIjmq_sviHQvXkcoUQQ) -->

<!-- <img src="/devsecops2.png" style="height:500px; width:930px"> -->


### Integration of Open-source Solutions into Pipeline:

It's easy to integrate open-source solution into existing CI/CD pipeline to enhance the security but before that check the solution properly and customise it as per your requirement (If needed), We've added few open-source solutions like Gitleaks, OWASP Dependency Checker, OWASP ZAP, etc. I'll share the reference below for further research. I'll also recommend to use any Vulnerability Management like Defectdojo to track the vulnerabilities.


### Benefits to Implement DevSecOps:

1.  Rapid, cost-effective software delivery
2.  Improved, proactive security
3.  Accelerated security vulnerability patching
4.  Automation compatible with modern development
5.  A repeatable and adaptive process

When we are saying DevSecOps it means continuation of integration and development along with the security. Here everyone can have a different mindset and approach to understand the DevSecOps process. When I've started my research about develops I came across multiple resources and I'll recommend everyone to explore from yourself on the basis of your requirements.

