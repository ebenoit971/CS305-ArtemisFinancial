# CS 305 Module Eight Journal – Reflection

## Course Overview
This repository contains my portfolio submission for **CS 305: Software Security** at Southern New Hampshire University.  
It includes one key artifact demonstrating secure coding and vulnerability assessment practices completed for the client **Artemis Financial**.

---

## Artifact Submitted
**Artifact:** Artemis Financial Vulnerability Assessment Report  
**Purpose:** Demonstrate my ability to identify, analyze, and mitigate software vulnerabilities while applying secure coding techniques.

---

## Client Summary
Artemis Financial is a financial services company that develops web-based applications to manage client transactions securely.  
The company wanted to enhance the security of its RESTful API to ensure that sensitive financial data remained protected.  
My role was to identify vulnerabilities, perform a security assessment, and apply best practices for secure coding to protect the system from potential threats.

---

## Vulnerability Assessment and Secure Coding
I successfully identified multiple security risks using the **OWASP Dependency-Check** tool and implemented **SSL/TLS encryption** with a self-signed certificate.  
I analyzed project dependencies and suppressed false positives to improve accuracy.  
Secure coding is essential because it prevents data breaches, maintains integrity, and protects a company’s reputation.  
Software security directly supports customer trust and organizational reliability.

---

## Challenges and Key Takeaways
The most challenging step was configuring Maven and interpreting detailed vulnerability reports.  
However, this process was valuable because it taught me how to read **CVSS scores** and prioritize risk mitigation.  
It strengthened my analytical approach to identifying and resolving security weaknesses.

---

##  Increasing Layers of Security
I added multiple layers of security by:
- Enabling **HTTPS communication** via an SSL keystore  
- Implementing **certificate validation**  
- Running **dependency scans** to detect outdated or risky libraries  

In the future, I would integrate **CI/CD security scanning** with tools such as **SonarQube** or **Snyk** for continuous monitoring and automated mitigation.

---

## Testing Functionality and Security
After refactoring, I launched the Spring Boot application securely in Eclipse as a Maven build.  
I verified successful HTTPS communication and reran the OWASP Dependency-Check scan to ensure no new vulnerabilities were introduced.

---

## Helpful Tools and Resources
- **OWASP Dependency-Check** – for vulnerability scanning  
- **Java Keytool** – for certificate creation and SSL configuration  
- **Maven** – for project build and dependency management  

These tools will continue to be useful in future software development and cybersecurity projects.

---

##  Future Employer Relevance
The **Artemis Financial Vulnerability Assessment Report** demonstrates my ability to perform real-world software security tasks, identify vulnerabilities, and apply secure coding practices.  
This artifact highlights my **technical skill, analytical reasoning, and understanding of cybersecurity best practices**.

---

## Repository Link
> Include this repository link when submitting your journal in Brightspace:  
> [https://github.com/YOUR-USERNAME/CS305-ArtemisFinancial](https://github.com/YOUR-USERNAME/CS305-ArtemisFinancial)

---

*Author: Edward Benoit*  
*Course: CS 305 – Software Security*  
*Southern New Hampshire University*
