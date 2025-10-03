# Network Security Simulation Lab

## Project Overview
Designed and deployed a secure virtualized testing environment to practice vulnerability assessment and penetration testing techniques in a controlled setting.

## Objectives
- Build enterprise-grade network architecture
- Implement security controls and monitoring
- Conduct vulnerability assessments
- Practice incident response procedures

## Architecture

### Environment Specifications
- **Hypervisor:** VirtualBox
- **Operating Systems:**
  - Kali Linux (Attacker machine)
  - Windows Server 2019 (Target)
  - Ubuntu 20.04 Server (Target)

### Network Design
- Isolated internal network (192.168.50.0/24)
- Static IP assignments
- Firewall rules implemented
- Network segmentation for security testing

[View Network Diagram](architecture/network-diagram.png)

## Implementation

### Phase 1: Infrastructure Setup
- Configured 3 virtual machines with static IPs
- Established isolated network environment
- Implemented basic firewall rules
- Set up monitoring and logging

### Phase 2: Security Testing
- Conducted social engineering simulations using SET
- Performed network reconnaissance
- Identified 5 critical security misconfigurations
- Documented findings with evidence

### Phase 3: Remediation
- Developed security hardening recommendations
- Implemented firewall rule improvements
- Established security baselines
- Created incident response procedures

## Key Findings
1. **Misconfigured Firewall Rules** - Allowed unrestricted inbound traffic on critical ports
2. **Weak Password Policies** - Default passwords on administrative accounts
3. **Unnecessary Services Running** - Expanded attack surface
4. **Missing Security Updates** - Known vulnerabilities present
5. **Insufficient Logging** - Limited visibility into security events

## Skills Demonstrated
- Network architecture and design
- Virtualization (VirtualBox)
- Linux/Windows system administration
- Security testing methodologies
- Technical documentation and reporting
- Risk assessment and mitigation

## Documentation
- [Network Diagram](architecture/network-diagram.png)
- [VM Configuration Guide](configuration/vm-setup-guide.md)
- [Firewall Rules](configuration/firewall-rules.md)
- [Vulnerability Assessment Report](testing/vulnerability-assessment.md)
- [Remediation Plan](testing/findings-and-remediation.md)

## Lessons Learned
- Importance of defense-in-depth strategy
- Value of proper network segmentation
- Need for comprehensive logging and monitoring
- Balance between security and usability

## Future Enhancements
- [ ] Implement IDS/IPS (Snort)
- [ ] Add Active Directory environment
- [ ] Set up SIEM for log aggregation
- [ ] Create automated security scanning scripts
- [ ] Expand to include web application testing

---
**Project Duration:** 2 weeks  
**Last Updated:** September 2025
