# Evolving Threat Landscapes
This project investigates various cybersecurity websites and forums to analyse the evolving threat landscape. The forums explored include publicly accessible platforms, dark web markets, and industry-specific forums where threat actors and security professionals discuss vulnerabilities, attack methods, and defensive strategies. 


### Types of Cybersecurity Forums:
-	Publicly Accessible Forums: Platforms like Reddit or specialized cybersecurity communities (e.g., BleepingComputer, Hack Forums) where threat intelligence and security news are frequently shared.
-	Dark Web and Deep Web Forums (VIA A VENDOR) : Underground marketplaces and forums such as Raid Forums (now defunct), or new dark web platforms where malicious actors share tactics, tools, and compromised data.
-	Industry-Specific Forums (VIA A VENDOR): Security-focused forums related to particular industries, like financial, healthcare, or manufacturing sectors, where threat actors target vulnerabilities or share attack methods relevant to those sectors.


### To ensure the trends and threats identified are relevant and actionable:
1.	Cross-Referencing Threat Intelligence Sources: Once a trend or potential threat is identified on a forum, it will be cross-referenced with reputable threat intelligence platforms such as Flashpoint, Recorded Future, or Digital Shadows to validate its credibility.
2.	Correlation with Industry Reports: Trends will also be compared against recent industry reports like those from Verizon’s Data Breach Investigations Report (DBIR), CrowdStrike’s Global Threat Report, or other sector-specific cybersecurity reports, ensuring alignment with known attacks affecting different industries.
3.	Threat Actor Profiling: Adversary behaviours will be profiled using MITRE ATT&CK, matching the identified TTPs against well-known adversaries and groups, particularly those that target specific sectors (e.g., FIN groups targeting financial services or APT groups targeting government organizations).
4.	Relevance to Target Organizations: The identified techniques will be assessed for their impact on different types of organizations. This will include an analysis of how trends affect specific industries (e.g., phishing attacks in the financial sector vs. supply chain attacks in the manufacturing sector).

### Examing TTPs with MITRE ATT&CK

After identifying emerging trends and threats from these forums, MITRE ATT&CK is employed to examine the techniques, tactics, and procedures (TTPs) used by adversaries. The research focuses on specific adversary behaviours and attack vectors impacting organizations of various sizes, from mid-sized businesses to Fortune 500 companies. The project outlines both technical and procedural mitigations, with particular emphasis on defending against phishing, supply chain attacks, and other high-risk threat. (https://github.com/RaphaelEjike/MITRE_ATT-CK)


### Evolving Threat Landscapes: 

As the threat landscape continues to evolve, staying on top of emerging trends is essential to keep defences strong, especially in critical sectors like energy. This project delves into the latest cybersecurity trends for 2024. For each trend, I’ll also provide actionable recommendations to strengthen your organisation’s defences.

### Key Cybersecurity Trends to Watch in 2024

1. Generative AI (GenAI)
2. Remote Workforce Risks
3. AI-Based Predictive Social Engineering
4. Ransomware Escalation
5. Zero Trust Architecture
6. Third-Party Risk
7. Regulatory Changes


#### 1. Generative AI (GenAI) in Cybersecurity
Generative AI is revolutionizing threat detection and response. It’s enabling rapid analysis and response automation, but attackers are also leveraging it for highly personalized phishing campaigns and complex malware. Attackers used AI to craft emails that appeared to come from known contacts, bypassing traditional filters due to their accuracy.
#### Recommendations:
-	Implement multi-layered defences that go beyond traditional email filters.
-	Regularly train employees to recognize more sophisticated phishing techniques, especially those that appear highly personalized.
  #### Reference
- https://www.paloaltonetworks.com/cyberpedia/generative-ai-in-cybersecurity
- https://secureframe.com/blog/generative-ai-cybersecurity


#### 2. Remote Workforce Vulnerabilities
With the normalisation of remote work, attackers are increasingly targeting home networks and personal devices, which can be less secure than corporate environments. Attackers exploited vulnerabilities in the home setup, gaining access to company data.
#### Recommendations:
- Enforce VPN use and endpoint security tools for remote workers.
- Educate employees on securing home networks, including Wi-Fi encryption and updating devices.
#### Reference
- https://insights.sei.cmu.edu/blog/remote-work-vulnerabilities-and-threats-to-the-enterprise
- https://www.netmaker.io/resources/remote-workforce-security
- https://www.deloitte.com/uk/en/services/risk-advisory/perspectives/managing-the-digital-risks-of-a-remote-workforce.html
- https://www.lookout.com/blog/remote-work-security-risks

#### 3. AI-Powered Social Engineering
AI is allowing attackers to conduct more sophisticated social engineering attacks. Deepfake audio and video, in particular, make it easier for threat actors to impersonate executives and other high-ranking officials. An Attacker can use deepfake audio to impersonate the CEO of a company, to instruct a finance department employee to approve a fraudulent fund transfer.
#### Recommendations:
- Require multi-step verification for any high-stakes financial or operational requests.
- Train employees to recognize indicators of deepfake audio or video, such as inconsistencies in speech.
  #### Reference
- https://www.weforum.org/stories/2024/10/ai-agents-in-cybersecurity-the-augmented-risks-we-all-need-to-know-about
- https://www.forbes.com/councils/forbestechcouncil/2023/05/26/how-ai-is-changing-social-engineering-forever


#### 4. Ransomware Escalation
Ransomware remains a major threat, with attackers increasingly targeting critical infrastructure. Energy providers are prime targets due to the high operational costs of disruptions.
#### Recommendations:
- Regularly back up systems and test the integrity of these backups.
- Run ransomware response simulations to prepare employees and management for quick, coordinated action.
 #### Reference
- https://flashpoint.io/blog/the-anatomy-of-a-ransomware-attack
- https://www.proofpoint.com/uk/blog/email-and-cloud-threats/eight-stages-of-the-ransomware-attack-chain

#### 5. Zero Trust Architecture
As traditional network perimeters fade, Zero Trust models are increasingly being adopted to reduce the risk of lateral movement within networks during a breach.
#### Recommendations:
- Identify critical assets and enforce strict access controls for these resources.
- Regularly audit and update permissions to ensure employees have only the necessary level of access.

 #### Reference
- https://www.microsoft.com/en-us/security/business/security-101/what-is-zero-trust-architecture
- https://www.nist.gov/publications/zero-trust-architecture

#### 6. Outcome-Driven Cybersecurity Metrics
As cybersecurity budgets grow, outcome-driven metrics help teams quantify and communicate the impact of their efforts. Linking security investments to business outcomes can also aid in prioritizing spending. After a breach, security can used outcome-based metrics to show how its investment in cybersecurity directly prevented revenue loss, helping secure additional budget for further improvements.
#### Recommendations:
- Align cybersecurity metrics with business goals and communicate these to executives.
- Track key metrics, such as incident response times, to measure the impact of security investments.
 #### Reference
 - https://www.gartner.com/en/documents/3980892
 - https://truefort.com/cybersecurity-outcome-driven-metrics
 - https://www.micromindercs.com/blog/the-shift-towards-outcome-driven-cyber-security-metrics

#### 7. Third-Party and Supply Chain Risks
As supply chains grow increasingly interconnected, attackers often target third-party vendors with weaker security. Energy providers rely on an array of suppliers, making them vulnerable to third-party risks.
#### Recommendations:
- Conduct regular third-party risk assessments and require vendors to adhere to security best practices.
- Implement monitoring solutions to track any suspicious third-party access.

#### Reference
- https://panorays.com/blog/managing-third-party-risks-global-supply-chain/
- https://blog.riskimmune.com/supply-chain-risk-management-vs-third-party-risk-management-understanding-the-differences/


#### 8. Regulatory Landscape Shifts
With evolving data privacy laws, organisations must regularly update their security and data protection practices to stay compliant.
#### Recommendations:
- Stay informed of changes in data privacy laws and adjust security policies accordingly.
- Regularly audit data practices to ensure compliance with all applicable regulations.

### Conclusion
These trends highlight the need for cybersecurity professionals to adopt a proactive, layered approach to safeguarding their organizations. By focusing on the unique challenges posed by each of these trends, teams can better anticipate new tactics from adversaries and mitigate risks more effectively. Staying informed and prepared is key to navigating an ever-evolving threat landscape.



