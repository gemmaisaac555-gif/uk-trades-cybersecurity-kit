# Glossary of Security Terms
### Plain English Definitions for Trades Business Owners

---

> This glossary covers the security and IT terms you're most likely to encounter as a small business owner, whether you're reading this kit, filling in a tender, talking to a customer, or trying to understand a data breach email. Definitions are written for non-technical people, not IT professionals.

---

## A

**Access control**
Deciding who is allowed to access what. Locking your phone so only you can use it is an access control. Password-protecting your accounts is an access control. The principle is: people should only have access to what they actually need.

**Account takeover**
When someone gets into one of your accounts (email, Xero, Tradify) without your permission. Usually happens because of weak passwords, reused passwords, or falling for a phishing attack. The attacker can then send emails pretending to be you, steal data, or change account details.

**Authentication**
Proving who you are to a system. Usually a password, but can also be a fingerprint, face recognition, or a code sent to your phone (see: two-factor authentication).

---

## B

**Backup**
A copy of your data stored separately from the original. If the original is lost, deleted, or encrypted by ransomware, you can restore from the backup. The key questions are: how recent is the backup? Is it stored somewhere separate from the original?

**Bitwarden**
A password manager — a secure app that stores all your passwords and generates strong new ones. Recommended in this kit because it's free, open source, and works on phones and computers. The only password you need to remember is your Bitwarden master password.

**BYOD (Bring Your Own Device)**
When employees use their personal phones or laptops for work. Convenient but creates complications around data ownership, security requirements, and what happens when someone leaves. See the mobile device policy for how to handle this.

---

## C

**Cyber Essentials**
A UK government-backed certification scheme that tests businesses against five basic security controls: firewalls, secure configuration, user access control, malware protection, and patch management. Increasingly required for government contracts and some commercial tenders. The basic self-assessment version costs £300.

**Cloud software (SaaS)**
Software you access through a web browser or app, where your data is stored on the provider's servers, not your own computer. Examples: Xero (accounting), Tradify (job management), Microsoft 365 (email and documents). Advantage: accessible anywhere, provider handles most backups. Risk: if the provider has an outage or you lose access to your account, you can't access your data.

**Credential stuffing**
An attack where criminals use lists of username/password combinations (stolen from other websites' breaches) and try them on other services. If you use the same password on multiple sites and one site is breached, attackers will try that password everywhere else. This is why password reuse is dangerous.

---

## D

**Data breach**
When personal data is accessed, lost, stolen, or disclosed without authorisation. Examples: losing a phone containing customer details, accidentally emailing the wrong person, ransomware encrypting your customer records. Under GDPR, serious data breaches must be reported to the ICO within 72 hours.

**Data minimisation**
Only collecting and keeping the personal data you actually need. If you don't need a customer's date of birth, don't ask for it. If you've finished a job and don't need to keep the photos on your phone, delete them. Less data held means less exposure if something goes wrong.

**DMARC / DKIM / SPF**
Technical settings for your email domain that help prevent criminals from sending emails that pretend to be from your email address. Not something you'll configure yourself in most cases — your IT person or Microsoft 365 admin can set them up. Worth doing because it protects your reputation and helps your emails avoid being marked as spam.

---

## E

**Encryption**
Scrambling data so it can only be read by someone with the right key. Full-disk encryption on a phone means that if someone finds your lost phone and removes the storage chip, the data is unreadable. Modern iPhones and Android phones (Android 12+) encrypt data by default — you don't have to do anything to turn it on.

**End-to-end encryption**
A stronger form of encryption where only the sender and recipient can read a message — not even the service provider can see it. WhatsApp uses end-to-end encryption for messages. This doesn't mean WhatsApp is automatically safe for business use — metadata (who you messaged, when) can still be visible, and business data in personal WhatsApp doesn't meet GDPR data storage requirements.

---

## F

**Firewall**
Software or hardware that monitors and controls incoming and outgoing network traffic based on security rules. Your broadband router has a basic firewall built in. Windows computers have a software firewall built in. For most small businesses, the defaults are adequate — the risk is usually not firewall bypass but phishing, weak passwords, and unpatched software.

**Find My Device / Find My iPhone**
Built-in features on Android and iPhone respectively that let you locate, lock, or wipe a device remotely if it's lost or stolen. Free, built into the operating system, should be enabled on all work phones. Requires the phone to be connected to the internet and to have the feature turned on before it goes missing.

**Full-disk encryption**
Encryption applied to everything stored on a device, not just individual files. If a phone with full-disk encryption is stolen and turned off, the data is unreadable without the correct PIN/password. On by default on iPhone and Android 12+.

---

## G

**GDPR (General Data Protection Regulation)**
EU law that became UK law after Brexit (now called UK GDPR). Sets rules about how personal data must be collected, stored, used, and protected. Applies to any business that handles personal data about individuals — which includes customer contact details, job addresses, email communications, and photos of people's homes. The ICO enforces it in the UK.

---

## H

**Hashing**
A way of storing passwords so that even if a database is stolen, the attacker doesn't get the actual passwords — just scrambled versions. Good websites store hashed passwords, not plaintext. If a website is breached and the attacker gets your actual password (not a hash), that website was not storing passwords securely.

---

## I

**ICO (Information Commissioner's Office)**
The UK's data protection regulator. They enforce GDPR and the Data Protection Act. If you have a serious data breach involving customer personal data, you need to report it to the ICO within 72 hours. Their website has good free guidance for small businesses: ico.org.uk

**Incident response**
The process of what you do when something goes wrong — a data breach, ransomware attack, lost device, or account takeover. Having a plan before an incident means you respond faster and make better decisions under pressure. The backup and recovery policy includes basic incident response steps.

**Intune (Microsoft Intune)**
Microsoft's Mobile Device Management (MDM) tool. Allows businesses to remotely manage phones, enforce security policies, and push software. Included in Microsoft 365 Business Premium. Not needed for very small businesses managing phones manually, but worth investigating if you have 10+ devices or want Cyber Essentials Plus certification.

---

## L

**Least privilege**
The principle that people should only have access to the systems and data they need to do their job — nothing more. A junior engineer probably doesn't need access to your Xero accounting software. A subcontractor probably shouldn't have access to your full customer database. Limiting access limits the damage if an account is compromised.

---

## M

**Malware**
Malicious software — any program designed to damage, disrupt, or gain unauthorised access to a system. Includes viruses, ransomware, spyware, and more. The most common entry points: clicking links in phishing emails, installing apps from unofficial sources, and visiting compromised websites.

**MDM (Mobile Device Management)**
Software that allows businesses to centrally manage mobile devices — enforce screen lock policies, push software updates, remotely wipe lost devices, and audit device compliance. Examples: Microsoft Intune, Jamf. Overkill for very small businesses managing manually; useful at scale.

**MFA / 2FA (Multi-Factor Authentication / Two-Factor Authentication)**
Adding a second proof of identity beyond just a password. Usually a code sent to your phone or generated by an app (e.g. Microsoft Authenticator). Means an attacker who steals your password still can't get into your account without also having access to your phone. One of the most effective security measures available. Should be enabled on email accounts and accounting software at minimum.

---

## N

**NCSC (National Cyber Security Centre)**
The UK government's cybersecurity authority. Part of GCHQ. Provides free guidance, threat intelligence, and incident reporting for UK businesses. Their website has practical guidance for small businesses: ncsc.gov.uk

---

## P

**Patch / Patching**
Updates to software that fix security vulnerabilities. "Patching" means applying these updates. Security patches are different from feature updates — they fix known weaknesses that attackers can exploit. Not updating software promptly is one of the most common causes of breaches. The mobile device policy's monthly update check is a patching process.

**Phishing**
A social engineering attack where criminals send emails (or texts, or calls) pretending to be a trusted source — your bank, HMRC, Microsoft, a supplier — to trick you into revealing passwords, clicking malicious links, or transferring money. The email looks convincing but leads to a fake website or downloads malware. "Smishing" is the same thing via text message.

**Password manager**
Software that securely stores all your passwords, generates strong unique ones, and fills them in automatically. You only need to remember one master password. Recommended: Bitwarden (free). Without a password manager, most people reuse passwords — which is one of the most dangerous security habits.

---

## R

**Ransomware**
Malware that encrypts all your files and demands payment (usually in cryptocurrency) to decrypt them. Even if you pay, there's no guarantee you'll get your data back. The only reliable protection is good backups stored separately from the infected system. Increasingly common against small businesses because they're less likely to have robust backups.

**Remote wipe**
The ability to delete all data from a device remotely, usually via the internet. Requires the device to be connected. Used when a phone is lost or stolen and can't be recovered. For Android: Find My Device. For iPhone: Find My iPhone. Covered in the mobile device policy.

---

## S

**Screen lock**
A security feature that requires a PIN, password, fingerprint, or face recognition to unlock a device. Essential on work phones — without it, anyone who finds or steals the phone has immediate access to all apps, email, and data on it. Should auto-lock after a period of inactivity (5–10 minutes recommended).

**SIM swap**
An attack where a criminal convinces your mobile network to transfer your phone number to a SIM card they control. They then receive your text messages — including two-factor authentication codes — and can take over your accounts. More sophisticated attack. Mitigation: use an authenticator app (Microsoft Authenticator, Google Authenticator) instead of SMS for two-factor codes where possible.

**Social engineering**
Manipulating people into revealing information or taking actions rather than hacking systems. Phishing is social engineering by email. A caller pretending to be your bank is social engineering by phone. The target is human judgment, not software vulnerabilities. Training and awareness are the defences.

**SPF record**
Part of your email domain's DNS settings that lists which servers are allowed to send email on behalf of your domain. Helps prevent your email address being used for spam. See also: DMARC, DKIM.

---

## T

**Two-factor authentication (2FA)**
See: MFA.

---

## U

**UK GDPR**
The UK's version of GDPR, adopted after Brexit. Functionally very similar to EU GDPR for most practical purposes. Enforced by the ICO.

---

## V

**VPN (Virtual Private Network)**
Encrypts your internet connection and routes it through a server elsewhere. Useful on public WiFi to prevent eavesdropping. Not a complete security solution — it doesn't protect against phishing, malware, or account takeovers. The mobile device policy recommends not using public WiFi for sensitive tasks (Xero, banking) — mobile data is the simpler alternative for most small businesses.

**Vulnerability**
A weakness in software, hardware, or human behaviour that can be exploited by an attacker. Unpatched software has known vulnerabilities. Weak passwords are a vulnerability. Clicking phishing links is a human vulnerability.

---

## W

**Whaling**
A targeted phishing attack aimed at senior people in a business (the "big fish") — typically the business owner or finance manager. Usually involves a convincing email that looks like it's from a trusted contact (a supplier, accountant, or bank) and asks for an urgent payment or login credentials. High value target, higher effort from attacker.

---

*Part of the Small Business Information Security Starter Kit.*
