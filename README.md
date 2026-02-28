# CS-305-Portofilo
CS 305
Bruno Manuel

Client Summary
Artemis Financial is a financial consulting company that creates personalized financial plans and manages sensitive customer information. Because the application processes confidential financial data, the primary software requirement was to strengthen security by reducing vulnerabilities, following secure development best practices, and protecting data—especially during transmission—against unauthorized access and exposure.

What I Did Well / Importance of Secure Coding
I performed well by identifying security weaknesses and applying secure coding improvements to reduce risk. I implemented HTTPS using SSL/TLS (with a self-signed certificate), adjusted the Spring Boot configuration to enforce secure connections, and reviewed dependency findings to reduce exposure from insecure or outdated components. Secure coding is critical because vulnerabilities can result in data breaches, financial loss, and reputational damage. Strong application security increases customer trust, supports business continuity, and reduces legal and operational risk.

Challenges / Helpful Parts
The most challenging part of the vulnerability assessment was interpreting OWASP Dependency-Check results and deciding which findings represented real risk versus false positives. This process was also helpful because it improved my ability to evaluate third-party libraries, understand real-world impact, and balance security updates with application stability.

Layers of Security / Future Tools
I increased layers of security by enabling SSL/TLS encryption, removing unnecessary dependencies, enforcing input validation, using secure exception handling practices, and configuring secure communication settings (such as strong cipher suites where applicable). In the future, I would continue using OWASP tools like Dependency-Check and OWASP ZAP, along with static analysis tools such as SonarQube, to identify issues early. I would prioritize mitigations using a risk-based approach (severity, exploitability, and business impact) to select the most effective fixes.

Testing & Verification After Refactoring
To confirm the software stayed functional and secure, I ran the application locally and validated that endpoints worked correctly over HTTPS. After refactoring, I re-ran vulnerability scans to verify that previously identified issues were addressed and that no new vulnerabilities were introduced. Repeated scanning and regression testing helped ensure that security improvements did not break functionality.

Tools & Practices Used
OWASP Dependency-Check for dependency vulnerability scanning
Spring Boot security configurations to support secure application behavior
SSL/TLS certificate generation to encrypt data in transit
Secure coding principles (least privilege, input sanitization, safe error handling)

What I’d Show Employers
For employers, I would highlight my Artemis Financial Secure Software Report (or Vulnerability Assessment Report) along with the refactored code changes that demonstrate secure communication via HTTPS and vulnerability mitigation. These artifacts show that I can interpret security scan results, apply secure development practices, and improve software security while maintaining a working application.
