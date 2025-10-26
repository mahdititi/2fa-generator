# Privacy Policy for 2FA Code Generator

**Current Version:** 1.2.0  
**Last Updated:** October 26, 2025

---

## 📋 What Changed in v1.2.0

New permissions added for enhanced functionality:
- **Context Menus** - Right-click feature for instant code generation
- **Active Tab** - Required for clipboard access via context menu
- **Scripting** - Enables clipboard functionality in active page
- **Notifications** - Shows confirmation messages

**Important:** All data remains 100% local - no collection, no tracking, no external servers.

---

## Version History

| Version | Date | Summary |
|---------|------|---------|
| **1.2.0** | Oct 26, 2025 | Added context menu permissions |
| 1.1.0 | Oct 25, 2025 | Initial privacy policy |

---

## Overview

2FA Code Generator is a browser extension designed to generate Time-based One-Time Passwords (TOTP) for two-factor authentication. We are deeply committed to protecting your privacy and ensuring the security of your data.

**Our Core Promise: Your data stays with you. Always.**

---

## What We Do NOT Do

❌ We do NOT collect any personal information  
❌ We do NOT track your browsing activity  
❌ We do NOT send data to external servers  
❌ We do NOT use analytics or tracking tools  
❌ We do NOT store data on remote servers  
❌ We do NOT share data with third parties  
❌ We do NOT sell your information  
❌ We do NOT require account registration  
❌ We do NOT use cookies for tracking  

---

## Data Storage

### Session Storage (Temporary)
Your 2FA secret keys are stored locally in your browser using Chrome's session storage API:
- **Storage Location:** Local browser storage only
- **Duration:** Until you close your browser
- **Access:** Only you have access - stored on your device only
- **Transmission:** Never transmitted over the network
- **Deletion:** Automatically cleared when browser closes

### No Permanent Storage
- We do not use persistent local storage
- We do not create backups of your data
- We do not sync data across devices
- We do not maintain any databases

---

## Permissions Explained

We request only the minimum permissions necessary for functionality:

### 1. Storage Permission
- **Purpose:** To temporarily store your 2FA secret key in session storage
- **Scope:** Local browser only, no external access
- **Duration:** Cleared automatically when you close your browser
- **Usage:** Allows the extension to remember your key during your browsing session

### 2. Context Menus Permission
- **Purpose:** Adds "Copy 2FA" option to your right-click menu
- **Scope:** Only appears when text is selected
- **Usage:** Enables quick code generation from selected text
- **Data Access:** Only reads the text you explicitly select

### 3. Active Tab Permission
- **Purpose:** Required to copy generated codes to clipboard via context menu
- **Scope:** Only active when you use the "Copy 2FA" context menu
- **Usage:** Injects minimal code to enable clipboard functionality
- **Data Access:** Does not read or access page content beyond clipboard operation

### 4. Scripting Permission
- **Purpose:** Enables clipboard copy functionality when using context menu
- **Scope:** Temporary injection only during clipboard operation
- **Usage:** Executes a single clipboard write command
- **Data Access:** No access to page data, only performs clipboard write

### 5. Notifications Permission
- **Purpose:** Shows confirmation messages when codes are generated
- **Scope:** Local notifications only
- **Usage:** Displays success/error messages for user feedback
- **Data Access:** None - only displays information you just requested

**Important:** We use permissions ONLY for their stated purposes. We never abuse permissions to collect data or track behavior.

---

## How Your Data is Protected

### Technical Security Measures
- ✓ All cryptographic operations performed locally in your browser
- ✓ Uses industry-standard TOTP algorithm (RFC 6238)
- ✓ No network communication of sensitive data
- ✓ Session-only storage (automatically cleared)
- ✓ No external dependencies for core functionality
- ✓ Minimal permission scope

### Privacy by Design
- All code executes locally on your device
- No servers to store or process your data
- No user accounts or login systems
- No third-party integrations
- Open and transparent operation

---

## Third-Party Services

**We use ZERO third-party services.**

- No analytics providers (Google Analytics, etc.)
- No advertising networks
- No social media integrations
- No external APIs
- No CDN dependencies for tracking
- No error reporting services that collect data

---

## What Happens to Your Secret Keys

1. **You paste/type** your secret key into the extension
2. **Extension stores** it temporarily in browser session storage
3. **Extension generates** codes locally using the key
4. **You close browser** → Key is automatically deleted
5. **Next session** → Start fresh with no stored data

**Your secret keys:**
- Never leave your device
- Never sent over the internet
- Never stored permanently
- Never accessible to websites you visit
- Never shared with the extension developers

---

## Children's Privacy

This extension does not knowingly collect any information from anyone, including children under 13. Since we collect no data at all, this extends to users of all ages.

---

## International Data Transfers

Since we do not collect any data, there are no international data transfers of any kind.

---

## Data Retention

**Retention Period:** Until you close your browser (session only)

**Deletion:** Automatic upon browser closure. You can also:
- Clear browser data manually at any time
- Uninstall the extension to remove all data
- Close individual browser windows to clear session data

---

## Your Rights

Under GDPR, CCPA, and other privacy laws, you have rights regarding your personal data. Since we do not collect any personal data:

- **Right to Access:** No data to access
- **Right to Deletion:** Data auto-deletes on browser close
- **Right to Portability:** No data to export
- **Right to Opt-Out:** Nothing to opt out from
- **Right to Know:** This policy explains everything we do (nothing)

---

## Changes to This Policy

We may update this privacy policy when:
- Adding new features that require different permissions
- Clarifying existing practices
- Complying with new legal requirements

**Notification Method:**
- Updated "Last Updated" date on this page
- Version number increment
- Notification in extension update notes

You can always find the latest version on the Chrome Web Store.

---

## Compliance

This extension complies with:
- ✓ Chrome Web Store Developer Program Policies
- ✓ General Data Protection Regulation (GDPR)
- ✓ California Consumer Privacy Act (CCPA)
- ✓ Privacy Shield Principles
- ✓ Best practices for browser extension privacy

---

## Contact & Support

**Questions about privacy?** Contact us through:
- Chrome Web Store support page
- Extension feedback system

**We commit to:**
- Responding to all privacy inquiries within 48 hours
- Taking privacy concerns seriously
- Transparent communication about our practices

---

## Transparency Commitment

We believe in complete transparency:

**You can verify our privacy claims by:**
1. Reviewing the extension's code (visible in Chrome)
2. Using browser developer tools to monitor network activity (you'll see zero external requests)
3. Checking browser storage (only session storage, no persistent data)
4. Reading this policy thoroughly

**We challenge you to find any privacy violation - there are none.**

---

## Summary (TL;DR)

**In Plain English:**
- We don't collect anything
- Everything stays on your computer
- Your data is automatically deleted when you close your browser
- We don't track you
- We don't sell anything
- We don't have servers storing your data
- You're in complete control

**That's it. Simple. Private. Secure.**

---

*This privacy policy is effective as of the date listed above and applies to version 1.2.0 and later of the 2FA Code Generator extension.*
