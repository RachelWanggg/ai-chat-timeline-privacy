# Privacy Policy — AI Chat Timeline

**Last updated:** April 15, 2026

## Overview

AI Chat Timeline ("the Extension") is a Chrome browser extension that adds
structured timeline navigation to AI chat interfaces. We are committed to
protecting your privacy. This policy explains what data the Extension
accesses, how it is used, and what is never collected.

## Data We Access

### Website Content (Read-Only)
The Extension reads the text content of AI chat messages on the following
domains only:
- claude.ai
- chatgpt.com
- chat.openai.com

This content is processed **locally in your browser** solely to build the
navigation timeline. It is never transmitted to any external server, never
stored remotely, and never shared with any third party.

### Locally Stored Data
The Extension stores the following data on your device using the browser's
built-in `chrome.storage.local` API:

| Data | Purpose |
|------|---------|
| Pinned anchors | Remember which timeline items you pinned, per conversation URL |
| Prompt library | Save and reuse your custom prompt templates |
| Theme preference | Remember your light/dark mode setting |
| API key | Store your API key locally to enable AI-powered features |

**All data is stored exclusively on your local device.** It is never
transmitted to any external server, never synced to any cloud service,
and is never accessible to the extension's developers.

## API Key

If you choose to enter an API key, it is:
- Stored only in `chrome.storage.local` on your device
- Used solely to make requests directly from your browser to the
  Anthropic API to revise and improve your prompt templates
- Never sent to any server operated by this extension
- Never shared with any third party

The prompt text you choose to revise is sent directly from your browser
to Anthropic's API. Please refer to Anthropic's privacy policy at
https://www.anthropic.com/privacy for how they handle your data.

You can remove your API key at any time by clearing it in the
extension settings.

## Data We Do NOT Collect

We do not collect, transmit, or store:

- Personally identifiable information (name, email, address)
- Authentication credentials or passwords unrelated to your API key
- Browsing history outside of the three supported AI chat domains
- Financial or payment information
- Location data
- Any analytics or telemetry

## Third Parties

This Extension does not integrate with any third-party analytics,
advertising, or tracking services. No user data is sold or transferred
to any third party under any circumstances.

When you use your API key, requests are sent directly from your browser
to the API provider (e.g. Anthropic). Please refer to their privacy
policy for how they handle your data.

## Remote Code

This Extension does not load or execute any remote code. All functionality
is contained within the extension package itself.

## Children's Privacy

This Extension does not knowingly collect any data from children under
the age of 13.

## Changes to This Policy

If this policy changes in the future, the updated version will be published
at this URL with a revised "Last updated" date.

## Contact

If you have any questions about this privacy policy, please open an issue at:
[https://github.com/RachelWanggg/AI-chat-timeline-extension/issues](https://github.com/RachelWanggg/AI-chat-timeline-extension/issues)

## Contact

If you have any questions about this privacy policy, please open an issue 
at:
https://github.com/RachelWanggg/ai-chat-timeline-privacy/issues
