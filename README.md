# Client Overview and Software Requirements
### Client: Artemis Financial is a financial services company seeking to improve the security of its web-based software application.
### Issue: The client wanted a thorough vulnerability assessment to identify and mitigate security risks in their system, ensuring compliance and protecting sensitive financial data.
# Vulnerability Discovery and Secure Coding
## What I did well:

I identified insecure code patterns and outdated dependencies.

I used OWASP Dependency-Check to detect known vulnerabilities.

I manually reviewed code for potential logic flaws and data exposure risks.

## Importance of Secure Coding:

It prevents breaches that could expose client data or cause financial loss.

Secure coding protects company reputation, ensures compliance with regulations, and reduces costly remediation later.

## Value to Company:

Strengthens trust with clients.

Reduces downtime and financial risk from cyberattacks.

Increases system resilience and maintainability.

# Challenges and Helpful Parts
## Challenging:

Understanding how to suppress false positives in the OWASP scan using XML properly.

Tracing indirect dependencies that introduced vulnerabilities.

## Helpful:

Gaining hands-on experience with Maven plugins and learning how to interpret CVE reports.

# Security Layers and Future Strategies
## Security Layers Added:

Implemented AES-256 encryption for data handling.

Used Java Keytool to create and manage a self-signed certificate for HTTPS communication.

Verified checksums to ensure file integrity.

## Future Assessment Tools:

I would combine static analysis tools (like SonarQube) with dynamic testing (e.g., OWASP ZAP)

Use threat modeling and CVSS scores to prioritize mitigation efforts.

# Ensuring Functional and Secure Code
## Post-Refactor Testing:

I ran the application to verify expected functionality.

Re-ran OWASP Dependency-Check to confirm no new vulnerabilities were introduced.

Conducted manual functional testing to verify encrypted communication and data handling.

# Tools, Resources, and Best Practices
## Used in Project:

OWASP Dependency-Check

Maven for build and dependency management

Java Keytool for certificate handling

AES encryption in Java

Static code review

## Helpful Practices:

Commenting code for clarity

Keeping libraries updated

Writing modular, testable methods

# Showcasing to Employers
I would present this project to employers as an example of my:

Proficiency in secure software development

Experience using security tools like OWASP and Keytool

Ability to refactor legacy code while maintaining functionality

Understanding of real-world software risk mitigation

It demonstrates technical skill, attention to detail, and a security-first mindset—qualities highly valued in modern software development.

