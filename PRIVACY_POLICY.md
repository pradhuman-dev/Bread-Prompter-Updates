# Privacy Policy for Bread Prompter

**Last Updated:** [Date]  
**Version:** 1.0.0

## Introduction

Bread Prompter ("we," "our," or "the Extension") is a Chrome browser extension that helps users interact with multiple AI chatbot platforms simultaneously. This Privacy Policy explains how we collect, use, store, and protect your information when you use our extension.

By using Bread Prompter, you agree to the collection and use of information in accordance with this policy.

## Information We Collect

### 1. User-Generated Content
- **Prompts and Text Input**: The extension stores the text you enter in the extension's popup interface locally on your device using Chrome's local storage API (`chrome.storage.local`).
- **Selected Web Page Text**: When you use the summarization feature, text you select from web pages is temporarily stored locally for processing.
- **Speech-to-Text Data**: If you use the voice input feature, audio is processed locally in your browser and converted to text. Audio data is not stored or transmitted.

### 2. Configuration Data
- **API Keys**: If you choose to enable AI-powered features (text refinement, context building), you may provide a Groq API key. This key is stored locally on your device using Chrome's local storage API.
- **Extension Settings**: Your preferences for enabled/disabled AI models, tab group configurations, and other extension settings are stored locally.

### 3. Tab and Browser Information
- **Tab Information**: The extension accesses tab information to manage AI chatbot tabs and organize them into groups. This information is used locally and not transmitted externally.
- **Login Status**: The extension detects whether you are logged into supported AI platforms (ChatGPT, Gemini, Claude, Grok, DeepSeek) to provide status indicators. This information is stored locally and not shared.

### 4. Technical Data
- **Extension State**: Internal state information (such as which AI models are enabled, tab group IDs) is stored locally to maintain extension functionality.

## How We Use Your Information

### Local Processing
- **Prompt Storage**: Your prompts are stored locally to enable features like undo/redo functionality and to restore your previous input when you reopen the extension.
- **Tab Management**: Tab information is used to organize AI chatbot tabs into groups and manage their state.
- **Login Detection**: Login status is detected to provide visual indicators in the extension interface.

### External Services

#### 1. Groq API (Optional)
If you provide a Groq API key and enable AI-powered features, the following data is sent to Groq's API service (`api.groq.com`):
- **Text Refinement**: When you use the "Refine with AI" feature, your text input is sent to Groq's API to generate an improved prompt.
- **Context Building**: When you use the "Build Context" feature, your initial prompt and selected answers to multiple-choice questions are sent to Groq's API to generate contextual prompts.
- **Summarization**: When you use summarization features, selected text from web pages is sent to Groq's API.

**Note**: Your Groq API key is used to authenticate requests to Groq's service. We do not have access to your API key or control over how Groq processes your data. Please review [Groq's Privacy Policy](https://groq.com/privacy) to understand how they handle your data.

#### 2. AI Chatbot Platforms
When you send prompts through the extension, your prompts are sent directly to the selected AI chatbot platforms:
- **ChatGPT** (chatgpt.com, chat.openai.com)
- **Google Gemini** (gemini.google.com)
- **Anthropic Claude** (claude.ai)
- **Grok** (grok.com)
- **DeepSeek** (chat.deepseek.com)

These platforms process your prompts according to their respective privacy policies. We do not intercept, store, or have access to the responses from these platforms.

## Data Storage and Security

### Local Storage
All data collected by the extension is stored locally on your device using Chrome's `chrome.storage.local` API. This includes:
- User prompts
- API keys (if provided)
- Extension settings
- Login status information
- Selected text for summarization

**Important**: Data stored in `chrome.storage.local` is:
- Stored on your local device only
- Not encrypted by default (Chrome encrypts storage at the OS level)
- Accessible only to this extension
- Deleted if you uninstall the extension

### Security Measures
- We do not transmit your data to any servers we control
- API keys are stored locally and used only to authenticate requests to third-party services
- We do not collect, store, or transmit personal identifying information
- All data processing occurs either locally in your browser or through the third-party services you choose to use

## Data Sharing and Disclosure

We do not:
- Sell your data to third parties
- Share your data with advertisers
- Transmit your data to servers we control
- Access your data except as necessary for extension functionality

### Third-Party Services
When you use AI-powered features, your data is sent to:
- **Groq API** (if you provide an API key): For text refinement and context generation
- **AI Chatbot Platforms**: For sending prompts and receiving responses

These services have their own privacy policies and terms of service. We are not responsible for how these third parties handle your data.

## Your Rights and Choices

### Access and Control
- **View Stored Data**: You can view data stored by the extension using Chrome's developer tools or by inspecting `chrome.storage.local`.
- **Delete Data**: You can delete stored data by:
  - Removing your API key through the extension's interface
  - Clearing extension data in Chrome's extension settings
  - Uninstalling the extension (which removes all stored data)

### Opt-Out Options
- **Disable AI Features**: You can disable AI-powered features by removing your API key or not providing one. The extension will continue to function for basic prompt broadcasting without AI features.
- **Disable Extension**: You can disable or uninstall the extension at any time through Chrome's extension management page.

## Permissions Explanation

The extension requires the following permissions:

- **`tabs`**: To open, manage, and organize AI chatbot tabs into groups
- **`storage`**: To store your prompts, settings, and API keys locally on your device
- **`tabGroups`**: To organize AI chatbot tabs into a dedicated tab group
- **Host Permissions**: To access AI chatbot platforms (chatgpt.com, claude.ai, gemini.google.com, grok.com, chat.deepseek.com) for:
  - Detecting login status
  - Injecting prompts into the chat interfaces
  - Managing tab interactions

These permissions are necessary for the extension's core functionality and are not used for any other purpose.

## Children's Privacy

Bread Prompter is not intended for use by children under the age of 13. We do not knowingly collect personal information from children. If you are a parent or guardian and believe your child has provided us with personal information, please contact us to have that information removed.

## Changes to This Privacy Policy

We may update this Privacy Policy from time to time. We will notify you of any changes by:
- Updating the "Last Updated" date at the top of this policy
- Posting the new Privacy Policy in the extension's repository
- Including a notice in the extension's update notes (if applicable)

You are advised to review this Privacy Policy periodically for any changes. Changes to this Privacy Policy are effective when they are posted.

## Data Retention

- **Local Storage**: Data stored locally remains on your device until:
  - You manually delete it
  - You uninstall the extension
  - You clear Chrome's extension data
  - You clear your browser's local storage

- **Third-Party Services**: We do not control how long third-party services (Groq, AI chatbot platforms) retain your data. Please refer to their respective privacy policies.

## International Data Transfers

When you use AI-powered features, your data may be processed by third-party services located outside your country of residence. By using these features, you consent to the transfer of your data to these services.

## Contact Information

If you have any questions about this Privacy Policy or our data practices, please contact us through:
- **GitHub Repository**: [Your Repository URL]
- **Chrome Web Store**: [Your Extension Page URL]

## Compliance

This Privacy Policy is designed to comply with:
- General Data Protection Regulation (GDPR)
- California Consumer Privacy Act (CCPA)
- Chrome Web Store Developer Program Policies

## Disclaimer

Bread Prompter is provided "as is" without warranties of any kind. We are not responsible for:
- How third-party AI services (Groq, ChatGPT, Gemini, Claude, Grok, DeepSeek) process or store your data
- The accuracy or quality of AI-generated responses
- Any data breaches or security incidents involving third-party services

## Summary

**In simple terms:**
- All your data (prompts, API keys, settings) is stored locally on your device
- We don't send your data to any servers we control
- When you use AI features, your data goes directly to Groq's API (if you provide an API key)
- When you send prompts, they go directly to the AI chatbot platforms you select
- You can delete all your data by uninstalling the extension
- We don't track you, sell your data, or use it for advertising

---

**Effective Date:** [Date]  
**Extension Version:** 1.0.0  
**Policy Version:** 1.0
