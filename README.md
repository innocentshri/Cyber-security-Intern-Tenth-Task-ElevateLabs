# Task 10 – Firewall Configuration & Testing

## Objective
The objective of this task is to understand firewall concepts, configure firewall rules, allow and deny network traffic, test connectivity, and analyze the impact of firewall rules on system security.

---

## Tools Used
- UFW
- Windows Firewall
- iptables

---

## What is a Firewall?
A firewall is a network security system that monitors and controls incoming and outgoing network traffic based on predefined security rules. It acts as a barrier between trusted internal networks and untrusted external networks.

---

## Importance of Firewalls
Firewalls are used to:
- Block unauthorized access
- Prevent malicious traffic
- Control inbound and outbound connections
- Reduce attack surface
- Protect systems from network-based attacks

--- 

## Firewall Rule Concepts
Firewall rules define:
- Which traffic is allowed
- Which traffic is blocked
- Direction of traffic (inbound or outbound)
- Port numbers and protocols

---

### Basic Firewall Actions 

### Allowing Ports
Specific ports such as:
- Port 22 (SSH)
- Port 80 (HTTP)
- Port 443 (HTTPS)

are allowed to enable required services.

---

### Denying Ports
Unused or risky ports are blocked to prevent unauthorized access and reduce exposure.

---

## Blocking Malicious IP Addresses
Firewalls can block suspicious or malicious IP addresses to:
- Stop brute force attempts
- Prevent repeated unauthorized access
- Protect system resources

---

## Testing Firewall Rules
After applying firewall rules:
- Connectivity is tested
- Allowed services remain accessible
- Blocked services become unreachable
- Network behavior is observed

This confirms that firewall rules are working as expected.

---

## Observing Firewall Logs
Firewall logs help in:
- Monitoring blocked traffic
- Identifying suspicious activities
- Auditing security events
- Troubleshooting connectivity issues

---

## Impact of Firewall Configuration

| Action | Security Impact |
|------|----------------|
| Allow necessary ports | Ensures service availability |
| Block unused ports | Reduces attack surface |
| Block malicious IPs | Prevents attacks |
| Logging enabled | Improves monitoring |

---

## Security Benefits
Proper firewall configuration:
- Improves network security
- Protects systems from external threats
- Supports defense-in-depth strategy
- Enhances overall system hardening

---

## Ethical Considerations
All firewall configurations and testing are performed:
- On personal or authorized systems
- For educational purposes only
- Without impacting real production environments

---

## Summary
This task helped in understanding:
- Firewall fundamentals
- Rule configuration
- Traffic control
- Network protection techniques

---

## Final Outcome
Developed firewall management and network security skills.

---

## Sources & References

1. Ubuntu UFW Documentation  
https://help.ubuntu.com/community/UFW  

2. Linux iptables Documentation  
https://www.netfilter.org/documentation/  

3. Microsoft Windows Firewall Overview  
https://learn.microsoft.com/en-us/windows/security/operating-system-security/network-security/windows-firewall/  

4. Cloudflare – What is a Firewall?  
https://www.cloudflare.com/learning/security/what-is-a-firewall/  

5. OWASP – Network Security Controls  
https://owasp.org/www-project-top-ten/
