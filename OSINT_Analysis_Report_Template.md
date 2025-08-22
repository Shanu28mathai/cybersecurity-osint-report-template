## 1. Executive Summary
Summarize the scope of investigation and key findings (digital footprint, exposures, risks).  

## 2. Scope of Work
- [ ] WHOIS / Domain Investigation  
- [ ] Breach Data Analysis  
- [ ] Social Media OSINT  
- [ ] Dark Web Monitoring  
- [ ] Metadata Extraction  
- [ ] Other (comment box data injection) 

## 3. Tools & Resources Used
- Google Dorking  
- Maltego  
- Spiderfoot  
- TheHarvester
- DNSdumpster  
- WHOIS Lookup  
- Shodan
- Sherlock
  
## 4. Discovered Data

| Source          |          Information Discovered            | Risk Level | Notes                              |
|-----------------|--------------------------------------------|------------|------------------------------------|
| WHOIS           |       Admin email address exposed          |  Medium    | Should use privacy-protected WHOIS |
| Breach Data     |       Email found in 3 breaches            |   High     | Reset password, enable 2FA         |
| Social Media    |       Personal data (DOB, phone) visible   |  Medium    | Remove/restrict visibility         |

Risk Levels: High / Medium / Low

## 5. Digital Footprint Summary
- Number of social media profiles found  - 05 social count
- Leaked credentials identified - No evidence of leaked usernames, passwords, or credential dumps
- Publicly exposed domains/emails  - 2 email counts
- OSINT-based vulnerabilities  - None apparent from surface-level browsing; further technical analysis would be needed


## 6. Recommendations
1. Enable two-factor authentication on all accounts  
2. Change passwords for compromised emails  
3. Use separate email aliases for public activity  
4. Remove unnecessary personal details from public profiles  
5. Monitor for future breaches and leaks - HaveIBeenPwned for brutnow.com and all associated emails.


## 7. Conclusion
Summarize overall risk level and immediate next steps.  

## 8. Disclaimer
This OSINT report is based entirely on publicly available information. It is intended for informational purposes only.  
