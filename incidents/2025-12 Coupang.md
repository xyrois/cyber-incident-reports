# Cyber Incident Report: Coupang Massive Customer Data Breach (Dec 2, 2025)

## Overview
In late 2025, South Korean e-commerce giant Coupang, Inc.—often referred to as the “Amazon of South Korea”—disclosed a massive data breach affecting approximately 33.7 million customer accounts. The incident was traced to unauthorized system access enabled by an authentication or private encryption key that remained active after a former employee left the company. The breach went undetected for several months and has since triggered government investigations, political response at the highest levels, and potential large-scale legal action.

---

## Victim Organization
- **Name:** Coupang, Inc.  
- **Sector:** E-commerce / Technology  
- **Role:** South Korea’s largest online retail platform, providing marketplace, logistics, and delivery services to tens of millions of customers

---

## Facts (What Happened?)
Coupang confirmed that attackers gained unauthorized access to its systems using a long-lived authentication or private encryption key associated with a former employee. The key was not revoked after the employee’s departure, allowing access from overseas servers for months before detection. 

The exposed data includes customer names, email addresses, phone numbers, physical addresses, and portions of order history. Coupang stated that payment information, credit card data, login credentials, and passwords were not compromised. Initial detection suggested a limited number of affected accounts, but subsequent investigation revealed that approximately 33.7 million customer accounts were impacted.

---

## Timeline
- **June 24, 2025:** Unauthorized access to Coupang systems believed to begin via overseas servers using a still-valid authentication key  
- **November 18, 2025:** Coupang detects suspicious activity and reports the incident to Korean authorities, including the Korea Internet & Security Agency (KISA)  
- **November 29–30, 2025:** Coupang publicly discloses the breach affecting 33.7 million accounts; CEO issues a public apology; South Korean government convenes an emergency ministerial meeting  
- **December 1, 2025:** Police investigation publicly confirmed; more than 10,000 citizens express interest in a class-action lawsuit  
- **December 2, 2025:** South Korea’s president calls for tougher penalties and stronger data-protection laws in response to the breach

---

## Motive
No ransomware demand has been publicly reported. Current reporting points toward **insider misuse or negligence**, with a former engineer suspected of using a still-valid private key or token after leaving the company. Likely motives include financial gain through the sale or abuse of personal data for phishing, identity theft, or fraud, as well as potential leverage related to employment or legal disputes.

---

## Damages & Impact
- **Data impact:** Personal information of approximately 33.7 million users exposed  
- **Customer risk:** Increased likelihood of phishing, social engineering, and fraud using accurate personal and order-related data; KISA has issued advisories to affected users  
- **Financial impact:** Coupang’s U.S.-listed stock fell roughly 9% in pre-market trading following disclosure; potential class-action claims reportedly seek at least 100,000 won (~$68) per claimant  
- **Operational/reputational impact:** Significant reputational damage in South Korea’s largest e-commerce market; heightened scrutiny of Coupang’s security practices, internal controls, and governance

---

## Attribution
- **Primary suspect:** Former Coupang employee with access to authentication systems  
- **Method:** Use of a private key or authentication token that was never revoked after employment termination  
- **Attribution status:** Under active investigation by South Korean law enforcement; no evidence of external cybercriminal group involvement disclosed to date

---

## Analysis & Opinion
This breach is a textbook example of how fundamental security hygiene failures can undermine even highly sophisticated technology companies. Failing to revoke a powerful authentication key after an employee’s departure represents a basic access control lapse. The fact that unauthorized access persisted for roughly five months suggests weaknesses in monitoring, logging, and key management. Beyond immediate financial and reputational harm, this incident is likely to accelerate stricter regulatory enforcement and harsher penalties for data protection failures in South Korea. It underscores the critical importance of rigorous identity lifecycle management, least-privilege access, and continuous monitoring in large-scale digital platforms.

---

## Sources
- Reuters — South Korean Police Probe Massive Data Leak at Coupang  
- Reuters — South Korea’s President Calls for Tougher Penalties After Coupang Data Breach  
- TechRadar — South Korean E-commerce Giant Coupang Suffers Huge Data Breach
