# CVE_Assessment_01_2019


Description: This is an assessment of the –INPUT-ACE version 2.2.1. This evaluation found vulnerabilities related to a possible buffer overflow  and a denial-of-service (DoS) using a User Datagram Protocol (UDP) flood attack . The UDP flood attack targeted the specific port in use by the software, instead of a flood around random ports on a remote host. As a result, the software achieved a status “suspended”.

References:
1. https://security.radware.com/ddos-knowledge-center/ddospedia/buffer-overflow-attack/ 
2. https://en.wikipedia.org/wiki/UDP_flood_attack 
3. https://en.wikipedia.org/wiki/Address_space_layout_randomization 
4. https://support.microsoft.com/en-ca/help/875352/a-detailed-description-of-the-data-execution-prevention-dep-feature-in 
5. https://docs.microsoft.com/en-us/windows/desktop/secbp/control-flow-guard 
6. https://docs.microsoft.com/en-us/windows/security/threat-protection/security-policy-settings/shut-down-the-system
7. https://cwe.mitre.org/data/definitions/131.html
