# Cyber Essentials Readiness Checklist

**Prepare your trades business for Cyber Essentials certification**

---

## 🎯 What Is Cyber Essentials?

Cyber Essentials is a UK government-backed certification scheme that shows you have basic cyber security controls in place. It's increasingly required for:
- Public sector contracts
- Some private sector tenders
- Cyber insurance (better rates or required)
- Supply chain requirements

**Two levels:**
1. **Cyber Essentials** - self-assessment questionnaire (£300-500)
2. **Cyber Essentials Plus** - includes technical verification (£1,000-2,000)

Most trades businesses start with basic Cyber Essentials.

---

## 📋 The Five Controls

Cyber Essentials focuses on five technical controls that prevent ~80% of cyber attacks:

1. **Firewalls** - Boundary protection
2. **Secure Configuration** - Removing unnecessary functionality
3. **Access Control** - Who can access what
4. **Malware Protection** - Antivirus and anti-malware
5. **Patch Management** - Keeping software updated

This checklist helps you assess readiness for each control.

---

## ✅ Control 1: Firewalls

Firewalls control what traffic can enter/leave your network.

### Boundary Firewalls

**Your office internet connection:**
- [ ] Router has firewall enabled (most ISP routers do by default)
- [ ] Router admin password changed from default
- [ ] Router firmware is up to date
- [ ] Unnecessary services disabled (UPnP, remote admin, WPS)

**Check your router:**
- Login to router admin panel (usually 192.168.1.1 or 192.168.0.1)
- Look for firmware update option
- Check firewall is enabled
- Change admin password if still default (admin/admin, admin/password, etc.)

**For NorthWest Heating:** BT Business Hub - logged in, firewall enabled by default, changed admin password, updated firmware. ✓

### Device-Based Firewalls

**All computers:**
- [ ] Windows Firewall enabled on all laptops/desktops (it is by default)
- [ ] macOS Firewall enabled if using Macs
- [ ] No third-party firewalls interfering (Norton, McAfee, etc. - if present, ensure properly configured)

**Check on Windows:**
- Settings > Update & Security > Windows Security > Firewall & network protection
- All three network types (Domain, Private, Public) should show "Firewall is on"

**For NorthWest Heating:** Checked both office laptops, Windows Firewall on. ✓

### Mobile Devices

**Company phones/tablets:**
- [ ] Don't need traditional firewalls
- [ ] Use mobile data or trusted WiFi only
- [ ] Avoid public WiFi for sensitive work

**For NorthWest Heating:** Engineers use phone data, office WiFi is secure. ✓

### What Cyber Essentials Asks

You'll need to describe:
- How your network connects to the internet
- What firewall protects the boundary
- Whether device firewalls are enabled
- How you ensure they stay configured correctly

**Pass/Fail:** This is usually straightforward. Most SMEs pass this easily.

---

## ✅ Control 2: Secure Configuration

Remove or disable unnecessary functionality that could be exploited.

### Operating Systems

**All computers:**
- [ ] Running supported OS versions:
  - Windows 10 or Windows 11 (not Windows 7/8)
  - macOS Monterey or newer
  - Linux with security updates enabled
- [ ] Unused software removed (old trial software, Adobe Reader when you use PDF in browser, etc.)
- [ ] Unnecessary services disabled
- [ ] Auto-run for removable media disabled

**Check Windows version:**
- Settings > System > About
- Look for "Windows 10" or "Windows 11"
- Check "OS build" is recent (means updates are working)

**For NorthWest Heating:** Both laptops on Windows 11, removed old software. ✓

### User Accounts

**All devices:**
- [ ] Standard user accounts for daily work
- [ ] Administrator accounts only for IT tasks
- [ ] No generic shared accounts (except where documented and necessary)
- [ ] Guest accounts disabled

**Check on Windows:**
- Settings > Accounts > Family & other users
- Your account should show "Administrator" only if you're the IT person
- Daily users should be "Standard user"

**For NorthWest Heating:** James and Sarah have admin, engineers use standard accounts on office computers. ✓

### Default Passwords

**All systems:**
- [ ] Router admin password changed from default
- [ ] Any network devices (WiFi access points) have passwords changed
- [ ] Printer admin password changed (if it has one)
- [ ] Default accounts on any software changed/disabled

**Common default usernames:** admin, administrator, root, guest

**For NorthWest Heating:** Changed router password, printer doesn't have admin interface. ✓

### Software Configuration

**All applications:**
- [ ] Automatic updates enabled where possible
- [ ] Unnecessary features disabled
- [ ] Macros disabled by default in Microsoft Office (it is by default)
- [ ] Browser configured securely (pop-up blocker on, don't save passwords if using password manager)

**Microsoft Office macro settings:**
- File > Options > Trust Center > Trust Center Settings > Macro Settings
- Should be "Disable all macros with notification" (default)

**For NorthWest Heating:** Office macros disabled by default, browsers configured. ✓

### Mobile Devices

**Company phones/tablets:**
- [ ] Unnecessary apps removed
- [ ] Auto-install apps disabled
- [ ] App permissions reviewed (does the calculator really need access to contacts?)
- [ ] Bluetooth disabled when not in use
- [ ] NFC disabled if not needed

**For NorthWest Heating:** Removed bloatware from Samsung phones, disabled unnecessary features. ✓

### What Cyber Essentials Asks

You'll need to describe:
- How you ensure only authorized software is installed
- How you configure devices securely
- How you manage administrator privileges
- How you handle default passwords

**Pass/Fail:** Common failure points are old Windows versions or excessive admin rights.

---

## ✅ Control 3: Access Control

Control who can access what systems and data.

### User Access Control

**All systems:**
- [ ] Unique user accounts for each person (no shared logins)
- [ ] Accounts removed promptly when staff leave (within 24 hours)
- [ ] Principle of least privilege (people only access what they need)
- [ ] Regular review of who has access to what (quarterly minimum)

**Document who has access to:**
- Email accounts
- Accounting software (Xero)
- Job management (Tradify)
- Cloud storage (OneDrive)
- Social media accounts
- Banking/payment systems

**For NorthWest Heating:** Everyone has own email, only James and Sarah access Xero, engineers share Tradify account (documented exception). ✓

### Password Policy

**All accounts:**
- [ ] Minimum password length enforced (12+ characters)
- [ ] Password complexity encouraged (mix of characters)
- [ ] Passwords not reused across accounts
- [ ] Password manager in use
- [ ] Passwords changed when compromised

**See:** [Password Policy](../policies/password-policy.md)

**For NorthWest Heating:** Bitwarden deployed, 12+ char passwords, MFA enabled on critical systems. ✓

### Multi-Factor Authentication (MFA)

**Critical systems (mandatory):**
- [ ] Email (Microsoft 365, Gmail, etc.)
- [ ] Accounting software
- [ ] Banking/payment systems
- [ ] Remote access tools
- [ ] Cloud storage with sensitive data

**Good practice (recommended):**
- [ ] Password manager
- [ ] Job management software
- [ ] Social media business accounts

**For NorthWest Heating:** MFA on email, Xero, banking, password manager. Tradify doesn't support MFA. ✓

### Remote Access

**If you have remote access to office systems:**
- [ ] VPN required for remote access
- [ ] MFA enabled for VPN
- [ ] Remote desktop disabled or secured with MFA
- [ ] List of who has remote access maintained

**If you don't have remote access:**
- [ ] Confirm remote desktop is disabled
- [ ] Confirm VPN not configured
- [ ] Document that remote access isn't used

**For NorthWest Heating:** No remote access to office - everything is cloud-based. ✓

### Administrator Accounts

**Privileged accounts:**
- [ ] Separate admin accounts from standard user accounts
- [ ] Admin accounts not used for daily work (email, browsing)
- [ ] Admin actions logged
- [ ] Limited number of admin accounts

**For NorthWest Heating:** James and Sarah have admin on office computers, only used when installing software. ✓

### Mobile Device Access

**Company phones:**
- [ ] Screen locks enabled (PIN/biometric)
- [ ] Automatic lock after 5 minutes
- [ ] Remote wipe capability configured
- [ ] Lost/stolen devices reported immediately

**See:** [Mobile Device Policy](../policies/06-mobile-device-policy.md)

**For NorthWest Heating:** All phones have 6-digit PINs or fingerprint, Find My Device enabled. ✓

### What Cyber Essentials Asks

You'll need to describe:
- How users are given access to systems
- How you use passwords and MFA
- How you manage administrator privileges
- How you control access on mobile devices

**Pass/Fail:** Common failure is lack of MFA on critical systems or shared accounts without justification.

---

## ✅ Control 4: Malware Protection

Protect against malicious software.

### Antivirus/Anti-Malware

**All computers:**
- [ ] Antivirus software installed and running
- [ ] Automatic updates enabled
- [ ] Real-time scanning enabled
- [ ] Regular scans scheduled
- [ ] Quarantined threats reviewed

**Built-in options (free):**
- Windows Defender (Windows 10/11) - perfectly adequate for SMEs
- macOS built-in protections

**Paid options (if you prefer):**
- Bitdefender, Norton, McAfee, Kaspersky, ESET

**Check Windows Defender:**
- Settings > Update & Security > Windows Security > Virus & threat protection
- Should show "No current threats"
- Should show "Real-time protection: On"

**For NorthWest Heating:** Using Windows Defender on both laptops, auto-updates on, real-time protection enabled. ✓

### Email Protection

**Email security:**
- [ ] Spam filtering enabled (Microsoft 365/Gmail have this built-in)
- [ ] Attachment scanning enabled
- [ ] Phishing protection enabled
- [ ] Staff trained to recognize suspicious emails

**Microsoft 365 has all of this by default.** You don't need to configure anything extra.

**For NorthWest Heating:** Using Microsoft 365 Business Basic, spam filtering active, conducted phishing awareness training. ✓

### Mobile Devices

**Company phones/tablets:**
- [ ] Only install apps from official stores (Google Play, Apple App Store)
- [ ] App permissions reviewed before installing
- [ ] "Unknown sources" installation blocked (Android)
- [ ] Regular OS updates applied

**Do you need antivirus on phones?** Generally no for iPhone. For Android, only if installing lots of third-party apps.

**For NorthWest Heating:** Samsung phones, only official apps, unknown sources blocked. No third-party antivirus needed. ✓

### Web Browsing

**All devices:**
- [ ] Browsers kept updated (Chrome, Edge, Safari, Firefox)
- [ ] Pop-up blocker enabled
- [ ] Safe browsing enabled (warns about dangerous sites)
- [ ] Ad blocker installed (optional but helpful)

**Check browser:**
- Chrome: Settings > Privacy and security > Security > Safe Browsing
- Should be "Standard protection" or "Enhanced protection"

**For NorthWest Heating:** All browsers up to date, safe browsing enabled. ✓

### Removable Media

**USB drives, external hard drives:**
- [ ] Scanned before use
- [ ] Auto-run disabled (Windows 10/11 default)
- [ ] Only trusted USB devices used
- [ ] Consider disabling USB ports if not needed (extreme measure)

**For NorthWest Heating:** Rarely use USB drives, auto-run disabled, scan before use when necessary. ✓

### What Cyber Essentials Asks

You'll need to describe:
- What antivirus you use
- How it's kept updated
- How you protect against malicious emails
- How mobile devices are protected

**Pass/Fail:** Easy pass if using Windows Defender or any reputable antivirus with updates enabled.

---

## ✅ Control 5: Patch Management

Keep software updated to fix security vulnerabilities.

### Operating System Updates

**All computers:**
- [ ] Automatic updates enabled (Windows Update, macOS Software Update)
- [ ] Updates installed within 14 days of release
- [ ] Restart scheduled to apply updates
- [ ] Check updates working (not paused/broken)

**Check Windows Update:**
- Settings > Update & Security > Windows Update
- Should show "You're up to date"
- Check "Last checked" is recent (within a week)

**For NorthWest Heating:** Both laptops set to auto-update, check monthly that updates are installing. ✓

### Application Updates

**All software:**
- [ ] Automatic updates enabled where possible:
  - Microsoft Office
  - Web browsers (Chrome, Edge, Firefox)
  - Adobe Reader/Acrobat
  - Java (if installed - consider removing if not needed)
- [ ] Updates checked manually for software without auto-update
- [ ] List of installed software maintained

**Common vulnerable software:**
- Adobe products (Reader, Flash - remove Flash if still installed)
- Java (remove if not needed)
- Old versions of Office (upgrade or remove)

**For NorthWest Heating:** Office 365 auto-updates, browsers auto-update, removed Java (wasn't needed). ✓

### Mobile Device Updates

**Company phones/tablets:**
- [ ] OS updates installed within 14 days
- [ ] App updates enabled (automatic if possible)
- [ ] Regular check that updates are working
- [ ] Old unsupported devices replaced

**Check phone OS:**
- Settings > System > System update (Android)
- Settings > General > Software Update (iPhone)

**For NorthWest Heating:** Company Samsung phones on Android 14, auto-update enabled for apps, manual check monthly for OS updates. ✓

### Firmware Updates

**Network devices:**
- [ ] Router firmware up to date
- [ ] WiFi access points up to date
- [ ] Any network switches/hardware up to date

**Check router firmware:**
- Login to router admin (usually 192.168.1.1 or 192.168.0.1)
- Look for "Firmware update" or "System update"
- Apply if available

**For NorthWest Heating:** BT router checks for firmware updates automatically. ✓

### Unsupported Software

**Remove or replace:**
- [ ] Windows 7, 8, 8.1 (upgrade to Windows 10/11)
- [ ] Office 2010 or older (upgrade to Office 365 or 2019+)
- [ ] Internet Explorer (use Edge, Chrome, Firefox)
- [ ] Adobe Flash Player (should be removed, no longer supported)
- [ ] Any software that hasn't been updated in 2+ years

**For NorthWest Heating:** Everything on supported versions, removed old software. ✓

### Patch Management Process

**Document how you:**
- [ ] Check for updates (automatic or manual)
- [ ] Test updates (or accept automatic updates)
- [ ] Apply updates (schedule if needed)
- [ ] Verify updates installed successfully
- [ ] Track what versions are installed

**For small businesses:**
"We enable automatic updates on all devices and check monthly that they're working."

**For NorthWest Heating:** "Auto-updates enabled. Sarah checks first Monday of each month that laptops and phones are up to date. Takes 30 minutes." ✓

### What Cyber Essentials Asks

You'll need to describe:
- How you keep operating systems updated
- How you manage application updates
- How you handle mobile device updates
- How quickly you apply security patches (14-day target)

**Pass/Fail:** Common failure is running unsupported Windows or not having a patch management process.

---

## 📊 Overall Readiness Assessment

### Score Your Readiness

Count how many items you can tick off across all five controls:

- **80%+ complete:** Ready to apply for Cyber Essentials now
- **60-79% complete:** 2-4 weeks of work needed
- **40-59% complete:** 1-2 months of work needed
- **<40% complete:** Follow the [30-Day Quick Start](../implementation/30-day-quick-start.md) first

### Common Gaps for Trades Businesses

**Issues we see frequently:**
1. ❌ MFA not enabled on critical systems
2. ❌ Shared accounts without justification
3. ❌ Old unsupported Windows versions
4. ❌ No documented patch management process
5. ❌ Excessive administrator privileges
6. ❌ No mobile device management

**Quick fixes (can do in a day):**
- Enable MFA on email and accounting
- Change default router password
- Enable automatic updates
- Set up password manager

**Longer fixes (need 1-2 weeks):**
- Upgrade old operating systems
- Create separate admin/user accounts
- Document access control procedures
- Set up mobile device management

---

## 🚀 Getting Certified

### The Process

**Step 1: Self-Assessment**
- Complete this checklist
- Fix any gaps
- Gather evidence (screenshots helpful)

**Step 2: Choose Certification Body**
- IASME Consortium (most common)
- Crest-approved bodies
- Costs: £300-500 for basic Cyber Essentials

**Step 3: Complete Questionnaire**
- Online form about your security controls
- Takes 1-2 hours to complete
- Be honest - they're checking reasonableness, not perfection

**Step 4: Submit and Wait**
- Certification body reviews your answers
- May ask for clarification
- Usually get result within 5-10 working days

**Step 5: Receive Certificate**
- Valid for 12 months
- Includes logo for website/tenders
- Renew annually

### Tips for Passing

**Do:**
- ✅ Be honest about your setup
- ✅ Explain exceptions (like shared accounts if necessary)
- ✅ Show you have processes, even if simple
- ✅ Document what you do
- ✅ Ask for clarification if confused

**Don't:**
- ❌ Lie or exaggerate
- ❌ Leave questions blank
- ❌ Ignore obvious vulnerabilities
- ❌ Rush the questionnaire

### What If You Fail?

**Common reasons for failure:**
- No MFA on email/critical systems
- Unsupported operating systems
- No patch management process
- Excessive use of shared accounts
- No evidence of security awareness

**What happens:**
- You get feedback on what to fix
- Fix the issues (usually takes 1-2 weeks)
- Resubmit (often free or small fee)
- Most people pass on second attempt

---

## 📅 Implementation Timeline

### If Starting From Scratch

**Weeks 1-2: Passwords and MFA**
- Deploy password manager
- Enable MFA on critical systems
- Change default passwords

**Weeks 3-4: Updates and Malware**
- Enable automatic updates everywhere
- Check antivirus is working
- Remove old unsupported software

**Weeks 5-6: Access Control and Documentation**
- Review who has access to what
- Remove unnecessary admin privileges
- Document your processes

**Weeks 7-8: Final Checks and Application**
- Work through this checklist
- Gather evidence
- Complete questionnaire
- Submit for certification

### If You've Done the 30-Day Quick Start

You're probably 60-70% ready. Focus on:
- Week 1: Enable MFA everywhere
- Week 2: Review and document access controls
- Week 3: Final checks and application

---

## 💰 Cost Breakdown

**Certification:**
- Cyber Essentials: £300-500
- Annual renewal: Same cost

**Implementation:**
- Password manager: £0-50/month
- Antivirus: £0 (Windows Defender) to £40/device/year
- Time: 20-40 hours total (spread over 2 months)

**Total first year:** ~£500-800 + your time

**ROI:**
- Opens up contracts requiring Cyber Essentials
- Better cyber insurance rates (10-20% discount)
- Customer confidence
- Actual security improvements

---

## 📋 Pre-Application Checklist

Before you submit for Cyber Essentials, verify:

### Technical Controls
- [ ] All computers on supported OS versions
- [ ] Antivirus installed and updated on all computers
- [ ] Automatic updates enabled everywhere
- [ ] Firewalls enabled on router and computers
- [ ] MFA enabled on email and accounting at minimum

### Access Controls
- [ ] Password manager deployed
- [ ] MFA enabled on critical systems
- [ ] Individual accounts for each person
- [ ] Admin privileges limited
- [ ] Screen locks on mobile devices

### Documentation
- [ ] List of all devices and software
- [ ] List of who has access to what
- [ ] Password policy documented
- [ ] Patch management process documented
- [ ] Mobile device policy documented

### Evidence (Helpful to Have)
- [ ] Screenshots of Windows Update status
- [ ] Screenshot of antivirus status
- [ ] Screenshot of firewall status
- [ ] List of current software versions
- [ ] Access control matrix

---

## 🎯 NorthWest Heating Example

### Their Journey to Cyber Essentials

**Starting point:** No formal security, basic protections only

**Timeline:** 6 weeks from start to certification

**Week 1-2:** Password manager and MFA (following 30-Day Quick Start)

**Week 3-4:** Updated laptops, configured mobile devices, documented processes

**Week 5:** Completed this checklist, gathered evidence

**Week 6:** Applied via IASME, passed first time

**What they documented:**
- "We use Bitwarden for passwords, MFA enabled on email/Xero/banking"
- "Windows Defender on both laptops, auto-updates enabled"
- "BT router with firewall, admin password changed"
- "Company Samsung phones with screen locks and Find My Device"
- "Sarah checks updates first Monday of each month"

**Cost:** £395 for certification + ~30 hours of James and Sarah's time

**Result:** Won a £15k council contract that required Cyber Essentials

---

## 🔗 Related Resources

- [30-Day Quick Start](../implementation/30-day-quick-start.md) - foundation before Cyber Essentials
- [Password Policy](../policies/password-policy.md) - meets CE access control requirements
- [Mobile Device Policy](../policies/06-mobile-device-policy.md) - meets CE mobile device requirements
- [NCSC Cyber Essentials Guidance](https://www.ncsc.gov.uk/cyberessentials/overview)

---

**Remember:** Cyber Essentials is about demonstrating you have basic security hygiene, not perfect security. If you've followed the 30-Day Quick Start, you're most of the way there already.

**Ready to apply? You've got this.**
