# Format	alignment
## 1.1 Why Reporting Matters

**English Definition:**
Reporting in penetration testing is the process of documenting findings, risks, and recommendations in a structured way to communicate results clearly, support decision-making, provide evidence, and guide security improvements.

 **Urdu:**
Penetration testing me reporting ka matlab hai findings, risks aur recommendations ko ek organized tariqe se likhna, taki results clear communicate ho saken, management ko decision-making me help mile, future ke liye record banay, aur security improve karne ka direction mile.

### 1.2 Best Practices for Penetration Test Documentation
#### 1. Accuracy

**English:**
Accuracy means presenting correct and exact details about vulnerabilities and exploits without assumptions.

**Urdu :**
Accuracy ka matlab hai vulnerabilities aur exploits ki bilkul sahi details dena, bina guess work ke.

#### 2. Clarity

**English:**
Clarity means writing in simple and understandable language so both technical and non-technical audiences can understand the findings.

**Urdu:**
Clarity ka matlab hai simple aur asaan language use karna, taki technical aur non-technical dono log findings samajh saken.

#### 3. Confidentiality

**English :**
Confidentiality means protecting sensitive information in the report and sharing it only with authorized people.

**Urdu:**
Confidentiality ka matlab hai sensitive data ko secure rakhna aur report sirf authorized logon ke sath share karna.

#### 4. Structure

**English:**
Structure means organizing the report in a professional flow, usually including Executive Summary, Methodology, Findings, Recommendations, and Conclusion.

**Urdu:**
Structure ka matlab hai report ko ek professional flow me organize karna, jaise Executive Summary, Methodology, Findings, Recommendations, aur Conclusion.



# 2. Risk Scoring & Vulnerability

**English:**
Risk scoring and vulnerability assessment is the process of measuring the severity of security weaknesses based on their impact, exploitability, and potential harm to the system.

**Urdu Definition:**
Risk scoring aur vulnerability assessment ka matlab hai system me security weaknesses ki severity ko measure karna, unke impact, exploit hone ki possibility, aur potential damage ke base par.

### 2.1 Common Risk Scoring Models
#### 1. CVSS (Common Vulnerability Scoring System)

**English:**
CVSS provides a numerical score (0.0 – 10.0) to indicate the severity of a vulnerability, categorized as Critical, High, Medium, or Low.

**Urdu:**
CVSS ek scoring system hai jo vulnerabilities ko 0 se 10 tak score deta hai, aur severity ko Critical, High, Medium ya Low categories me divide karta hai.

#### 2. DREAD Model

**English:**
DREAD is a model that evaluates risk based on: Damage, Reproducibility, Exploitability, Affected Users, and Discoverability.

 **Urdu:**
DREAD model risk ko evaluate karta hai 5 factors par: Damage, Reproducibility, Exploitability, Affected Users, aur Discoverability.

#### 3. STRIDE Model

**English:**
STRIDE is a threat modeling framework that categorizes threats into: Spoofing, Tampering, Repudiation, Information Disclosure, Denial of Service, Elevation of Privilege.

**Urdu:**
STRIDE ek framework hai jo threats ko 6 categories me divide karta hai: Spoofing, Tampering, Repudiation, Information Disclosure, Denial of Service, aur Elevation of Privilege.

#### 4. OWASP Risk Rating

**English:**
OWASP Risk Rating helps evaluate web application risks by measuring likelihood (how easily it can happen) and impact (damage if it happens).

**Urdu:**
OWASP Risk Rating web application risks ko evaluate karta hai likelihood (kitna asaan hai exploit karna) aur impact (damage kitna hoga) ke base par.

#### 2.2 CVSS Scoring Breakdown

**English Definition:**
CVSS divides risk into four main levels based on the score.

** Urdu:**
CVSS vulnerabilities ko 4 main severity levels me divide karta hai score ke base par.

### Severity Level --------	Score Range-----------	Explanation 
Critical -----------------	9.0 – 10.0-------------	Bohat dangerous vulnerability jo immediate fix zaroori hai.

High----------------	7.0 – 8.9	------------------Severe vulnerability jo system compromise kar sakti hai.

Medium-----------------	4.0 – 6.9	-------------------Moderate vulnerability jo exploit hone ke liye specific condition chahti hai.

Low	--------------------0.1 – 3.9-----------------	Minor issue jo kam damage karta hai, lekin fix karna phir bhi zaroori hai.
**Example:**

**English:**
A vulnerability in a web server allows remote code execution with no authentication. According to CVSS:

Attack Vector: Network

Attack Complexity: Low

Privileges Required: None

Impact: High

Final Score: 9.8 (Critical)

Roman Urdu:
Agar ek web server vulnerability remote code execution allow karti hai bina authentication ke, to CVSS ke hisaab se iska score 9.8 (Critical) hoga, aur isse turant fix karna zaroori hai.


