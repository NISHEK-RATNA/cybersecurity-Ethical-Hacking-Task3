# ApexPlanet Software Pvt. Ltd.- Internship – Task 3
## Web Application Security Testing

### Internship Domain
Cybersecurity and Ethical Hacking

### Objective
The objective of this task was to identify and understand common web application security vulnerabilities using DVWA in a controlled Kali Linux environment.

### Testing Environment
- Operating System: Kali Linux
- Web Application: DVWA
- Web Server: Apache
- Database: MariaDB
- Testing Tool: Burp Suite Community Edition
- Browser: Firefox
- Command-Line Tool: cURL
- Target: Local DVWA installation
- Target URL: http://127.0.0.1/DVWA/

### Vulnerabilities Tested

#### 1. SQL Injection
Tested SQL Injection and Blind SQL Injection using DVWA.

**Mitigation:**
- Prepared Statements
- Parameterized SQL queries
- Input validation
- Least-privilege database accounts

#### 2. Cross-Site Scripting (XSS)
Tested:
- Stored XSS
- Reflected XSS
- DOM-Based XSS

**Mitigation:**
- Input validation
- Output encoding
- Content Security Policy (CSP)

#### 3. Cross-Site Request Forgery (CSRF)
Tested password-change functionality and demonstrated the need for CSRF protection.

**Mitigation:**
- CSRF tokens
- Server-side token verification
- SameSite cookie protection

#### 4. File Inclusion
Tested File Inclusion vulnerabilities using controlled inputs.

**Mitigation:**
- File allowlisting
- File-path validation
- Restricting remote file inclusion
- Proper filesystem permissions

#### 5. Command Injection
Tested whether user input could influence operating-system commands.

**Mitigation:**
- Input validation
- Safe application APIs
- Avoiding direct shell command execution
- Least-privilege execution

#### 6. Burp Suite
Used Burp Suite Proxy to intercept and analyze the DVWA login request.

Burp Suite Intruder
