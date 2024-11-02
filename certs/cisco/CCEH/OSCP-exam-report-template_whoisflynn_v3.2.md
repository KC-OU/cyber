---
title: "Cisco Certs - Network Academy - Ethical Hacker"
author: ["Kieran Collins"]
date: "2024-10-30"
subject: "Markdown"
keywords: [Markdown, Cisco, CCEH]
subtitle: "Cisco Network Acadmeny - Ethical Hacker"
lang: "en"
titlepage: true
titlepage-color: "00FF7F"
titlepage-text-color: "FFFFFF"
titlepage-rule-color: "000000"
titlepage-rule-height: 2
book: true
classoption: oneside
code-block-font-size: \scriptsize
---
# Cisco - Network Academy - Ethical Hacker 

## Course Introduction

### Welcome to the Ethical Hacking Course

This starts with a video with a breif introduction and below is a summary

This Ethical Hacking course, taught by Cisco principal engineer Omar Santos, aims to train future cybersecurity professionals to proactively identify vulnerabilities.  The course uses a gamified approach where students role-play as junior penetration testers at a fictional company.  Under the guidance of a virtual mentor, they'll conduct vulnerability assessments, solve challenges, and learn to think like hackers. Though intense, the course promises to be a rewarding experience, equipping students with essential ethical hacking skills and a strong cybersecurity mindset.


### The Fictional Companies in the Ethical Hacking Course
Throughout the content of the course, you follow an engaging gamified narrative and get lots of practice with hands-on labs inspired by real-world scenarios. On this journey, you will be guided by your virtual mentor “Alex” at our fictional offensive security company, Protego Security Solutions. Within your role as a junior penetration tester at Protego, you will learn all the penetration testing phases of a client engagement. Pixel Paradise, a video game company, is the fictional company that will serve as your client during the course. 

Below are informational flyers for each fictional company.

![Protego-Security-Solutions](certs/cisco/CCEH/img/protego.png){ width=90% height=90% }

![Pixel-Paradise](certs/cisco/CCEH/img/pixel.png){ width=85% height=85% } 

### What will I Learn in This Course?

The digital landscape is evolving at an unprecedented rate and cyber threats lurk around every corner. Cybersecurity resilience in the modern world cannot be just an add on - it's a necessity.

Offensive security professionals like ethical hackers and penetration testers can help proactively discover unknown threats and address them before the cybercriminals do.

This course is designed to prepare you with an Ethical Hacker skillset and give you a solid understanding of offensive security. You will become proficient in the art of scoping, executing, and reporting on vulnerability assessments, while recommending mitigation strategies.

After completing this course, continue your cybersecurity career in offensive security (red team) as an ethical hacker or penetration tester. Or use this course to strengthen your defensive security (blue team) knowledge. By understanding the mindset of threat actors, you will be able to more effectively implement security controls and monitor, analyze, and respond to current security threats.

| Module Title  | Module Objectives |
| ------------- |-------------------|
|Introduction to Ethical Hacking and Penetration Testing| Explain the importance of methodological ethical hacking and penetration testing. |
|Planning and Scoping a Penetration Testing Assessment|Create penetration testing preliminary documents.|
|Information Gathering and Vulnerability Scanning|Perform information gathering and vulnerability scanning activities.|
|Social Engineering Attacks|Explain how social engineering attacks succeed.|
|Exploiting Application-Based Vulnerabilities|Explain how to exploit wired and wireless network vulnerabilities.|
|Cloud, Mobile, and IoT Security|Explain how to exploit cloud, mobile, and IoT security vulnerabilities.|
|Performing Post-Exploitation Techniques|Explain how to perform post-exploitation activities.|
|Reporting and Communication|Create a penetration testing report.|
|Tools and Code Analysis|Classify pentesting tools by use case.|

## Module 1 - Introduction to Ethical Hacking and Penetration Testing

### 1.0 Introdution - Skipping

I am skipping 1.0 Introduction due to not it is not required due to is have parts that are not relevient at this point of time.

### 1.1 Understanding Ethical Hacking and Penetration Testing

As a refresher, the term ethical hacker describes a person who acts as an attacker and evaluates the security posture of a computer network for the purpose of minimizing risk. The NIST Computer Security Resource Center (CSRC) defines a hacker as an “unauthorized user who attempts to or gains access to an information system.” Now, we all know that the term hacker has been used in many different ways and has many different definitions. Most people in a computer technology field would consider themselves hackers based on the simple fact that they like to tinker. This is obviously not a malicious thing. So, the key factor here in defining ethical versus nonethical hacking is that the latter involves malicious intent. The permission to attack or permission to test is crucial and what will keep you out of trouble! This permission to attack is often referred to as “the scope” of the test (what you are allowed and not allowed to test). More on this later in this module.

A security researcher looking for vulnerabilities in products, applications, or web services is considered an ethical hacker if he or she responsibly discloses those vulnerabilities to the vendors or owners of the targeted research. However, the same type of “research” performed by someone who then uses the same vulnerability to gain unauthorized access to a target network/system would be considered a nonethical hacker. We could even go so far as to say that someone who finds a vulnerability and discloses it publicly without working with a vendor is considered a nonethical hacker – because this could lead to the compromise of networks/systems by others who use this information in a malicious way.
The truth is that as an ethical hacker, you use the same tools to find vulnerabilities and exploit targets as do nonethical hackers. However, as an ethical hacker, you would typically report your findings to the vendor or customer you are helping to make the network more secure. You would also try to avoid performing any tests or exploits that might be destructive in nature.

An ethical hacker’s goal is to analyze the security posture of a network’s or system’s infrastructure in an effort to identify and possibly exploit any security weaknesses found and then determine if a compromise is possible. This process is called security penetration testing or ethical hacking.

> [!TIP]
> Hacking is NOT a Crime [**Hacking is not a Crime**](https://hackingisnotacrime.org) is a nonprofit organization that attempts to raise awareness about the pejorative use of the term hacker. Historically, hackers have been portrayed as evil or illegal. Luckily, a lot of people already know that hackers are curious individuals who want to understand how things work and how to make them more secure.

### Why Do We Need to Do Penetration Testing?

So, why do we need penetration testing? Well, first of all, as someone who is responsible for securing and defending a network/system, you want to find any possible paths of compromise before the bad guys do. For years we have developed and implemented many different defensive techniques (for instance, antivirus, firewalls, intrusion prevention systems [IPSs], anti-malware). We have deployed defense-in-depth as a method to secure and defend our networks. But how do we know if those defenses really work and whether they are enough to keep out the bad guys? How valuable is the data that we are protecting, and are we protecting the right things? These are some of the questions that should be answered by a penetration test. If you build a fence around your yard with the intent of keeping your dog from getting out, maybe it only needs to be 4 feet tall. However, if your concern is not the dog getting out but an intruder getting in, then you need a different fence – one that would need to be much taller than 4 feet. Depending on what you are protecting, you might also want razor wire on the top of the fence to deter the bad guys even more. When it comes to information security, we need to do the same type of assessments on our networks and systems. We need to determine what it is we are protecting and whether our defenses can hold up to the threats that are imposed on them. This is where penetration testing comes in. Simply implementing a firewall, an IPS, anti-malware, a VPN, a web application firewall (WAF), and other modern security defenses isn’t enough. You also need to test their validity. And you need to do this on a regular basis. As you know, networks and systems change constantly. This means the attack surface can change as well, and when it does, you need to consider reevaluating the security posture by way of a penetration test.


### 1.1.3 **Lab** - Researching Pentesting Careers

I think it is important for you to understand the employment landscape and the different roles and responsibilities that cybersecurity professions include. A good general reference to explore for descriptions of different job roles is The National Initiative for Cybersecurity Careers and Studies (NICCS) Cyber Career Pathways Tool. It offers a visual way to discover and compare different job roles in our profession.

In this activity, you discover and compare ethical hacking jobs that are listed on various job boards. Don’t worry, we are not trying to get rid of you! We just want you to understand where you fit in to the big picture in our profession. I think that you will find that we are treating you very well, and rest assured that you have a lot of room to grow with us.

In this lab, you will complete the following objectives:

- Conduct a Penetration Tester Job Search
- Analyze Penetration Tester Job Requirements
- Discover Resources to Further Your Career




# Labs Questions and Answers

> [!WARNING]
> This will the machines and courses answers, so please see this a **Warning**.

## 1.1.3

