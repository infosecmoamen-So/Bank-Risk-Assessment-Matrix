# Commercial Bank: Cybersecurity Risk Register

## 📝 Analyst Notes: Threat Landscape
Considering the bank employs 120 staff members handling data for 2,200 accounts, human-centric vulnerabilities like Business Email Compromise are highly probable[cite: 5]. Furthermore, strict financial regulations necessitate robust technical controls; publicly accessible backups or poorly encrypted databases pose a catastrophic compliance and financial risk[cite: 5]. Geographically, the coastal location introduces an environmental risk to the supply chain (e.g., cash delivery delays due to hurricanes), directly threatening the bank's ability to meet daily Federal Reserve requirements[cite: 5].

---

## 🔢 Risk Scoring Matrix
* **Formula used:** `Likelihood × Severity = Priority Score`[cite: 5]
* **Likelihood Scale:** 1 (Rare), 2 (Likely), 3 (Certain)[cite: 5]
* **Severity Scale:** 1 (Low), 2 (Moderate), 3 (Catastrophic)[cite: 5]

| Asset | Risk Category | Vulnerability Description | Likelihood (1-3) | Severity (1-3) | Priority Score (1-9) |
| :--- | :--- | :--- | :---: | :---: | :---: |
| **Funds / Data** | **Financial records leak** | A database server of backed-up data is publicly accessible[cite: 5]. | **3** | **3** | **9 (Critical)** |
| **Funds / Data** | **Business email compromise** | An employee is tricked into sharing confidential information[cite: 5]. | **3** | **2** | **6 (High)** |
| **Funds / Data** | **Compromised user database** | Customer data is poorly encrypted[cite: 5]. | **2** | **3** | **6 (High)** |
| **Funds** | **Supply chain disruption** | Delivery delays of cash due to natural disasters (coastal area)[cite: 5]. | **1** | **3** | **3 (Medium)** |
| **Funds** | **Theft** | The bank's safe is left unlocked[cite: 5]. | **1** | **3** | **3 (Medium)** |

---

## 🔍 Priority Analysis & Justification
1. **Financial Records Leak (Score: 9):** Rated highest priority. A publicly accessible backup server guarantees discovery by malicious actors (Likelihood: 3), leading to catastrophic regulatory fines and loss of consumer trust (Severity: 3)[cite: 5].
2. **Business Email Compromise (Score: 6):** With 120 employees, social engineering is highly likely (Likelihood: 3), and can lead to moderate/severe financial unauthorized access (Severity: 2)[cite: 5].
3. **Theft (Score: 3):** While leaving a safe unlocked is a catastrophic failure (Severity: 3), the likelihood is minimal (Likelihood: 1) due to the bank's location in a low-crime area and standard operational physical security[cite: 5].
