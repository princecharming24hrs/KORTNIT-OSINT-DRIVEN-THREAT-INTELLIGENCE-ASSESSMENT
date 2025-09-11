# KORTNIT GROUP - OSINT Driven Threat Intelligence Assessment
A Proactive and Preventive CyberSecurity Threat Intelligence project for an IT Service firm - Kortnit group


# A Brief about Kortnit Group

Sector: Information Technology

Primary Domain: kortnit.com

Kortnit Group is an IT Service firm that develops software for businesses to help manage their networks, systems, 
and information technology infrastructure. 
It is headquartered in Massachusetts, 
with sales and product development offices in several locations in the United States and several other countries.

# Executive Summary 
**Kortnit Project - Cybersecurity Assessment**

## **Project Overview**

This report documents a comprehensive cybersecurity assessment of Kortnit, an IT services company, conducted on September 11, 2025. The assessment employed multiple intelligence-gathering techniques to identify critical security exposures and potential attack vectors that could be exploited by threat actors.

## **Key Findings**

### **Information Exposure Through Multiple Channels**

The assessment revealed significant information leakage across various digital platforms:

* **Google Dorking** exposed sensitive documents including PDFs marked "confidential" and Excel files containing potential password information

* **Social media reconnaissance** on LinkedIn revealed detailed employee information and company structure

* **Document metadata analysis** using ExifTool disclosed author details and creation timestamps from official company documents

* **Email harvesting** through Maltego identified numerous employee email addresses across company domains

### **Critical Security Vulnerabilities Discovered**

1. **Employee Email Compromises**: Multiple staff email addresses were found in data breach databases via HaveIBeenPwned.com, indicating previous security incidents affecting personnel credentials

2. **Infrastructure Exposure**:

   * DNS records revealed internal network structure

   * WHOIS data exposed administrative contacts and technical infrastructure details

   * Subdomain enumeration using TheHarvester tool identified additional attack surfaces

1. **Configuration File Exposure**: Google dorking revealed potentially sensitive configuration files (XML, CNF formats) and administrative interfaces accessible through search engines

### **Threat Actor Analysis**

The assessment identified that companies like Kortnit are prime targets for:

* **Nation-State Actors**: Particularly the Russian Foreign Intelligence Service (SVR), which has previously targeted IT service providers

* **Advanced Persistent Threats (APTs)**: Groups conducting long-term, stealthy infiltration campaigns

* **Supply Chain Attackers**: Threat actors seeking to compromise downstream customers through trusted software providers

### **Historical Context: The SolarWinds Connection**

The report references the 2020 SolarWinds supply chain attack as a relevant case study, highlighting how IT service companies become high-value targets due to their trusted relationships with multiple organizations, including government agencies and major corporations.

## **Risk Assessment**

The combination of exposed sensitive information, compromised employee credentials, and Kortnit's position as an IT services provider creates a significant risk profile. The company's access to client systems and trusted position in the supply chain makes it an attractive target for sophisticated threat actors seeking broader access to downstream organizations.

## **Recommendations for Mitigation**

The assessment concludes with seven critical security improvements:

1. **Stronger Vendor Checks** - Implement comprehensive verification and auditing of software suppliers

2. **Zero Trust Approach** - Continuously verify all users and systems rather than relying on perimeter security

3. **Enhanced Monitoring** - Deploy advanced detection capabilities for unusual or hidden network activity

4. **Network Segmentation** - Limit potential attacker lateral movement through network isolation

5. **Careful Patching Procedures** - Validate all software updates before deployment to prevent malicious code injection

6. **Incident Response Planning** - Establish comprehensive procedures for detecting, containing, and recovering from security incidents

7. **Industry Collaboration** - Participate in threat intelligence sharing with industry peers and government agencies

## **Conclusion**

This assessment demonstrates multiple avenues through which Kortnit could be compromised by sophisticated threat actors. The company's role as an IT service provider amplifies these risks, as successful compromise could potentially impact numerous downstream clients. Immediate implementation of the recommended security controls is essential to reduce the organization's attack surface and improve overall security posture.



Our world and business are generally run by information
information meant to push the business further for greater productivity and profit 
and also enhance decision-making through communication 
Most companies now use email and social media to achieve these.
Systems that are used also need updates and upgrades to keep up with the growing information traffic
The information traffic has also posed a threat to many businesses' exposure to attacks, corruption, 
and breaches to company data, confidential documents, and processes.
These have cost millions of dollars in business closure, opportunity, client deflection, and even lawsuits 

The project was carried out on the Kortnit group (kortnit.com) to analyse its possible vulnerability 
and also propose a process to mitigate against possible IOC incidents of compromise detected within its infrastructure 
to avoid possible cyber exploits and future attacks on its business

# Scope and Methodology

# Tools

Goggle Dorking 

TheHarvester

Hunter.io

Maltego

# Findings and Analysis


# Potential Threats


# Recommendations

Tactics


Ethical Considerations






