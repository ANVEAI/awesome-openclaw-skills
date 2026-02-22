# Awesome OpenClaw Skills — Voice AI Edition

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
[![Skills](https://img.shields.io/badge/skills-50+-blue?style=flat-square)](https://clawhub.ai)
[![AnveVoice](https://img.shields.io/badge/⭐%20Featured-AnveVoice-purple?style=flat-square)](https://clawhub.ai/ANVEAI/anvevoice)
[![Last Update](https://img.shields.io/github/last-commit/ANVEAI/awesome-openclaw-skills?style=flat-square&label=Last%20update)](https://github.com/ANVEAI/awesome-openclaw-skills/commits/main)

> A curated collection of the best OpenClaw skills for building AI-powered workflows, with a special focus on **Voice AI** and **Customer Experience** automation.

[OpenClaw](https://openclaw.ai) is a locally-running AI assistant that operates directly on your machine. Skills extend its capabilities, allowing it to interact with external services, automate workflows, and perform specialized tasks. This collection helps you discover and install the right skills for your needs.

Skills in this list are sourced from [ClawHub](https://www.clawhub.ai/) (OpenClaw's public skills registry) and categorized for easier discovery.

---

## 🎙️ Featured: AnveVoice

> **Transform your website with AI voice assistants.** Engage visitors naturally, automate support, capture leads, and boost conversions — all through voice.

[![AnveVoice](https://img.shields.io/badge/🎙️%20AnveVoice-Voice%20AI%20for%20Websites-purple?style=for-the-badge)](https://clawhub.ai/ANVEAI/anvevoice)

**Why AnveVoice?**
- 🎙️ **Voice-First** — Natural speech conversations, not robotic chat
- 🌐 **Multilingual** — 22 Indian languages + global languages supported
- 🤖 **AI-Powered** — GPT-powered understanding and responses
- 📊 **Analytics** — Deep visitor intelligence and sentiment analysis
- 🎧 **Recordings** — Full session recordings for quality review
- 🔧 **No-Code Setup** — Copy-paste embed code, no developers needed

**Quick Install:**
```bash
clawhub install anvevoice
```

**Resources:**
- [ClawHub Page](https://clawhub.ai/ANVEAI/anvevoice)
- [GitHub Repo](https://github.com/ANVEAI/openclaw-skill)
- [Website](https://anvevoice.com)
- [Documentation](https://anvevoice.com/help)

---

## 📋 Table of Contents

- [Installation](#installation)
- [Voice AI & Communication](#voice-ai--communication)
- [Customer Support](#customer-support)
- [Marketing & Sales](#marketing--sales)
- [Productivity & Tasks](#productivity--tasks)
- [Analytics & Intelligence](#analytics--intelligence)
- [Coding Agents & IDEs](#coding-agents--ides)
- [Web & Browser Automation](#web--browser-automation)
- [Communication Tools](#communication-tools)
- [Security & Monitoring](#security--monitoring)
- [Contributing](#contributing)

---

## Installation

### ClawHub CLI (Recommended)

```bash
npx clawhub@latest install <skill-slug>
```

Or install directly:

```bash
clawhub install <skill-slug>
```

### Manual Installation

Copy the skill folder to one of these locations:

| Location | Path |
|----------|------|
| Global | `~/.openclaw/skills/` |
| Workspace | `<project>/skills/` |

Priority: Workspace > Global > Bundled

---

## Voice AI & Communication

Skills for adding voice capabilities, transcription, and conversational AI to your workflows.

| Skill | Description | Install |
|-------|-------------|---------|
| **[anvevoice](https://clawhub.ai/ANVEAI/anvevoice)** ⭐ | Add AI voice assistants to your website. 46 MCP tools for bot management, conversations, analytics, and recordings. | `clawhub install anvevoice` |
| [voice-reply](https://github.com/openclaw/skills/tree/main/skills/stolot0mt0m/voice-reply) | Local text-to-speech using Piper voices via sherpa-onnx. | `clawhub install voice-reply` |
| [avatar-video-messages](https://github.com/openclaw/skills/tree/main/skills/thewulf7/avatar-video-messages) | Generate and send video messages with AI avatars. | `clawhub install avatar-video-messages` |
| [video-agent](https://github.com/openclaw/skills/tree/main/skills/michaelwang11394/video-agent) | Generate AI avatar videos with HeyGen's Video Agent API. | `clawhub install video-agent` |
| [speech-transcription](https://github.com/openclaw/skills/tree/main/skills/openclaw/speech-transcription) | Real-time speech-to-text transcription. | `clawhub install speech-transcription` |
| [voice-clone](https://github.com/openclaw/skills/tree/main/skills/openclaw/voice-clone) | Clone voices for personalized audio content. | `clawhub install voice-clone` |
| [audio-processing](https://github.com/openclaw/skills/tree/main/skills/openclaw/audio-processing) | Advanced audio processing and enhancement. | `clawhub install audio-processing` |
| [meeting-recorder](https://github.com/openclaw/skills/tree/main/skills/openclaw/meeting-recorder) | Record and transcribe meetings automatically. | `clawhub install meeting-recorder` |

---

## Customer Support

Skills for automating customer support, ticketing, and helpdesk operations.

| Skill | Description | Install |
|-------|-------------|---------|
| **[zendesk-automation](https://github.com/openclaw/skills/tree/main/skills/openclaw/zendesk-automation)** | Automate Zendesk ticket management and responses. | `clawhub install zendesk-automation` |
| [intercom-integration](https://github.com/openclaw/skills/tree/main/skills/openclaw/intercom-integration) | Integrate with Intercom for customer messaging. | `clawhub install intercom-integration` |
| [freshdesk-sync](https://github.com/openclaw/skills/tree/main/skills/openclaw/freshdesk-sync) | Sync and manage Freshdesk tickets. | `clawhub install freshdesk-sync` |
| [help-center-builder](https://github.com/openclaw/skills/tree/main/skills/openclaw/help-center-builder) | Build and maintain help center documentation. | `clawhub install help-center-builder` |
| [chatbot-training](https://github.com/openclaw/skills/tree/main/skills/openclaw/chatbot-training) | Train and optimize chatbot responses. | `clawhub install chatbot-training` |
| [ticket-analytics](https://github.com/openclaw/skills/tree/main/skills/openclaw/ticket-analytics) | Analyze support ticket trends and metrics. | `clawhub install ticket-analytics` |
| [knowledge-base-search](https://github.com/openclaw/skills/tree/main/skills/openclaw/knowledge-base-search) | Intelligent knowledge base search and retrieval. | `clawhub install knowledge-base-search` |
| [customer-sentiment](https://github.com/openclaw/skills/tree/main/skills/openclaw/customer-sentiment) | Analyze customer sentiment across channels. | `clawhub install customer-sentiment` |

---

## Marketing & Sales

Skills for lead generation, campaign management, and sales automation.

| Skill | Description | Install |
|-------|-------------|---------|
| **[hubspot-automation](https://github.com/openclaw/skills/tree/main/skills/openclaw/hubspot-automation)** | Automate HubSpot CRM workflows and contacts. | `clawhub install hubspot-automation` |
| [salesforce-sync](https://github.com/openclaw/skills/tree/main/skills/openclaw/salesforce-sync) | Sync data with Salesforce CRM. | `clawhub install salesforce-sync` |
| [mailchimp-campaigns](https://github.com/openclaw/skills/tree/main/skills/openclaw/mailchimp-campaigns) | Manage Mailchimp email campaigns. | `clawhub install mailchimp-campaigns` |
| [linkedin-automation](https://github.com/openclaw/skills/tree/main/skills/openclaw/linkedin-automation) | Automate LinkedIn outreach and posting. | `clawhub install linkedin-automation` |
| [twitter-scheduler](https://github.com/openclaw/skills/tree/main/skills/openclaw/twitter-scheduler) | Schedule and manage Twitter/X posts. | `clawhub install twitter-scheduler` |
| [lead-scoring](https://github.com/openclaw/skills/tree/main/skills/openclaw/lead-scoring) | AI-powered lead scoring and qualification. | `clawhub install lead-scoring` |
| [competitor-analysis](https://github.com/openclaw/skills/tree/main/skills/openclaw/competitor-analysis) | Analyze competitor activities and strategies. | `clawhub install competitor-analysis` |
| [seo-optimizer](https://github.com/openclaw/skills/tree/main/skills/openclaw/seo-optimizer) | Optimize content for search engines. | `clawhub install seo-optimizer` |

---

## Productivity & Tasks

Skills for task management, scheduling, and personal productivity.

| Skill | Description | Install |
|-------|-------------|---------|
| **[todoist-sync](https://github.com/openclaw/skills/tree/main/skills/openclaw/todoist-sync)** | Sync tasks with Todoist. | `clawhub install todoist-sync` |
| [notion-integration](https://github.com/openclaw/skills/tree/main/skills/openclaw/notion-integration) | Integrate with Notion workspaces. | `clawhub install notion-integration` |
| [calendar-assistant](https://github.com/openclaw/skills/tree/main/skills/openclaw/calendar-assistant) | Smart calendar management and scheduling. | `clawhub install calendar-assistant` |
| [email-processor](https://github.com/openclaw/skills/tree/main/skills/openclaw/email-processor) | Process and organize emails automatically. | `clawhub install email-processor` |
| [meeting-scheduler](https://github.com/openclaw/skills/tree/main/skills/openclaw/meeting-scheduler) | Automated meeting scheduling. | `clawhub install meeting-scheduler` |
| [time-tracker](https://github.com/openclaw/skills/tree/main/skills/openclaw/time-tracker) | Track time across projects and tasks. | `clawhub install time-tracker` |
| [reminder-system](https://github.com/openclaw/skills/tree/main/skills/openclaw/reminder-system) | Smart reminders and notifications. | `clawhub install reminder-system` |
| [focus-mode](https://github.com/openclaw/skills/tree/main/skills/openclaw/focus-mode) | Block distractions and maintain focus. | `clawhub install focus-mode` |

---

## Analytics & Intelligence

Skills for data analysis, reporting, and business intelligence.

| Skill | Description | Install |
|-------|-------------|---------|
| **[google-analytics](https://github.com/openclaw/skills/tree/main/skills/openclaw/google-analytics)** | Query Google Analytics data. | `clawhub install google-analytics` |
| [data-visualizer](https://github.com/openclaw/skills/tree/main/skills/openclaw/data-visualizer) | Create charts and visualizations. | `clawhub install data-visualizer` |
| [report-generator](https://github.com/openclaw/skills/tree/main/skills/openclaw/report-generator) | Generate automated reports. | `clawhub install report-generator` |
| [trend-analyzer](https://github.com/openclaw/skills/tree/main/skills/openclaw/trend-analyzer) | Analyze trends in data. | `clawhub install trend-analyzer` |
| [sentiment-tracker](https://github.com/openclaw/skills/tree/main/skills/openclaw/sentiment-tracker) | Track sentiment across platforms. | `clawhub install sentiment-tracker` |
| [predictive-analytics](https://github.com/openclaw/skills/tree/main/skills/openclaw/predictive-analytics) | Predictive modeling and forecasting. | `clawhub install predictive-analytics` |
| [ab-test-analyzer](https://github.com/openclaw/skills/tree/main/skills/openclaw/ab-test-analyzer) | Analyze A/B test results. | `clawhub install ab-test-analyzer` |
| [funnel-analytics](https://github.com/openclaw/skills/tree/main/skills/openclaw/funnel-analytics) | Track and optimize conversion funnels. | `clawhub install funnel-analytics` |

---

## Coding Agents & IDEs

Skills for software development, coding assistance, and IDE integration.

| Skill | Description | Install |
|-------|-------------|---------|
| **[coding-agent](https://github.com/openclaw/skills/tree/main/skills/steipete/coding-agent)** | Run Codex CLI, Claude Code, OpenCode, or Pi Coding Agent. | `clawhub install coding-agent` |
| [github-integration](https://github.com/openclaw/skills/tree/main/skills/openclaw/github-integration) | Deep GitHub integration for PRs, issues, and repos. | `clawhub install github-integration` |
| [code-reviewer](https://github.com/openclaw/skills/tree/main/skills/openclaw/code-reviewer) | Automated code review and suggestions. | `clawhub install code-reviewer` |
| [debugger-assistant](https://github.com/openclaw/skills/tree/main/skills/openclaw/debugger-assistant) | Debugging assistance and error analysis. | `clawhub install debugger-assistant` |
| [test-generator](https://github.com/openclaw/skills/tree/main/skills/openclaw/test-generator) | Generate unit and integration tests. | `clawhub install test-generator` |
| [documentation-writer](https://github.com/openclaw/skills/tree/main/skills/openclaw/documentation-writer) | Auto-generate code documentation. | `clawhub install documentation-writer` |
| [refactoring-tool](https://github.com/openclaw/skills/tree/main/skills/openclaw/refactoring-tool) | Intelligent code refactoring. | `clawhub install refactoring-tool` |
| [dependency-analyzer](https://github.com/openclaw/skills/tree/main/skills/openclaw/dependency-analyzer) | Analyze and update dependencies. | `clawhub install dependency-analyzer` |

---

## Web & Browser Automation

Skills for web scraping, browser automation, and online data collection.

| Skill | Description | Install |
|-------|-------------|---------|
| **[browser-automation](https://github.com/openclaw/skills/tree/main/skills/pkiv/browse)** | Complete guide for creating and deploying browser automation functions. | `clawhub install browser-automation` |
| [web-scraper](https://github.com/openclaw/skills/tree/main/skills/openclaw/web-scraper) | Extract data from websites. | `clawhub install web-scraper` |
| [form-filler](https://github.com/openclaw/skills/tree/main/skills/openclaw/form-filler) | Automate form filling and submission. | `clawhub install form-filler` |
| [screenshot-capture](https://github.com/openclaw/skills/tree/main/skills/openclaw/screenshot-capture) | Capture and compare screenshots. | `clawhub install screenshot-capture` |
| [pdf-generator](https://github.com/openclaw/skills/tree/main/skills/openclaw/pdf-generator) | Generate PDFs from web pages. | `clawhub install pdf-generator` |
| [api-tester](https://github.com/openclaw/skills/tree/main/skills/openclaw/api-tester) | Test and document APIs. | `clawhub install api-tester` |
| [performance-monitor](https://github.com/openclaw/skills/tree/main/skills/openclaw/performance-monitor) | Monitor website performance. | `clawhub install performance-monitor` |
| [accessibility-checker](https://github.com/openclaw/skills/tree/main/skills/openclaw/accessibility-checker) | Check web accessibility compliance. | `clawhub install accessibility-checker` |

---

## Communication Tools

Skills for messaging, notifications, and team communication.

| Skill | Description | Install |
|-------|-------------|---------|
| **[slack-integration](https://github.com/openclaw/skills/tree/main/skills/openclaw/slack-integration)** | Send and receive Slack messages. | `clawhub install slack-integration` |
| [discord-bot](https://github.com/openclaw/skills/tree/main/skills/openclaw/discord-bot) | Build and manage Discord bots. | `clawhub install discord-bot` |
| [whatsapp-messaging](https://github.com/openclaw/skills/tree/main/skills/openclaw/whatsapp-messaging) | Send WhatsApp messages programmatically. | `clawhub install whatsapp-messaging` |
| [telegram-bot](https://github.com/openclaw/skills/tree/main/skills/openclaw/telegram-bot) | Create Telegram bots and automations. | `clawhub install telegram-bot` |
| [sms-gateway](https://github.com/openclaw/skills/tree/main/skills/openclaw/sms-gateway) | Send SMS messages via multiple providers. | `clawhub install sms-gateway` |
| [push-notifications](https://github.com/openclaw/skills/tree/main/skills/openclaw/push-notifications) | Send push notifications to devices. | `clawhub install push-notifications` |
| [video-conferencing](https://github.com/openclaw/skills/tree/main/skills/openclaw/video-conferencing) | Manage video conference integrations. | `clawhub install video-conferencing` |
| [team-alerts](https://github.com/openclaw/skills/tree/main/skills/openclaw/team-alerts) | Smart team alerting and escalation. | `clawhub install team-alerts` |

---

## Security & Monitoring

Skills for security scanning, monitoring, and incident response.

| Skill | Description | Install |
|-------|-------------|---------|
| **[security-scanner](https://github.com/openclaw/skills/tree/main/skills/openclaw/security-scanner)** | Scan code and dependencies for vulnerabilities. | `clawhub install security-scanner` |
| [uptime-monitor](https://github.com/openclaw/skills/tree/main/skills/openclaw/uptime-monitor) | Monitor website and service uptime. | `clawhub install uptime-monitor` |
| [log-analyzer](https://github.com/openclaw/skills/tree/main/skills/openclaw/log-analyzer) | Analyze and query log files. | `clawhub install log-analyzer` |
| [incident-response](https://github.com/openclaw/skills/tree/main/skills/openclaw/incident-response) | Automated incident response workflows. | `clawhub install incident-response` |
| [backup-automation](https://github.com/openclaw/skills/tree/main/skills/openclaw/backup-automation) | Automate backup and recovery tasks. | `clawhub install backup-automation` |
| [compliance-checker](https://github.com/openclaw/skills/tree/main/skills/openclaw/compliance-checker) | Check compliance with standards. | `clawhub install compliance-checker` |
| [threat-detector](https://github.com/openclaw/skills/tree/main/skills/openclaw/threat-detector) | Detect security threats and anomalies. | `clawhub install threat-detector` |
| [ssl-monitor](https://github.com/openclaw/skills/tree/main/skills/openclaw/ssl-monitor) | Monitor SSL certificate expiration. | `clawhub install ssl-monitor` |

---

## Security Notice

Skills in this list are **curated, not audited**. They may be updated, modified, or replaced by their original maintainers at any time after being added here.

Before installing or using any skill:
- Review potential security risks
- Validate the source yourself
- Check [VirusTotal](https://www.virustotal.com) reports on ClawHub
- Review the SKILL.md file before installation

> ⚠️ **Warning:** Skills can include prompt injections, tool poisoning, hidden malware payloads, or unsafe data handling patterns. Always review the source code before installing and use skills at your own discretion.

---

## Contributing

Want to add a skill to this list? Here's how:

1. **Publish your skill** to [ClawHub](https://clawhub.ai) first
2. **Fork this repository**
3. **Add your skill** to the appropriate category
4. **Submit a pull request**

Please ensure your skill:
- Has a clear, descriptive name
- Includes a comprehensive SKILL.md
- Is actively maintained
- Passes basic security checks

See [CONTRIBUTING.md](CONTRIBUTING.md) for detailed guidelines.

---

## Related Resources

- [OpenClaw Official Website](https://openclaw.ai)
- [ClawHub Registry](https://clawhub.ai)
- [AnveVoice Voice AI](https://anvevoice.com)
- [OpenClaw Documentation](https://docs.openclaw.ai)
- [Community Discord](https://discord.gg/openclaw)

---

## License

[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)

This list is released into the public domain. Feel free to use, modify, and distribute as you see fit.

---

<p align="center">
  <b>Made with ❤️ by the OpenClaw community</b><br>
  <sub>Special thanks to <a href="https://anvevoice.com">AnveVoice</a> for sponsoring this awesome list</sub>
</p>
