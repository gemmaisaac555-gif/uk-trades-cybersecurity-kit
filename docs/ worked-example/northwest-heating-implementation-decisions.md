# NorthWest Heating & Gas Ltd — Implementation Decisions

> **What this document is:** A record of every meaningful decision James and Sarah made when building their security setup, and the reasoning behind each choice. This is useful for audits, for onboarding future staff, and as a reference if they ever need to revisit a decision.

---

## How to Read This Document

Each decision is recorded as:
- **The choice they faced** — what options existed
- **What they decided** — what they actually did
- **Why** — their reasoning
- **What they'd watch out for** — when this decision might need revisiting

---

## Device Decisions

### Decision 1: Company phones vs. BYOD for engineers

**Choice they faced:** Issue company phones to all engineers, or let them use personal phones with a BYOD policy.

**What they decided:** Company phones for all 6 engineers. Personal phones (BYOD) only for James and Sarah, who already used their own iPhones for email.

**Why:**
- Engineers are out on job sites — phones get dropped, lost, left behind. If it's a company phone, replacing it is straightforward. If it's a personal phone, it gets complicated quickly.
- Easier to manage: Sarah can check, update, and if necessary wipe a fleet of identical Samsung A34s. Mixed personal devices would mean different Android versions, different manufacturers, different settings menus.
- Cost was acceptable: 6x Samsung Galaxy A34 came to around £900 total when purchased refurbished. Cheaper than the management overhead of BYOD.
- Avoids awkward conversations about personal phone privacy — company phone is clearly company property.

**What they'd watch out for:** If a future engineer strongly prefers their own phone, the BYOD option is still available. The policy covers both scenarios. Worth revisiting if team size grows significantly (managing 15+ company phones becomes more work).

---

### Decision 2: Which Android phones to standardise on

**Choice they faced:** Higher-spec phones (Samsung S-series, Pixel), mid-range (Samsung A-series), or budget devices.

**What they decided:** Samsung Galaxy A34 for all engineers.

**Why:**
- Supports Android 12+ which means full-disk encryption is on by default — no configuration needed
- Samsung has a strong track record of 4 years of security updates on A-series devices
- Mid-range price point (around £150 refurbished) is right for work phones that will get knocked about
- All the same model means Sarah only has to learn one settings menu
- Tradify, Outlook, and Teams all run well on it

**What they'd watch out for:** When the A34 reaches end of security updates (estimated 2028), they'll need to plan replacements. Sarah has a calendar reminder set for January 2027 to review this.

---

### Decision 3: Screen lock method

**Choice they faced:** PIN only, password, fingerprint, or face recognition.

**What they decided:** Fingerprint as the primary method, with a 6-digit PIN as backup. Automatic lock after 5 minutes.

**Why:**
- Fingerprint is fast — engineers are unlocking phones constantly on job sites, a complex password would be abandoned in practice
- 5-minute auto-lock is a balance between security and usability; they tried 2 minutes in testing and one engineer complained it locked while he was reading a job sheet
- 6-digit PIN is sufficient for a backup method that's rarely used
- Face recognition was considered but rejected — less reliable in bright outdoor light and when wearing dust masks

**What they'd watch out for:** If NCSC guidance changes on minimum PIN length, or if a security incident involves PIN guessing, revisit this.

---

## Software and App Decisions

### Decision 4: Which password manager to use

**Choice they faced:** Bitwarden (free/paid), 1Password, Dashlane, LastPass, or browser-built-in password saving.

**What they decided:** Bitwarden, free tier for individuals, with a shared team vault managed by Sarah.

**Why:**
- Free tier covers individual use entirely — no cost to roll out to 8 staff
- Open source — the code is publicly audited, which matters for a security tool
- Works on Android (Samsung phones), iOS (James and Sarah's iPhones), and Windows (office PC)
- Browser extension works in Chrome and Edge
- Sarah evaluated it against 1Password (better UI but £4/user/month) and decided the free Bitwarden was the better value for a business this size
- LastPass was explicitly ruled out following their 2022 breach

**What they'd watch out for:** If Bitwarden changes its free tier terms significantly, or if the team grows and shared vault management becomes unwieldy, revisit paid options. 1Password Teams would be the natural upgrade path.

---

### Decision 5: Photo management workflow

**Choice they faced:** Leave job site photos in engineers' camera rolls, use a dedicated photo app, or upload to Tradify and delete from device.

**What they decided:** Upload to Tradify within 24 hours of a job, then delete from camera roll.

**Why:**
- Discovered one engineer had 400+ job site photos going back 18 months — customer homes, visible addresses, boiler makes/models, sometimes doors/windows. If that phone was lost or stolen, that's a significant data exposure.
- Tradify already stores job photos against the correct job record — it's where they should be anyway
- Deleting from camera roll removes the data from a less-controlled location
- 24 hours gives engineers a reasonable window rather than requiring uploads mid-job

**What they'd watch out for:** Engineers need to actually do this — Sarah added a check to the monthly phone review. If photos are building up in camera rolls again, it means the habit hasn't stuck and needs reinforcement.

---

### Decision 6: WhatsApp for work communications

**Choice they faced:** Ban WhatsApp for work entirely, allow it for personal use only, or use it for work communications.

**What they decided:** WhatsApp allowed on company phones for personal use. Not to be used for work customer communications — customer contact goes through Tradify and Outlook.

**Why:**
- Banning WhatsApp outright would feel heavy-handed and be unenforceable in practice
- Using WhatsApp for customer communication creates data that lives outside their controlled systems — can't be audited, searched, or backed up properly
- The practical risk is customer data (addresses, job details) sitting in WhatsApp message history, which doesn't meet GDPR data storage requirements
- Personal WhatsApp use on a work phone is low risk and high goodwill

**What they'd watch out for:** If engineers start using personal WhatsApp groups to coordinate jobs and share customer details informally, that's the scenario to close down. Sarah will ask about this at annual review.

---

## Policy Language Decisions

### Decision 7: Tone and formality of policy documents

**Choice they faced:** Formal, legally-worded policy documents vs. plain English written in NorthWest Heating's voice.

**What they decided:** Plain English, written in James's voice, with formal structure kept where necessary for legal/audit purposes.

**Why:**
- Their team are heating engineers, not IT professionals. A policy full of legal language won't be read, understood, or followed.
- James tested an early draft on Dave (one of the engineers) — Dave said "I'd probably skim this and sign it." That was the signal to rewrite it.
- The final versions use phrases like "use common sense" and "don't take the piss" — language James would actually use in a team meeting
- Legal validity doesn't require formal language; it requires clear intent and evidence of communication

**What they'd watch out for:** If they ever need to defend a policy decision to a regulator or in an employment dispute, make sure the plain English version is unambiguous. If any section feels unclear, add a formal clarification note — but keep the main text readable.

---

### Decision 8: Level of monitoring/surveillance disclosed

**Choice they faced:** Say nothing about monitoring, implement monitoring quietly, or be explicit about what they do and don't monitor.

**What they decided:** Explicitly state what they can do (remote locate, remote wipe) and explicitly state what they won't do (read texts, track location routinely, look at photos).

**Why:**
- The biggest concern from engineers when the policy was announced was "are you going to track us?"
- Being explicit about what monitoring does and doesn't happen removes suspicion and builds trust
- Under GDPR and UK employment law, employees should know what data is being collected about them anyway — this is just good practice
- The distinction between "we can wipe it if lost" (legitimate) vs "we're watching what you do" (intrusive) is important to communicate clearly

**What they'd watch out for:** If they ever do need to investigate a specific incident involving a phone, get legal advice first. The policy covers what routine monitoring looks like — an investigation is a different situation.

---

## Rollout Decisions

### Decision 9: How to communicate the policy to staff

**Choice they faced:** Email the policy document, ask staff to read and sign, hold a formal training session, or quick team briefing.

**What they decided:** 15-minute Friday afternoon team meeting. James explained the why, walked through key points, answered questions. Sarah followed up individually with anyone who needed help setting things up.

**Why:**
- 8 people in a room is manageable and more effective than email for this kind of thing
- Friday afternoon — work is winding down, people are more relaxed
- Keeping it to 15 minutes respects engineers' time
- James presenting it (not Sarah reading out a policy document) made it feel like a company decision, not an admin exercise
- Individual follow-up from Sarah meant technical setup issues got resolved immediately rather than being left

**What they'd watch out for:** For future policy updates, same approach. New starters will need a briefing as part of their induction — Sarah has added this to the new starter checklist.

---

### Decision 10: Technical setup before or after announcement

**Choice they faced:** Announce the policy first, then set up devices. Or set up devices first, then announce.

**What they decided:** Set up devices first (Bitwarden installed, Find My Device configured, PINs checked), then announce.

**Why:**
- Reduced the friction at the team meeting — "you need to install Bitwarden" vs "Bitwarden is already on your phone, here's your login"
- Meant Sarah could answer "is this hard?" with "no, it's already done" — removes the fear of it being complicated
- Two phones didn't have PINs set — quietly fixing these before the meeting was better than calling it out publicly
- Doing the setup revealed one phone was on an outdated Android version — fixed before the meeting

**What they'd watch out for:** For future policy changes, same principle applies. Do the easy technical work before the announcement where possible.

---

## Decisions Still Open

These are things NorthWest Heating hasn't decided yet, but are aware of:

| Topic | Current State | When to Decide |
|---|---|---|
| Mobile Device Management (MDM) software | Not implemented — managing manually | When team grows beyond ~12, or after any security incident involving a device |
| Cyber Essentials certification | Interested, not applied | When chasing larger commercial contracts that require it |
| Email security (SPF/DKIM/DMARC) | Not configured | When setting up Microsoft 365 properly — recommend doing this soon |
| Formal data retention schedule | No policy yet | Before next ICO guidance review or after first GDPR query from customer |

---

*Document Owner: Sarah Mitchell*
*Created: January 2025*
*Next Review: January 2026*
