# Ethical Hacking Task 01 – Information Gathering & Reconnaissance

# Project Overview

This project is submitted as part of the **Ethical Hacking Lab – Task 01**. The objective of this task is to understand and perform **Passive Reconnaissance (Information Gathering)** using publicly available resources. No exploitation or unauthorized access was attempted during this task.

The target selected for this assignment is the official website of **Infosys**.

---

# Objective

The main objectives of this task are:

- Understand the Reconnaissance phase of Ethical Hacking.
- Collect publicly available information about a target website.
- Perform WHOIS lookup.
- Analyze DNS records.
- Identify technologies used by the website.
- Check HTTP Security Headers.
- Analyze robots.txt and sitemap.xml.
- Prepare a professional security assessment report.

---

# Target Information

| Field | Details |
|-------|---------|
| Website Name | Infosys |
| Website URL | https://www.infosys.com |
| Target Type | Public Company Website |
| Reconnaissance Type | Passive Information Gathering |

---

# Tools Used

The following online tools were used during this task:

| Tool | Purpose |
|------|---------|
| WHOIS Lookup | Domain registration details |
| DNS Lookup | DNS record enumeration |
| BuiltWith | Website technology identification |
| SecurityHeaders | HTTP Security Header analysis |
| Browser | robots.txt & sitemap.xml analysis |

---

# Step 1 – WHOIS Lookup

WHOIS lookup was performed to collect public information about the registered domain.

# Information Collected

- Domain Name
- Registrar
- Registration Date
- Expiration Date
- Name Servers
- Domain Status

# Observation

The domain is registered through a well-known registrar and contains valid registration information. The domain status indicates that it is currently active.

**Screenshot**

```
Screenshots/01_WHOIS.png
```

---

# Step 2 – DNS Enumeration

DNS Enumeration helps identify different DNS records associated with the website.

# Records Identified

- A Record
- AAAA Record (if available)
- MX Record
- NS Record
- TXT Record

# Observation

The DNS records indicate proper domain configuration with dedicated mail servers and name servers.

**Screenshot**

```
Screenshots/02_DNS.png
```

---

# Step 3 – Website Technology Identification

Website technologies were identified using BuiltWith.

# Technologies Observed

- Web Server
- CDN
- JavaScript Libraries
- Frameworks
- SSL Certificate
- Analytics
- Content Delivery Network

# Observation

The website uses modern enterprise-level technologies for better security, scalability, and performance.

**Screenshot**

```
Screenshots/03_BuiltWith.png
```

---

# Step 4 – HTTP Security Headers Analysis

HTTP Security Headers were checked to evaluate the website's security posture.

| Header | Status | Purpose |
|--------|--------|---------|
| Content-Security-Policy | Present | Prevents XSS attacks |
| X-Frame-Options | Present | Prevents Clickjacking |
| X-Content-Type-Options | Present | Prevents MIME Sniffing |
| Strict-Transport-Security | Present | Forces HTTPS |
| Referrer-Policy | Present | Controls Referrer Information |

# Observation

Most recommended security headers are properly configured, indicating good security practices.

**Screenshot**

```
Screenshots/04_SecurityHeaders.png
```

---

# Step 5 – Robots.txt Analysis

The robots.txt file was accessed to understand crawler restrictions.

# URL

https://www.infosys.com/robots.txt

# Findings

- Search engine crawler rules are defined.
- Sensitive directories are restricted from indexing.
- Helps improve website SEO and crawler management.

**Screenshot**

```
Screenshots/05_Robots.png
```

---

# Step 6 – Sitemap Analysis

The sitemap.xml file was checked to identify indexed pages.

# URL

https://www.infosys.com/sitemap.xml

# Findings

- Sitemap is available.
- Contains URLs for search engine indexing.
- Improves website discoverability.

**Screenshot**

```
Screenshots/06_Sitemap.png
```

---


# Observations

- The target website uses HTTPS.
- Security headers are properly configured.
- Public DNS information is accessible.
- Domain registration information is available through WHOIS.
- Website uses enterprise-level technologies.
- Proper SEO configuration is implemented using robots.txt and sitemap.xml.

---

# Learning Outcomes

After completing this task, I learned:

- Fundamentals of Passive Reconnaissance
- Domain Information Gathering
- WHOIS Analysis
- DNS Enumeration
- Website Fingerprinting
- HTTP Security Header Analysis
- Importance of robots.txt
- Importance of sitemap.xml
- Ethical and Legal Information Gathering

---

# Conclusion

This project provided practical knowledge of the reconnaissance phase of ethical hacking. During the task, publicly available information about the selected target website was collected using passive reconnaissance techniques. WHOIS lookup revealed domain registration details, DNS enumeration identified network-related records, and technology fingerprinting helped determine the technologies used by the website. Security headers were analyzed to understand how the website protects itself against common web-based attacks. Additionally, robots.txt and sitemap.xml files were examined to understand website indexing and crawler management. This exercise demonstrated that a significant amount of useful information can be obtained without interacting directly with the target system. Overall, the task strengthened my understanding of ethical hacking methodologies and the importance of information gathering in cybersecurity assessments.

---

