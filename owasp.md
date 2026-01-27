https://owasp.org/www-project-top-ten/
https://owasp.org/www-project-web-security-testing-guide/ 

---

## OWASP Top Ten Web Application Security Risks
1. **A01:2025 – Broken Access Control**  
Failures in enforcing what authenticated users are allowed to do — leads to unauthorized access to data or functionality. Includes issues like unauthorized privilege escalation and improper restriction of API endpoints.
2. **A02:2025 – Security Misconfiguration**  
Incorrectly configured systems or software defaults left insecure (open cloud storage, unnecessary services enabled, etc.). Often easy for attackers to find and exploit.
3. **A03:2025 – Software Supply Chain Failures**  
Weaknesses in the build, dependency, or distribution ecosystem — e.g., compromised third-party libraries or tooling that introduce vulnerabilities far upstream.
4. **A04:2025 – Cryptographic Failures**  
Improper use or lack of encryption, weak algorithms, poor key management — leading to sensitive data exposure or breaches of confidentiality/integrity.
5. **A05:2025 – Injection**  
Classic flaws like SQL, command, or other injections where untrusted input alters program logic, leading to data leaks, corruption, or control of back-end systems.
6. **A06:2025 – Insecure Design**  
Fundamental design flaws where security isn’t built into architecture and workflows. Prompts systemic weaknesses that technical controls alone can’t easily fix.
7. **A07:2025 – Authentication Failures**  
Weak or broken authentication mechanisms — e.g., poor session management, predictable tokens — that let attackers impersonate users.
8. **A08:2025 – Software or Data Integrity Failures**  
Failures to guarantee that code and data haven’t been tampered with — e.g., unsigned updates or unverified inputs leading to unauthorized changes.
9. **A09:2025 – Logging and Alerting Failures**  
Insufficient or ineffective security logging and alerting, making it hard to detect, investigate, or respond to incidents.
10. **A10:2025 – Mishandling of Exceptional Conditions**  
New in 2025: improper handling of error paths, edge cases, and system exceptions that can lead to logic flaws or “fail-open” vulnerabilities.
