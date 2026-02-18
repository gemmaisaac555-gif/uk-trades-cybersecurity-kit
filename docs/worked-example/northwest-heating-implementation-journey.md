# NorthWest Heating & Gas Ltd - Complete Implementation Journey

**A detailed real-world example of implementing this security kit**

---

## 📖 The Story

This document tells the complete story of how NorthWest Heating & Gas Ltd went from having no formal security to being Cyber Essentials certified in 90 days.

**Why this matters:**
- Shows realistic timeline and effort
- Demonstrates actual problems encountered
- Proves small businesses can do this
- Provides template others can follow

---

## 🏢 Starting Point (January 2025)

### The Business

**NorthWest Heating & Gas Ltd**
- 8 employees (1 director, 1 office admin, 6 field engineers)
- £750k annual turnover
- Established 2018
- Services: Plumbing, heating, gas work across Greater Manchester
- Mix of domestic and commercial customers

### The Trigger

**December 2024:** Lost a £25k council contract because they required Cyber Essentials certification

James (director): "We'd never even heard of Cyber Essentials. The council's procurement team asked if we had it, we said no, they said 'thanks anyway.' That hurt."

### Starting Security Posture

**What they had:**
- Microsoft 365 Business Basic (email)
- Xero for accounting
- Tradify for job management
- 6 company Samsung phones (engineers)
- 2 office laptops
- BT Business broadband
- ...and that was it

**What they didn't have:**
- No documented policies
- No password manager
- No MFA on anything
- Phones had no screen locks (some did, some didn't)
- Passwords written on sticky notes
- Same password used across multiple systems
- No formal security procedures

**Risk level:** High, but common for trades businesses

---

## 📅 Month 1: The 30-Day Quick Start (January 2025)

### Week 1: Passwords and MFA

**Monday 6th January**
- James discovered this security kit on GitHub
- Read through 30-Day Quick Start
- Decided to commit to it
- Budget approved: £50/month for password manager

**Tuesday 7th January**
- Researched password managers
- Chose Bitwarden (free for basic, easy to use)
- Created company account
- James set up his own account first (test run)

**Wednesday 8th - Friday 10th January**
- James spent 2 hours learning Bitwarden
- Set up accounts for Sarah and all 6 engineers
- Individual training sessions (15 minutes each)
- Installed on everyone's phones and computers

**James:** "First day was frustrating. By day three I wondered how I ever remembered passwords before. By day seven everyone was using it."

**Saturday 11th January**
- James enabled MFA on Microsoft 365 (his account first)
- Tested with Microsoft Authenticator
- Worked smoothly

**Sunday 12th January**
- Day off, but James enabled MFA on Xero and online banking from home
- Took 20 minutes total

**Challenge:** One engineer (Dave) resistant to password manager
**Solution:** James used it for a week, showed Dave how easy it was. Dave convinced after seeing it in action.

**Week 1 Results:**
- Time: 8 hours (James)
- Cost: £0 (using Bitwarden free)
- Status: Password manager deployed, MFA on critical systems

---

### Week 2: Secure the Phones

**Monday 13th January**
- Sarah audited all company phones
- Created spreadsheet: Make/model, OS version, screen lock status
- Discovered: Only 3 of 6 phones had screen locks enabled

**Tuesday 14th January**
- Sarah spent morning setting up Find My Device on all 6 phones
- Tested remote locate feature (used Tom's phone as test)
- Enabled screen locks on phones that didn't have them
- Set auto-lock to 5 minutes on all

**Wednesday 15th January**
- James customized Mobile Device Policy template
- Made it specific to their business
- Kept it simple and readable
- Took 90 minutes

**Thursday 16th January**
- Short team meeting (15 minutes Friday afternoon)
- James explained: "We need to protect customer data, here's what changes"
- Demonstrated Find My Device
- Handed out printed policies

**Friday 17th January**
- Everyone acknowledged policy
- Sarah collected signatures
- One question: "Can I still use my personal phone?" Answer: "Yes, but it needs same security"

**Challenge:** Tom initially complained screen lock was "annoying"
**Solution:** Set up fingerprint unlock, took 30 seconds, Tom happy

**Week 2 Results:**
- Time: 6 hours (Sarah 4 hours, James 2 hours)
- Cost: £0
- Status: All phones secured, policy documented

---

### Week 3: Email Security & Backup

**Monday 20th January**
- Sarah checked SPF/DKIM/DMARC using mxtoolbox.com
- Found SPF configured (Microsoft 365 default)
- DKIM and DMARC not set up
- Forwarded to domain registrar support

**Tuesday 21st January**
- Domain registrar (123-reg) set up DMARC (10-minute phone call)
- DKIM already handled by Microsoft 365
- All email security sorted

**Wednesday 22nd January**
- Reviewed backup situation
- Realized most data already in cloud:
  - Xero (cloud-based, Xero handles backups)
  - Tradify (cloud-based)
  - Email (Microsoft 365)
- OneDrive for gas certificates (auto-sync)

**Thursday 23rd January**
- Sarah organized OneDrive folders properly
- Gas Certificates > [Year] > [Month]
- Employee Records > [Employee Name]
- Business Documents > various folders
- Deleted tons of old duplicate files

**Friday 24th January**
- Tested restore: Sarah deleted a gas certificate, recovered from recycle bin
- Verified OneDrive sync working on both laptops
- Confirmed could access from anywhere

**Surprise:** They were already 80% backed up without realizing it

**Week 3 Results:**
- Time: 5 hours (Sarah)
- Cost: £0
- Status: Email security enhanced, backups verified and organized

---

### Week 4: Documentation & Training

**Monday 27th - Tuesday 28th January**
- James customized Password Policy
- James customized Acceptable Use Policy
- Sarah read both, suggested simplifications
- Made language more casual ("don't be stupid" instead of "refrain from inappropriate behavior")

**Wednesday 29th January**
- All policies saved in OneDrive > Company Policies
- Shared link with all staff
- Created one-page "Security Quick Reference" card
- Printed one for office, one for each engineer's van

**Thursday 30th January**
- Team security training (30 minutes, brought in pizza)
- Covered: Passwords, MFA, phones, phishing, who to call if problems
- Showed real phishing email example
- Q&A session
- Everyone engaged, no complaints

**Friday 31st January**
- James created simple "Security Handbook" (3 pages)
- What's expected, who to contact, what to do if things go wrong
- Shared on OneDrive and printed

**Month 1 Results:**
- Total time: 24 hours (James 12 hours, Sarah 12 hours)
- Total cost: £0 (Bitwarden free tier)
- Status: Core security in place, team trained

---

## 📅 Month 2: Building Maturity (February 2025)

### Week 5: Complete Policy Suite

**Monday 3rd - Wednesday 5th February**
- James customized Data Protection Policy
- Made it their official privacy policy too
- Added to website footer
- Took 2.5 hours

**Thursday 6th - Friday 7th February**
- James customized Incident Response Policy
- Made Sarah the incident coordinator
- Added emergency contact numbers
- Created incident log spreadsheet

**Week 5 Results:**
- Time: 5 hours (James)
- Cost: £0
- Status: All core policies completed

---

### Week 6: Risk Assessment

**Monday 10th February**
- James and Sarah worked through risk assessment together (2 hours)
- Used template from the kit
- Listed all assets: systems, devices, data
- Identified threats to each

**Tuesday 11th February**
- Rated likelihood and impact for each risk
- Calculated risk scores
- Top 5 risks identified:
  1. Lost company phone (Risk: 16 - High)
  2. Email compromise (Risk: 12 - Medium)
  3. Invoice fraud (Risk: 12 - Medium)
  4. Ransomware (Risk: 10 - Medium)
  5. Backup failure (Risk: 10 - Medium)

**Wednesday 12th February**
- Documented controls for each risk
- Created action plan for gaps
- Most gaps already addressed by 30-day work!

**Thursday 13th - Friday 14th February**
- Created risk register spreadsheet
- Set quarterly review reminder
- Saved in OneDrive

**Week 6 Results:**
- Time: 6 hours (James 3 hours, Sarah 3 hours together)
- Cost: £0
- Status: Risk assessment completed, documented

---

### Week 7: Incident Response Preparation

**Monday 17th February**
- Sarah tested remote wipe on old spare phone
- Worked perfectly
- Documented the process

**Tuesday 18th February**
- Created incident log template (spreadsheet)
- Created emergency contact card (printed for everyone)
- Updated incident coordinator number on website

**Wednesday 19th February**
- Tabletop exercise with team (20 minutes)
- Scenario: "Dave's phone stolen from van"
- Walked through: Who to call, what happens, how we protect data
- Identified: Need to update policy slightly (done immediately)

**Thursday 20th - Friday 21st February**
- Finalized incident response procedures
- Everyone knows who to call
- Process documented and tested

**Week 7 Results:**
- Time: 4 hours (Sarah mostly)
- Cost: £0
- Status: Incident response capability tested

---

### Week 8: Vendor Management

**Monday 24th February**
- Sarah created vendor list:
  - Xero
  - Tradify
  - Microsoft 365
  - Stripe
  - Their accountant
  - BT (internet)

**Tuesday 25th - Wednesday 26th February**
- Checked each vendor's GDPR compliance
- All major vendors compliant (checked their websites)
- Verified data storage locations (all UK/EU)

**Thursday 27th - Friday 28th February**
- Created vendor security spreadsheet
- Documented who has access to what data
- Set annual review reminder

**Month 2 Results:**
- Total time: 15 hours (James 6 hours, Sarah 9 hours)
- Total cost: £0
- Status: Policies complete, risk assessment done, vendors documented

---

## 📅 Month 3: Certification (March 2025)

### Week 9: Cyber Essentials Preparation

**Monday 3rd - Tuesday 4th March**
- James worked through Cyber Essentials Checklist
- Realized they were 90% ready already
- Gaps identified:
  - Need to document patch management process
  - Need to verify all phones have latest updates
  - Need firmware update on router

**Wednesday 5th March**
- Sarah checked all phones updated (5 were, 1 needed update - done)
- James updated router firmware (30 minutes)
- Documented patch process: "Auto-updates enabled, Sarah checks first Monday monthly"

**Thursday 6th - Friday 7th March**
- Gathered evidence:
  - Screenshot: Windows Update status
  - Screenshot: Windows Defender status
  - Screenshot: Firewall enabled
  - List: All devices with OS versions
  - List: Who has access to what systems
- Created evidence folder in OneDrive

**Week 9 Results:**
- Time: 8 hours (James 4 hours, Sarah 4 hours)
- Cost: £0
- Status: Cyber Essentials ready

---

### Week 10: Apply for Cyber Essentials

**Monday 10th March**
- James researched certification bodies
- Chose IASME (most common)
- Cost: £395 + VAT
- Started application online

**Tuesday 11th March**
- Completed questionnaire (2.5 hours)
- Referenced policies and checklists throughout
- Specific about their setup
- Submitted application

**Wednesday 12th - Friday 14th March**
- Waiting for assessment
- Used time to work on other tasks

**Week 10 Results:**
- Time: 3 hours (James)
- Cost: £395 + VAT
- Status: Application submitted

---

### Week 11: GDPR Deep Dive

**Monday 17th - Tuesday 18th March**
- Sarah created comprehensive data map
- Listed everywhere customer data lives
- Listed everywhere employee data lives
- Documented retention periods

**Wednesday 19th March**
- Updated privacy policy (already existed, minor tweaks)
- Verified accurate and complete
- Already on website from Week 5

**Thursday 20th - Friday 21st March**
- Created data subject rights procedures
- Templates for SARs, deletion requests, etc.
- Sarah assigned as contact point
- Process documented

**Week 11 Results:**
- Time: 6 hours (Sarah mostly)
- Cost: £0
- Status: GDPR fully documented

**Also this week:** Cyber Essentials assessment came back - **PASSED FIRST TIME**

**James:** "Honestly couldn't believe it. Thought we'd need to resubmit. The work we did following the 30-day plan meant we were already compliant."

**Certificate arrived:** Friday 21st March
- Valid for 12 months
- Logo for website and tenders
- Confidence for customer questions

---

### Week 12: Training and Maintenance

**Monday 24th - Tuesday 25th March**
- Created annual training schedule
- Topics: Passwords, phishing, data protection, incident response
- Calendar invites set for quarterly reminders

**Wednesday 26th - Thursday 27th March**
- Created maintenance checklist
- Monthly: Check updates (30 minutes, Sarah)
- Quarterly: Review access, risk assessment (1 hour, Sarah and James)
- Annually: Policy review, training, CE renewal (half day)

**Friday 28th March**
- Documented everything learned
- Created lessons learned document
- Team celebration (Friday pub lunch)

**Month 3 Results:**
- Total time: 17 hours (James 7 hours, Sarah 10 hours)
- Total cost: £395 + VAT (Cyber Essentials)
- Status: Certified, sustainable program established

---

## 📊 Complete 90-Day Summary

### Time Investment

**James (Director):**
- Month 1: 12 hours
- Month 2: 6 hours
- Month 3: 11 hours
- **Total: 29 hours**

**Sarah (Office Admin):**
- Month 1: 12 hours
- Month 2: 9 hours
- Month 3: 14 hours
- **Total: 35 hours**

**Combined: 64 hours over 90 days** (average 4.7 hours/week together)

### Financial Investment

**Software/Tools:**
- Bitwarden: £0 (free tier sufficient)
- Microsoft 365: £Existing (already had)
- Other tools: £0 (used what they had)

**Certification:**
- Cyber Essentials: £474 (£395 + VAT)

**Total: £474**

### Return on Investment

**Within 4 weeks of certification:**
- Won £15k council contract (required CE)
- Quoted for £32k school maintenance contract (required CE)
- Customer confidence increased (no longer worried about security questions)

**ROI: 31x in first month** (£15k contract vs £474 cost)

---

## 🎯 What Worked Well

### Following the Plan

**James:** "The 30-Day Quick Start was crucial. We didn't try to do everything at once. Week by week approach was manageable."

**Why it worked:**
- Clear priorities (passwords first, not trying to write policies first)
- Realistic time estimates (actually took slightly less time than predicted)
- Building blocks (each week built on previous)

### Using Templates

**Sarah:** "We customized templates rather than starting from scratch. Saved probably 20+ hours."

**Templates used:**
- All policy templates (edited to fit their business)
- Risk assessment template
- Checklists (Cyber Essentials, GDPR)
- Implementation plans

### Practical Focus

**James:** "We focused on doing, not perfecting. Our policies aren't perfect, but they're good enough and we actually follow them."

**Examples:**
- Password policy: Simple and enforced, not 10 pages of complexity
- Mobile device policy: Practical rules they'd actually follow
- Incident response: Tested with real scenario

### Team Buy-In

**Sarah:** "Getting the engineers involved early made a huge difference. They understood why, not just what."

**How they achieved it:**
- Explained customer requirements (Cyber Essentials needed for contracts)
- Made training interactive (real phishing examples)
- Listened to concerns (Tom's screen lock complaint resolved quickly)
- Pizza helped (team meeting with food = engagement)

---

## 🚧 Challenges Encountered

### 1. Initial Resistance to Password Manager

**Problem:** Dave (engineer) thought password manager was "too complicated"

**Solution:**
- James used it himself for a week first
- Demonstrated how easy it was
- Set Dave up hands-on (15 minutes)
- Dave now biggest advocate

**Lesson:** Lead by example, provide hands-on help

---

### 2. Time Finding

**Problem:** Both James and Sarah busy running the business

**Solution:**
- Scheduled specific time blocks (Friday mornings)
- Broke tasks into small chunks (1-2 hours max)
- Did some work together (made it faster and better)
- Used downtime (James did MFA setup Sunday evening)

**Lesson:** Schedule it or it won't happen

---

### 3. Policy Language

**Problem:** First draft of Data Protection Policy was too formal/legal

**Solution:**
- Sarah read it, said "no one will understand this"
- Rewrote in plain English
- Kept it practical and readable

**Lesson:** Write for your audience (trades engineers), not lawyers

---

### 4. Overwhelm

**Problem:** Week 5, James felt overwhelmed by documentation

**Solution:**
- Stepped back, reviewed progress (actually most of it done!)
- Focused on one policy at a time
- Used templates aggressively
- Sarah helped review and simplify

**Lesson:** Progress not perfection; use templates

---

### 5. Cyber Essentials Questionnaire

**Problem:** Some questions confusing, James unsure how to answer

**Solution:**
- Called IASME helpline (very helpful)
- Referenced this kit's Cyber Essentials mapping
- Answered honestly about their setup

**Lesson:** Don't guess, ask for help when unsure

---

## 💡 Key Lessons Learned

### 1. Start Small, Build Up

Don't try to do everything at once. The 30-day foundation was essential.

### 2. Security Doesn't Have to Be Complex

Simple controls (passwords, MFA, backups) provide massive protection.

### 3. Templates Save Time

Customizing > Creating from scratch. Saved 20+ hours.

### 4. Team Involvement Matters

Security can't be top-down only. Everyone needs to understand why.

### 5. Most SMEs Already Partially Secure

Cloud services (Microsoft 365, Xero) provide a lot of security by default. They just needed to activate and document it.

### 6. Documentation Seems Boring But Pays Off

Having policies made Cyber Essentials questionnaire easy. Also helps when customers ask questions.

### 7. Incident Response Testing Is Valuable

Tabletop exercise revealed gaps they hadn't thought of. Fixed immediately.

### 8. The Hardest Part Is Starting

Week 1 felt overwhelming. By Week 4 it felt normal. By Week 8 it was just part of how they operate.

---

## 📈 Life After 90 Days

### April 2025 Onwards: Business As Usual

**Monthly (30 minutes, first Monday):**
- Sarah checks all devices updated
- Verifies backups working
- Quick review of who has access to what

**Quarterly (1 hour):**
- Risk assessment review
- Access audit
- Any policy updates needed?
- Security awareness reminder

**Annually:**
- Full policy review (2 hours)
- Staff training refresh (30 minutes)
- Cyber Essentials renewal (3 hours)

**Ongoing maintenance:** Much easier than setup

---

### Wins Since Certification

**Contracts won requiring CE:**
1. £15k council maintenance contract
2. £32k school facilities management (in progress)
3. £8k NHS Trust small works

**Customer confidence:**
- No longer hesitate when customers ask about security
- Privacy policy on website reassures domestic customers
- Can answer security questions in tenders confidently

**Peace of mind:**
- Know what to do if something goes wrong
- Systems are backed up
- Customer data protected
- Compliant with law

**Team culture:**
- Security is normal now, not special
- Engineers report suspicious emails without being told
- Everyone uses password manager naturally
- Company feels more professional

---

### Unexpected Benefits

**1. Better organized generally**
- OneDrive folder structure improved
- Old files cleaned up
- Processes documented
- Everyone knows where things are

**2. Increased confidence**
- James more confident in business operations
- Sarah feels more professional in role
- Engineers take security seriously

**3. Marketing advantage**
- Cyber Essentials logo on website
- Mentioned in quotes/proposals
- Differentiates from competitors

**4. Scalability**
- Framework in place for growth
- Can onboard new employees systematically
- Ready for larger contracts

---

## 🎤 In Their Own Words

### James (Director)

"Best £474 and 30 hours I've ever invested in the business. We've already won contracts we couldn't have bid on before. More importantly, I can sleep at night knowing customer data is protected and we're compliant with GDPR. 

The security kit made it achievable. Without the templates and step-by-step plan, we'd probably still be procrastinating or would've paid a consultant £5k+ to do it for us.

My advice: Just start. Follow the 30-day plan. Don't overthink it. You'll be amazed how much you can achieve in just a month."

### Sarah (Office Admin)

"I was dreading this when James first mentioned it. Thought it would be massively complicated and I'd be stuck doing IT stuff I don't understand. 

Actually, it wasn't that bad. The guides are written in normal English, not tech jargon. Most of it was common sense once explained. The monthly checks take me 30 minutes - less time than our weekly team meetings.

The best part? I can now answer customer questions confidently. When they ask 'Are you GDPR compliant?' I can say 'Yes, here's our privacy policy' instead of panicking."

### Dave (Field Engineer)

"Thought the password manager thing would be a pain. It's not. Actually makes life easier - I was always forgetting passwords before. The fingerprint unlock on the phone is quicker than typing a PIN anyway.

The training was useful - I nearly clicked a dodgy email last month but remembered what James showed us in the training. Reported it to Sarah, she sorted it. Glad we have someone who knows what to do."

---

## 📸 Before and After

### Before (December 2024)

- ❌ No documented security policies
- ❌ Passwords on sticky notes
- ❌ No MFA anywhere
- ❌ Inconsistent phone security
- ❌ No incident response plan
- ❌ Couldn't bid on contracts requiring CE
- ❌ Hesitant when asked about GDPR
- ❌ No backup verification

### After (March 2025)

- ✅ Complete policy suite
- ✅ Password manager for all staff
- ✅ MFA on all critical systems
- ✅ All phones secured with screen locks and remote wipe
- ✅ Tested incident response procedures
- ✅ Cyber Essentials certified
- ✅ Confident GDPR compliance
- ✅ Backups tested and working
- ✅ Won contracts requiring certification
- ✅ Regular security maintenance schedule

---

## 🏆 Final Thoughts

**Was it worth it?** Absolutely.

**Was it easy?** No, but manageable with the right guidance.

**Could other trades businesses do this?** 100% yes.

**Would they do anything differently?** Start sooner.

---

**NorthWest Heating & Gas Ltd went from security novices to Cyber Essentials certified in 90 days while running a busy business. If they can do it, so can you.**

**The kit works. The plan works. You just have to start.**
