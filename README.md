

### **Attack Plan: "Non-Stop Social Chaos"**
**Core Idea:** Use **social engineering** to amplify disruption during each attack.

#### **Attack 1 (0–15 mins): Phishing + Ransomware**
- **Primary Attack:**
  - **Phishing Email:** Fake "COVID-19 Protocol Update" with ransomware (LockBit).
  - **Goal:** Encrypt DPI systems (patient records).
- **Social Engineering Disturbances:**
  1. **Fake IT Support Calls:**
     - Team members call helpdesk posing as doctors: *"I can’t access patient records—this is life-or-death!"*
     - **Goal:** Overload helpdesk, delay ransomware detection.
  2. **Fake Patient Complaints:**
     - Call front desk pretending to be patients: *"My appointment was canceled—why?!"*
     - **Goal:** Distract administrative staff.
  3. **Social Media Misinformation:**
     - Post fake "data breach" on Twitter: *"@HopitalSaintLaurent hacked—patient data leaked!"*
     - **Goal:** Force PR team to respond.

---

#### **Attack 2 (15–30 mins): Insider Threat + Data Sabotage**
- **Primary Attack:**
  - Use **stolen admin credentials** to modify/delete patient records (e.g., change prescriptions).
  - Disable backups.
- **Social Engineering Disturbances:**
  1. **Fake Legal Threats:**
     - Email compliance team: *"You’re violating RGPD—we’re suing!"*
     - **Goal:** Force legal team to investigate.
  2. **Vendor Impersonation:**
     - Call IT posing as the SaaS vendor: *"Your system has a critical vulnerability—let us in to fix it!"*
     - **Goal:** Trick staff into granting access.
  3. **Internal Chat Spam:**
     - Flood Slack/Teams with fake "emergency updates" (e.g., *"Server crash imminent!"*).
     - **Goal:** Slow internal communications.

---

#### **Attack 3 (30–45 mins): OT Sabotage + Environmental Disruption**
- **Primary Attack:**
  - Exploit OT network to override HVAC (make rooms too hot/cold).
  - Disable non-critical medical devices.
- **Social Engineering Disturbances:**
  1. **Fake Maintenance Calls:**
     - Call facilities team: *"The HVAC system is failing—send someone NOW!"*
     - **Goal:** Divert OT teams from real issues.
  2. **Fake Patient Emergencies:**
     - Call nurses: *"A patient in Room 203 is having a heart attack!"* (false alarm).
     - **Goal:** Waste medical staff time.
  3. **Media Calls:**
     - Fake reporters call PR: *"Is the hospital under cyberattack? Comment now!"*
     - **Goal:** Force public relations chaos.

---

#### **Attack 4 (45–60 mins): DDoS + Credential Stuffing**
- **Primary Attack:**
  - **DDoS** hospital website (block patient portals).
  - **Brute-force VPN/SSO** (lock out staff).
- **Social Engineering Disturbances:**
  1. **Fake Ransomware Notes:**
     - Send decoy ransom demands to random departments (e.g., *"Pay 10 BTC or we leak data!"*).
     - **Goal:** Create panic, waste time.
  2. **CEO Fraud:**
     - Email finance team: *"CEO here—transfer funds to this account immediately!"*
     - **Goal:** Distract financial teams.
  3. **Fake Power Outage Reports:**
     - Call facilities: *"The entire building lost power—what’s happening?!"*
     - **Goal:** Trigger unnecessary investigations.

---

### **Social Engineering Tools**
| **Tactic**               | **Tools**                          |
|--------------------------|-----------------------------------|
| Fake Calls               | Burner phones, VoIP               |
| Phishing Emails          | GoPhish, Evilginx                 |
| Fake Social Media Posts  | Twitter bots, Reddit throwaways  |
| Vendor Impersonation     | Caller ID spoofing                |

---

### **Why This Works**
- **Human-Centric Distractions:** Forces defenders to **react emotionally** (e.g., patient emergencies, legal threats).
- **Layered Pressure:** Combines **technical attacks** (ransomware) with **human distractions** (fake calls).
- **Realistic for 1 Hour:** Each disturbance is **quick to execute** but **hard to ignore**.

