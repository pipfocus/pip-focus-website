# Privacy Policy

**Last updated:** March 29, 2026

## Overview

Pip Focus is committed to protecting your privacy. This extension does not collect, store, or transmit any personal data to external servers.

## Data Collection

**We collect nothing.** Specifically:

- No personal information
- No browsing history
- No analytics or tracking
- No cookies
- No advertising identifiers

## Data Storage

All your data (blocked websites, timer preferences, focus stats, session history) is stored **locally in your browser** using Chrome's built-in storage API (`chrome.storage.local` and `chrome.storage.sync`).

If you're signed into Chrome with a Google account, a small subset of settings may sync across your devices via `chrome.storage.sync`. This syncing is handled entirely by Chrome/Google — Pip Focus does not operate any servers.

## Permissions Explained

Pip Focus requests the following permissions:

| Permission | Why It's Needed |
|------------|-----------------|
| `storage` | Save your blocked sites, preferences, stats, and session history |
| `tabs` | Detect when you visit a blocked site and manage tab state |
| `scripting` | Inject the blocked-page overlay and floating Pip icon on web pages |
| `alarms` | Timer functionality for session countdowns, chime scheduling, and temporary pass expiry |
| `notifications` | Desktop notifications for inactivity nudges |
| `offscreen` | Play the end-of-session chime audio in the background |
| `idle` | Detect screen lock to pause focus time accumulation |
| `declarativeNetRequest` | Required by Manifest V3 for host access; the extension clears dynamic rules and uses overlay-based blocking |
| `host_permissions` (`<all_urls>`) | Required to inject the content script on any website you choose to block |

## Third-Party Services

Pip Focus does **not** use any third-party services, analytics platforms, or external APIs.

## Open Source

For more information, visit our website:
https://pipfocus.github.io/website/

## Data Deletion

No data is collected externally, so there's nothing to delete from our end. To remove all local data, use the **Delete all data** option in Settings, or simply uninstall the extension.

## Changes to This Policy

If we make changes to this privacy policy, we will update the "Last updated" date above.

## Contact

If you have questions about this privacy policy, visit our website:
https://pipfocus.github.io/website/

Twitter: [@pip_focus](https://twitter.com/pip_focus) · Instagram: [@pip_focus](https://instagram.com/pip_focus)

---

**TL;DR:** Pip Focus stores everything locally in your browser. We don't collect any data. Period.
