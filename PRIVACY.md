# Privacy Policy for Auto Clicker Chrome Extension

**Last Updated**: December 18, 2025

## Overview

Auto Clicker is committed to protecting your privacy. This Privacy Policy explains how our Chrome extension handles data.

## Data Collection

**We do NOT collect any personal data.**

The Auto Clicker extension:
- ❌ Does NOT collect personal information
- ❌ Does NOT track your browsing activity
- ❌ Does NOT send data to external servers
- ❌ Does NOT use cookies or analytics
- ❌ Does NOT share data with third parties

## Data Storage

### Local Storage Only

The extension stores the following data **locally on your device only**:

1. **Click Interval Setting**
   - Your preferred click interval (in milliseconds)
   - Stored in: `chrome.storage.local`

2. **Random Interval Setting**
   - Whether random intervals are enabled
   - Minimum and maximum interval values
   - Stored in: `chrome.storage.local`

3. **Language Preference**
   - Your selected interface language
   - Stored in: `chrome.storage.local`

### Data Access

All stored data:
- Remains on your local device
- Is never transmitted over the network
- Is not accessible to the extension developers
- Can be cleared by removing the extension
- Can be reset through Chrome's extension settings

## Permissions Explained

The extension requires the following permissions:

### activeTab
- **Purpose**: To inject the auto-clicker script into the active webpage
- **Scope**: Only works on the tab where you activate the shortcut
- **Data Access**: No data is read or collected from pages

### storage
- **Purpose**: To save your settings (interval, language, etc.)
- **Scope**: Local device storage only
- **Data Access**: Only stores your preferences

### scripting
- **Purpose**: To execute the auto-clicking functionality on web pages
- **Scope**: Only active when you trigger the keyboard shortcut
- **Data Access**: No data is read from web pages

### host_permissions: <all_urls>
- **Purpose**: To allow the auto-clicker to work on any website you choose
- **Scope**: Only activates when you use the keyboard shortcut
- **Data Access**: No browsing data is collected or transmitted

## Third-Party Services

This extension does NOT use any third-party services, including:
- ❌ No analytics services (e.g., Google Analytics)
- ❌ No advertising networks
- ❌ No crash reporting services
- ❌ No external APIs

## Security

- All code runs locally in your browser
- No external network connections are made
- Settings are encrypted by Chrome's storage API
- Open source code available for audit

## Children's Privacy

This extension does not knowingly collect information from children under 13. The extension is suitable for all ages as it does not collect any personal information.

## Changes to Privacy Policy

We may update this Privacy Policy from time to time. Changes will be reflected in the "Last Updated" date at the top of this document. Continued use of the extension after changes constitutes acceptance of the updated policy.

## Data Deletion

To delete all data stored by this extension:

1. **Remove Settings**: Right-click the extension icon → Remove from Chrome
2. **Clear Storage**: Chrome Settings → Privacy and Security → Site Settings → View permissions and data stored across sites → Remove the extension

## Your Rights

You have the right to:
- Know what data is stored (see "Data Storage" section)
- Delete your data at any time (by removing the extension)
- Use the extension without providing personal information

## Compliance

This extension complies with:
- Chrome Web Store Developer Program Policies
- General Data Protection Regulation (GDPR)
- California Consumer Privacy Act (CCPA)
- Children's Online Privacy Protection Act (COPPA)

## Contact

For privacy-related questions or concerns:
- GitHub: [Open an issue](#)
- Email: [your-email@example.com]

## Transparency

The complete source code of this extension is available for review, ensuring full transparency about what the extension does with your data (which is nothing).

---

## Summary

**TL;DR**: Auto Clicker does not collect, transmit, or share any of your data. All settings are stored locally on your device. Your privacy is 100% protected.

---

**Your trust is important to us. This extension is designed with privacy as the top priority.**
