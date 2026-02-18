# Information Security Risk Assessment Template

**Identify and manage security risks for your trades business**

---

## 🎯 What Is a Risk Assessment?

A risk assessment helps you:
- Identify what could go wrong with your data and systems
- Understand how likely each risk is
- Decide which risks to address first
- Document your security decisions

**You need this for:**
- Cyber Essentials certification
- GDPR compliance (showing appropriate security)
- Insurance requirements
- Your own peace of mind

---

## 📋 How to Use This Template

**Step 1:** Identify your assets (what needs protecting)  
**Step 2:** Identify threats (what could go wrong)  
**Step 3:** Assess likelihood and impact  
**Step 4:** Calculate risk level  
**Step 5:** Decide on controls  
**Step 6:** Review regularly

**Time needed:** 2-4 hours for initial assessment, 1 hour for annual review

---

## Part 1: Asset Inventory

**List everything that holds or processes business data:**

### Business Systems

| Asset | What It Holds | Owner | Location |
|-------|--------------|-------|----------|
| Email (Microsoft 365) | Customer communications, quotes | James | Cloud |
| Xero | Customer invoices, payment details | Sarah | Cloud |
| Tradify | Job schedules, customer addresses | Engineers | Cloud |
| OneDrive | Gas certificates, employee records | Sarah | Cloud |
| Company phones (6) | Customer contacts, job photos | Engineers | Mobile |
| Office laptops (2) | All business data | James/Sarah | Office |
| BT router | Network access | Office | Office |
| Paper files | Old records, employee contracts | Sarah | Filing cabinet |

**Add rows for your specific systems**

### Critical Data

| Data Type | Where Stored | Sensitivity | Volume |
|-----------|--------------|-------------|--------|
| Customer names/addresses | Tradify, Xero | Medium | ~500 records |
| Payment details | Xero (encrypted) | High | ~500 records |
| Gas certificates | OneDrive | High (legal req) | ~200/year |
| Employee records | OneDrive, paper | High | 8 employees |
| Bank details | Online banking | Critical | 1 account |
| Email communications | Microsoft 365 | Medium | Thousands |

**Sensitivity levels:**
- **Critical:** Business can't operate without it, severe consequences if lost
- **High:** Significant impact, legal requirements, customer trust
- **Medium:** Important but replaceable, moderate impact
- **Low:** Easily recreated, minimal impact

---

## Part 2: Threat Identification

**For each asset, what could go wrong?**

### Common Threats for Trades Businesses

| Threat | Description | Typical Target |
|--------|-------------|----------------|
| **Lost/stolen device** | Phone or laptop lost/stolen with customer data | Mobile phones, laptops |
| **Phishing** | Fake email tricks someone into revealing passwords | Email accounts |
| **Ransomware** | Malware encrypts data, demands payment | Computers, servers |
| **Password attack** | Weak password guessed or stolen | All systems |
| **Email compromise** | Hacker gains access to email account | Email |
| **Invoice fraud** | Fake email changing supplier payment details | Email, banking |
| **Malware** | Virus or spyware infects devices | Computers, phones |
| **Unauthorized access** | Ex-employee or unauthorized person accesses systems | All systems |
| **Data breach** | Customer data exposed or leaked | All customer data |
| **Hardware failure** | Computer dies, taking data with it | Computers, servers |
| **Fire/flood/theft** | Physical damage to office/equipment | Office, paper files |
| **Human error** | Accidental deletion, sent to wrong person | All data |
| **Insider threat** | Malicious employee steals/deletes data | All systems |
| **Supply chain** | Supplier/subcontractor compromised | Shared systems |

---

## Part 3: Risk Assessment Matrix

### Likelihood Scale

**5 - Very Likely:** Expected to happen, happens regularly  
**4 - Likely:** Will probably happen in next 12 months  
**3 - Possible:** Might happen in next 2-3 years  
**2 - Unlikely:** Possible but not expected  
**1 - Rare:** Almost never happens, very unlikely

### Impact Scale

**5 - Catastrophic:** Business closure, major legal issues, severe financial loss  
**4 - Major:** Significant financial loss, serious reputation damage, major disruption  
**3 - Moderate:** Financial loss, reputation damage, disruption but recoverable  
**2 - Minor:** Small financial loss, temporary inconvenience  
**1 - Negligible:** No significant impact

### Risk Level Calculation

**Risk = Likelihood × Impact**

| Score | Risk Level | Action Required |
|-------|-----------|-----------------|
| 20-25 | **Critical** | Immediate action, cannot operate without addressing |
| 15-19 | **High** | Address within 1 month, priority action |
| 10-14 | **Medium** | Address within 3 months, significant concern |
| 5-9 | **Low** | Address within 6 months, monitor |
| 1-4 | **Very Low** | Accept or address when convenient |

---

## Part 4: Risk Register Template

**Complete this for each significant risk:**

### Risk #1: Lost Company Phone with Customer Data

| Field | Details |
|-------|---------|
| **Asset Affected** | Company Samsung phones (6 devices) |
| **Threat** | Phone lost or stolen with customer data accessible |
| **Likelihood** | 4 (Likely - engineers work at multiple sites daily) |
| **Impact** | 4 (Major - GDPR breach, customer trust, ICO fine) |
| **Risk Score** | 16 (High) |
| **Current Controls** | • Screen locks (6-digit PIN)  <br>• Find My Device enabled  <br>• Data also in Tradify (not just on phone) |
| **Residual Risk** | Medium (9) |
| **Additional Controls Needed** | • Remote wipe capability tested monthly  <br>• Staff training on reporting lost devices  <br>• Reduce local data storage (use cloud more) |
| **Action Owner** | Sarah |
| **Target Date** | End of month |
| **Status** | In progress |

---

### Risk #2: Email Account Compromise

| Field | Details |
|-------|---------|
| **Asset Affected** | Microsoft 365 email accounts (all staff) |
| **Threat** | Phishing attack or weak password leads to account compromise |
| **Likelihood** | 3 (Possible - phishing is common) |
| **Impact** | 4 (Major - access to customer data, could send fake invoices) |
| **Risk Score** | 12 (Medium) |
| **Current Controls** | • MFA enabled on all accounts  <br>• Password manager in use  <br>• Spam filtering enabled |
| **Residual Risk** | Low (6) |
| **Additional Controls Needed** | • Annual phishing awareness training  <br>• Review suspicious emails regularly |
| **Action Owner** | James |
| **Target Date** | Quarterly training |
| **Status** | Complete |

---

### Risk #3: Ransomware Infection

| Field | Details |
|-------|---------|
| **Asset Affected** | Office laptops, customer data, gas certificates |
| **Threat** | Ransomware encrypts data, demands payment to decrypt |
| **Likelihood** | 2 (Unlikely - but increasing trend) |
| **Impact** | 5 (Catastrophic - lose all data, can't operate, customer records gone) |
| **Risk Score** | 10 (Medium) |
| **Current Controls** | • Antivirus on laptops (Windows Defender)  <br>• Daily backups to OneDrive  <br>• MFA on critical systems  <br>• Phishing awareness |
| **Residual Risk** | Low (4) |
| **Additional Controls Needed** | • Test restore from backup quarterly  <br>• Offline backup for critical data  <br>• Incident response plan tested |
| **Action Owner** | Sarah |
| **Target Date** | Next month |
| **Status** | Planned |

---

### Risk #4: Invoice Fraud (Fake Supplier Payment Change)

| Field | Details |
|-------|---------|
| **Asset Affected** | Business bank account, supplier relationships |
| **Threat** | Fake email pretending to be supplier with new bank details |
| **Likelihood** | 3 (Possible - common scam targeting trades) |
| **Impact** | 4 (Major - lose payment, strain supplier relationship) |
| **Risk Score** | 12 (Medium) |
| **Current Controls** | • Verbal confirmation of new bank details  <br>• MFA on banking  <br>• Limited number of people can make payments |
| **Residual Risk** | Low (6) |
| **Additional Controls Needed** | • Written procedure for payment changes  <br>• Staff training on invoice fraud  <br>• Small test payment first for new details |
| **Action Owner** | Sarah |
| **Target Date** | This week |
| **Status** | Complete |

---

### Risk #5: No Backups / Backup Failure

| Field | Details |
|-------|---------|
| **Asset Affected** | All business data |
| **Threat** | Hardware failure, ransomware, accidental deletion with no backup |
| **Likelihood** | 2 (Unlikely - but consequences severe) |
| **Impact** | 5 (Catastrophic - permanent data loss) |
| **Risk Score** | 10 (Medium) |
| **Current Controls** | • OneDrive sync for critical files  <br>• Xero/Tradify cloud-based (provider backups)  <br>• Email in Microsoft 365 (cloud) |
| **Residual Risk** | Low (4) |
| **Additional Controls Needed** | • Test restore quarterly  <br>• Verify OneDrive syncing monthly  <br>• Document what's backed up vs. what isn't |
| **Action Owner** | Sarah |
| **Target Date** | Monthly checks |
| **Status** | Ongoing |

---

### Risk #6: Ex-Employee Access Not Revoked

| Field | Details |
|-------|---------|
| **Asset Affected** | All systems |
| **Threat** | Former employee still has login access, could access/delete/steal data |
| **Likelihood** | 3 (Possible - we've had staff leave) |
| **Impact** | 3 (Moderate - data breach, sabotage potential) |
| **Risk Score** | 9 (Low) |
| **Current Controls** | • Passwords changed when someone leaves  <br>• Individual accounts (not shared logins) |
| **Residual Risk** | Very Low (3) |
| **Additional Controls Needed** | • Checklist for employee departure  <br>• Quarterly access review  <br>• MFA makes stolen passwords less useful |
| **Action Owner** | James |
| **Target Date** | Create checklist this month |
| **Status** | Planned |

---

## Part 5: Blank Risk Assessment Template

**Use this template to assess other risks:**

### Risk #___: [Risk Name]

| Field | Details |
|-------|---------|
| **Asset Affected** |  |
| **Threat** |  |
| **Likelihood** | ___ ([Rare/Unlikely/Possible/Likely/Very Likely]) |
| **Impact** | ___ ([Negligible/Minor/Moderate/Major/Catastrophic]) |
| **Risk Score** | ___ (Likelihood × Impact) |
| **Current Controls** | •  <br>•  <br>• |
| **Residual Risk** | ___ ([After controls applied]) |
| **Additional Controls Needed** | •  <br>•  |
| **Action Owner** |  |
| **Target Date** |  |
| **Status** | [Not started / Planned / In progress / Complete] |

---

## Part 6: Risk Treatment Decisions

**For each risk, choose one of four options:**

### 1. Mitigate (Reduce)
**Apply controls to reduce likelihood or impact**

Example: Install antivirus to reduce malware risk

### 2. Accept
**Acknowledge risk but take no further action (usually low risks)**

Example: Accept risk of meteor strike on office (very unlikely, can't prevent)

### 3. Transfer
**Shift risk to another party (insurance, outsourcing)**

Example: Cyber insurance covers financial loss from data breach

### 4. Avoid
**Stop activity that creates the risk**

Example: Stop collecting payment card details, use Stripe instead

**Most trades business risks = Mitigate** (apply security controls)

---

## Part 7: Action Plan

**Summary of all actions needed:**

| Priority | Risk | Action | Owner | Due Date | Status |
|----------|------|--------|-------|----------|--------|
| High | Lost phone | Test remote wipe monthly | Sarah | End of month | In progress |
| High | Email compromise | Phishing training | James | Next quarter | Planned |
| Medium | Ransomware | Test backup restore | Sarah | Next month | Planned |
| Medium | Invoice fraud | Document payment procedure | Sarah | This week | Complete |
| Low | Ex-employee access | Create departure checklist | James | This month | Planned |

**Update this quarterly as you complete actions and identify new risks.**

---

## Part 8: Risk Assessment Review Schedule

**When to review:**

**Annual full review:**
- Reassess all risks
- Update likelihood/impact based on changes
- Identify new risks
- Document in risk register

**Quarterly quick review:**
- Check action plan progress
- Add any new significant risks
- Update completed actions

**After any significant change:**
- New system implemented
- Staff changes
- Business expansion
- After any security incident

**After an incident:**
- Add to risk register
- Document what happened
- Update controls
- Adjust likelihood/impact

---

## ✅ Implementation Checklist

### Initial Setup (Week 1)
- [ ] List all assets (systems, data)
- [ ] Identify main threats
- [ ] Complete risk register for top 5-10 risks
- [ ] Calculate risk scores
- [ ] Prioritize actions

### Actions (Weeks 2-4)
- [ ] Implement high-priority controls
- [ ] Assign owners for each risk
- [ ] Set target dates
- [ ] Track progress

### Ongoing Management
- [ ] Monthly: Check action plan progress
- [ ] Quarterly: Quick review of risk register
- [ ] Annually: Full risk assessment review
- [ ] After incidents: Update risk register

---

## 📊 NorthWest Heating Example

**Their top 5 risks identified:**
1. Lost company phone (High - 16)
2. Email compromise (Medium - 12)
3. Invoice fraud (Medium - 12)
4. Ransomware (Medium - 10)
5. No backup / backup failure (Medium - 10)

**Actions taken:**
- Set up remote wipe on all phones
- Enabled MFA on all accounts
- Created invoice verification procedure
- Tested OneDrive backup restore
- Quarterly access review scheduled

**Time invested:**
- Initial assessment: 3 hours (James and Sarah together)
- Implementing controls: Already done via 30-Day Quick Start
- Quarterly review: 30 minutes
- Annual review: 1-2 hours

**Result:** Clear understanding of risks, documented decisions, evidence for Cyber Essentials and customer questions

---

## 🔗 Related Resources

- [Cyber Essentials Checklist](../checklists/cyber-essentials-checklist.md) - implements controls to reduce risks
- [30-Day Quick Start](30-day-quick-start.md) - addresses most high risks
- [All Policies](../policies/) - document your controls

---

**Risk assessment isn't about achieving zero risk (impossible). It's about understanding your risks and making informed decisions about which ones to address first.**
