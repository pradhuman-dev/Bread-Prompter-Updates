# Privacy Policy for Bread Prompter

**Last Updated:** March 14, 2026
**Policy Version:** 2.1.0
**Extension Version:** 3.0.0

---

> **Quick Summary:** Bread Prompter is a privacy-first Chrome extension. All your data — prompts, API keys, and settings — is stored locally on your device with OS-level encryption. We collect zero personal data, run no tracking, and operate no servers of our own.

---

## Introduction

Bread Prompter is a privacy-first Chrome browser extension that lets you interact with multiple AI chatbot platforms simultaneously — including ChatGPT, Google Gemini, Anthropic Claude, Grok, and DeepSeek — from a single, streamlined interface.

This Privacy Policy explains exactly how we handle your data. The short version: we don't collect it, we don't store it on any server we control, and we don't share it with anyone.

By installing and using Bread Prompter, you agree to the practices described in this policy.

---

## Our Core Privacy Commitment

Bread Prompter is built on three non-negotiable privacy principles:

- **Local-only storage** — all data stays on your device, never on our servers
- **Zero personal data collection** — we do not collect names, emails, IP addresses, or any personally identifiable information (PII)
- **No tracking or analytics** — we do not use cookies, fingerprinting, or behavioral tracking of any kind

---

## Information We Collect

### 1. User-Generated Content (Stored Locally Only)

- **Prompts and text input** — text you type in the extension popup is saved locally on your device via Chrome's `storage.local` API
- **Selected web page text** — when using the summarization feature, selected text is temporarily held in local memory for processing only
- **Speech-to-text data** — voice input is processed entirely in your browser; no audio is ever recorded, stored, or transmitted

### 2. Configuration Data (Stored Locally Only)

- **Groq API key** — if you provide one, it is stored locally using Chrome's encrypted storage API and never transmitted to us
- **Extension preferences** — your enabled AI models, tab group settings, and UI preferences are stored locally

### 3. Browser & Tab Information (Local Use Only)

- **Tab data** — the extension accesses tab information solely to open, group, and manage AI chatbot tabs; this data never leaves your device
- **Login status detection** — the extension detects whether you are logged into supported AI platforms to show status indicators; this information is stored locally and never shared

### 4. What We Do NOT Collect

- No names, email addresses, or contact information
- No IP addresses or device identifiers
- No browsing history outside of supported AI platform tabs
- No usage analytics or telemetry
- No crash reports or diagnostic data sent to our servers

---

## Data Storage & Encryption

All data stored by Bread Prompter uses Chrome's `chrome.storage.local` API. This means:

- Your data is stored on your **local device only** — not in the cloud, not on our servers
- Chrome encrypts local extension storage at the **OS level** (DPAPI on Windows, Keychain on macOS, and equivalent on Linux)
- Data is accessible **only to the Bread Prompter extension** — no other extensions or websites can read it
- All data is **permanently deleted** when you uninstall the extension

We do not implement any additional proprietary encryption on top of Chrome's built-in OS-level encryption. Your API keys and prompts are protected by the same encryption that secures your Chrome profile.

---

## How We Use Your Information

### Local Processing

- **Prompt storage** — your prompts are saved locally to support undo/redo and to restore your last input when you reopen the extension
- **Tab management** — tab data is used to organize AI chatbot tabs into groups and track their state
- **Login detection** — login status is detected to display visual indicators in the extension UI

### External Services (Optional & User-Initiated Only)

Bread Prompter only sends data externally when you explicitly trigger a feature that requires it.

#### Groq API (Optional)

If you provide a Groq API key and use AI-powered features, the following data is sent directly to Groq's API (`api.groq.com`):

- Your text input — when using the **Refine with AI** or **Build Context** features
- Selected web page text — when using the **summarization** feature

We do not have access to your Groq API key or control over Groq's data practices. Please review [Groq's Privacy Policy](https://groq.com/privacy).

#### AI Chatbot Platforms

When you send a prompt through the extension, it is delivered directly to whichever AI platforms you select:

- **ChatGPT** (chatgpt.com, chat.openai.com)
- **Google Gemini** (gemini.google.com)
- **Anthropic Claude** (claude.ai)
- **Grok** (grok.com)
- **DeepSeek** (chat.deepseek.com)

We do not intercept, store, log, or have any access to these prompts or the AI responses you receive. Each platform processes your data under its own privacy policy.

---

## Data Sharing & Disclosure

We do not sell, rent, trade, or share your data with any third party. Specifically:

- We do not sell your data to advertisers or data brokers
- We do not share your data with marketing or analytics companies
- We do not transmit any data to servers we own or operate
- We do not disclose your data to law enforcement except as required by law (and since we hold no data, there is nothing to disclose)

---

## Your Rights & Controls

### Access & Deletion

- **View stored data** — use Chrome DevTools → Application → Extension Storage to inspect `chrome.storage.local`
- **Delete your API key** — remove it through the extension's settings interface
- **Clear all extension data** — go to Chrome Settings → Extensions → Bread Prompter → Clear storage
- **Delete everything** — uninstalling the extension permanently removes all locally stored data

### Opt-Out Options

- **Disable AI features** — simply don't provide a Groq API key; the extension functions fully for prompt broadcasting without it
- **Disable the extension** — toggle it off or uninstall it at any time via `chrome://extensions`

---

## Chrome Permissions Explained

Bread Prompter requests only the permissions it needs to function:

- **`tabs`** — to open, manage, and group AI chatbot tabs
- **`storage`** — to save your prompts, settings, and API key locally on your device
- **`tabGroups`** — to organize AI chatbot tabs into a named group for easy navigation
- **Host permissions** (`chatgpt.com`, `claude.ai`, `gemini.google.com`, `grok.com`, `chat.deepseek.com`) — to detect login status, inject prompts into chat interfaces, and manage tab interactions

No permission is used for tracking, data collection, or any purpose beyond the extension's core features.

---

## Children's Privacy

Bread Prompter is not directed at children under 13. We do not knowingly collect any information from children. If you believe a child has used this extension and provided any personal data, please contact us and we will take appropriate action.

---

## Changes to This Policy

We may update this Privacy Policy as the extension evolves. When we do:

- The "Last Updated" date at the top of this document will be revised
- A notice will be included in the extension's Chrome Web Store update notes
- The updated policy will be published in our GitHub repository

We encourage you to review this policy periodically. Continued use of the extension after changes constitutes acceptance of the updated policy.

---

## Compliance

This Privacy Policy is designed to comply with:

- General Data Protection Regulation (GDPR)
- California Consumer Privacy Act (CCPA)
- Chrome Web Store Developer Program Policies
- Children's Online Privacy Protection Act (COPPA)

---

## Contact

Questions about this policy or our data practices? Reach us through:

- **GitHub Repository:** [https://github.com/pradhuman-dev/Bread-Prompter-Updates]
- **Chrome Web Store:** [https://chromewebstore.google.com/detail/nidjlfajbkinfgdjekhfdfpejeegnfjg?utm_source=item-share-cb]

---

> **In plain English:** Your prompts, API keys, and settings live only on your device, encrypted by your OS. We don't track you. We don't know who you are. We have no servers storing your data. You're in full control.

---

*Effective Date: February 17, 2026 · Extension Version: 3.0.0 · Policy Version: 2.1.0*
