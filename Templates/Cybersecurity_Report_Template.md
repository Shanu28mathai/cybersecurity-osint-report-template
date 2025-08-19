# 🛡️ Cybersecurity Assessment Report

*Client/Company:Brutnow Media Company*
*Website/Domain:https://brutnow.com*  
*Date:18/0/2025*  
*Analyst:Shanu Mathai*  

---

## 1. Executive Summary
Provide a non-technical overview of the assessment results. Highlight key findings, risks, and the overall security posture.

---

## 2. Scope of Work

- [ ] Web Application Security Scan  
- [ ] Vulnerability Scan  
- [ ] Network/Port Analysis  
- [ ] WordPress Security Check  
- [ ] SSL/TLS Configuration Check  
- [ ] Other (databroken link)  

---

## 3. Tools & Methodology

List the tools and frameworks used for the assessment.  
- Nmap  
- WPScan  
- Nikto  
- Gobuster 
- SSLscan
- hydra
- Ncrack
- DNSMap
- recon-ng

---

## 4. Findings

Risk ID 	Description	                          Severity	    Recommendation
C-01	Outdated word-press plugins	               High	         Update to latest version
C-02	Port 21(FTP) open	                         Medium	       Disable FTP or restrict access
C-03	Weak SSL/TLS configuration	               Medium	       Enable TLS 1.2+ only
C-04	XML-RPC enabled 	                         High	         Disable xml-rpc 
C-05	Default login URL	                         Critical      Limited login or disabled default login 


Severity Levels: Critical / High / Medium / Low

---

## 5. Risk Assessment
Summarize how findings affect the client’s risk exposure.  
- Critical: Immediate action required  - C-05
- High: Needs urgent remediation  - C-04 & C-01
- Medium: Should be fixed in normal patch cycle  - C-02 & C-03
- Low: Monitor and address as needed  

---

## 6. Recommendations & Action Plan
Provide clear next steps for the client.  
1. Patch outdated software  
2. Disable unnecessary services/ports  
3. Improve password & access policies  
4. Harden web server security  
5. Enable security monitoring  

---

## 7. Conclusion
Summarize overall security status and stress importance of continuous monitoring and updates.  

---

## 8. Disclaimer
This report is for educational and informational purposes only. The assessment was conducted based on the agreed scope and publicly available information
