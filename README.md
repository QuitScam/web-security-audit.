# Web Security Audit  
This project demonstrates a penetration test on a vulnerable web application using common tools like sqlmap, Nikto, and OWASP ZAP.

## Tools Used  
- **sqlmap**: Automated SQL injection discovery and exploitation.  
- **Nikto**: Web server vulnerability scanner.  
- **OWASP ZAP**: Proxy-based tool for web application penetration testing.  

## Methodology  
1. **Reconnaissance**  
   - Identify open ports and services using `nmap`.  
   - Check web application vulnerabilities with `Nikto`.

2. **Exploitation**  
   - Use `sqlmap` to test for SQL injection vulnerabilities.  
   - Explore security gaps in outdated components.

3. **Reporting**  
   - Document findings and provide recommendations for patching.  

## Results  
- **Critical vulnerabilities found**: 3.  
- **Recommendations**:  
  - Secure database queries to prevent SQL injections.  
  - Update web server software.  

## Screenshots  
- Coming soon.  

## Reports  
- Available in the `reports/` folder.