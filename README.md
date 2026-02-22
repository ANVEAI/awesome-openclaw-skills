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

## 📚 Category-Specific Collections

Looking for skills tailored to your role? Check out these curated collections:

| Collection | Target Audience | Skills | Link |
|------------|-----------------|--------|------|
| **Developer Skills** | Software engineers, DevOps | 50+ | [github.com/ANVEAI/openclaw-developer-skills](https://github.com/ANVEAI/openclaw-developer-skills) |
| **Marketing Skills** | Growth marketers, SEO | 50+ | [github.com/ANVEAI/openclaw-marketing-skills](https://github.com/ANVEAI/openclaw-marketing-skills) |
| **Productivity Skills** | Everyone | 50+ | [github.com/ANVEAI/openclaw-productivity-skills](https://github.com/ANVEAI/openclaw-productivity-skills) |
| **Business Skills** | Business owners, ops | 50+ | [github.com/ANVEAI/openclaw-business-skills](https://github.com/ANVEAI/openclaw-business-skills) |
| **Automation Skills** | Power users, DevOps | 50+ | [github.com/ANVEAI/openclaw-automation-skills](https://github.com/ANVEAI/openclaw-automation-skills) |
| **AI/ML Skills** | ML engineers, researchers | 50+ | [github.com/ANVEAI/openclaw-ai-ml-skills](https://github.com/ANVEAI/openclaw-ai-ml-skills) |
| **Startup Skills** | Founders, early teams | 50+ | [github.com/ANVEAI/openclaw-startup-skills](https://github.com/ANVEAI/openclaw-startup-skills) |

**Total: 350+ OpenClaw skills across 70+ categories**

---

## Contents

- [Installation](#installation)
- [Voice AI & Communication](#voice-ai--communication)
- [AI Agents & Automation](#ai-agents--automation)
- [Customer Support](#customer-support)
- [Marketing & Sales](#marketing--sales)
- [Content Creation & Writing](#content-creation--writing)
- [Productivity & Tasks](#productivity--tasks)
- [Analytics & Intelligence](#analytics--intelligence)
- [Search & Research](#search--research)
- [Coding Agents & IDEs](#coding-agents--ides)
- [Developer Tools & APIs](#developer-tools--apis)
- [Web & Browser Automation](#web--browser-automation)
- [Communication Tools](#communication-tools)
- [Social Media & Community](#social-media--community)
- [Data & Databases](#data--databases)
- [Finance & Crypto](#finance--crypto)
- [Home & IoT Automation](#home--iot-automation)
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

## AI Agents & Automation

Skills for building and orchestrating autonomous AI agents that can perform complex multi-step tasks.

| Skill | Description | Install |
|-------|-------------|---------|
| **[agent-autonomy-kit](https://clawhub.ai/ANVEAI/agent-autonomy-kit)** | Enable agents to continue working autonomously without waiting for prompts. | `clawhub install agent-autonomy-kit` |
| **[agent-council](https://clawhub.ai/ANVEAI/agent-council)** | Create and manage multi-agent systems with Discord integration. | `clawhub install agent-council` |
| **[agent-doppelganger](https://clawhub.ai/ANVEAI/agent-doppelganger)** | Constrained autonomous delegate for identity-proxied communication. | `clawhub install agent-doppelganger` |
| **[agent-commons](https://clawhub.ai/ANVEAI/agent-commons)** | Shared reasoning layer for AI agents to consult and extend reasoning chains. | `clawhub install agent-commons` |
| **[a2a-market](https://clawhub.ai/ANVEAI/a2a-market)** | AI Agent skill marketplace for buying, selling, and monetizing agent capabilities. | `clawhub install a2a-market` |
| **[cron](https://github.com/openclaw/skills/tree/main/skills/openclaw/cron)** | Schedule and manage automated tasks with cron-like precision. | `clawhub install cron` |
| **[workflow-automation](https://github.com/openclaw/skills/tree/main/skills/openclaw/workflow-automation)** | Build complex multi-step workflows with conditional logic. | `clawhub install workflow-automation` |

---

## Content Creation & Writing

Skills for generating, editing, and optimizing written content across platforms.

| Skill | Description | Install |
|-------|-------------|---------|
| **[scribe](https://clawhub.ai/ANVEAI/scribe)** | AI-powered writing assistant for blogs, copy, and SEO content. | `clawhub install scribe` |
| **[content-pipeline](https://clawhub.ai/ANVEAI/content-pipeline)** | Safe content workflow with human-in-the-loop approval. | `clawhub install content-pipeline` |
| **[medium-publisher](https://github.com/openclaw/skills/tree/main/skills/openclaw/medium-publisher)** | Publish and manage Medium articles directly. | `clawhub install medium-publisher` |
| **[devto-publisher](https://github.com/openclaw/skills/tree/main/skills/openclaw/devto-publisher)** | Cross-post content to Dev.to community. | `clawhub install devto-publisher` |
| **[newsletter-generator](https://github.com/openclaw/skills/tree/main/skills/openclaw/newsletter-generator)** | Create and send email newsletters with AI-generated content. | `clawhub install newsletter-generator` |
| **[ghost-writer](https://github.com/openclaw/skills/tree/main/skills/openclaw/ghost-writer)** | Generate long-form content from outlines and research. | `clawhub install ghost-writer` |
| **[ad-copy-generator](https://github.com/openclaw/skills/tree/main/skills/openclaw/ad-copy-generator)** | Create high-converting ad copy for various platforms. | `clawhub install ad-copy-generator` |
| **[social-caption-writer](https://github.com/openclaw/skills/tree/main/skills/openclaw/social-caption-writer)** | Generate engaging captions for social media posts. | `clawhub install social-caption-writer` |

---

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

## Search & Research

Skills for web search, data extraction, and research automation.

| Skill | Description | Install |
|-------|-------------|---------|
| **[web-search](https://github.com/openclaw/skills/tree/main/skills/openclaw/web-search)** | Search the web using Brave Search API with region-specific results. | `clawhub install web-search` |
| **[web-fetch](https://github.com/openclaw/skills/tree/main/skills/openclaw/web-fetch)** | Fetch and extract readable content from URLs. | `clawhub install web-fetch` |
| **[deep-research](https://clawhub.ai/ANVEAI/deep-research)** | Async deep research via Gemini Interactions API with RAG-grounding. | `clawhub install deep-research` |
| **[academic-deep-research](https://clawhub.ai/ANVEAI/academic-deep-research)** | Transparent, rigorous research with full methodology and APA citations. | `clawhub install academic-deep-research` |
| **[exa-search](https://github.com/openclaw/skills/tree/main/skills/openclaw/exa-search)** | Neural search for AI-powered semantic web search. | `clawhub install exa-search` |
| **[arxiv-explorer](https://github.com/openclaw/skills/tree/main/skills/openclaw/arxiv-explorer)** | Search and summarize academic papers from arXiv. | `clawhub install arxiv-explorer` |
| **[wikipedia-research](https://github.com/openclaw/skills/tree/main/skills/openclaw/wikipedia-research)** | Query Wikipedia for quick research and fact-checking. | `clawhub install wikipedia-research` |
| **[news-aggregator](https://github.com/openclaw/skills/tree/main/skills/openclaw/news-aggregator)** | Aggregate and summarize news from multiple sources. | `clawhub install news-aggregator` |

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

## Developer Tools & APIs

Skills for API management, testing, and developer productivity.

| Skill | Description | Install |
|-------|-------------|---------|
| **[api-gateway](https://github.com/openclaw/skills/tree/main/skills/openclaw/api-gateway)** | Manage and monitor API endpoints with rate limiting. | `clawhub install api-gateway` |
| **[postman-runner](https://github.com/openclaw/skills/tree/main/skills/openclaw/postman-runner)** | Run Postman collections directly from OpenClaw. | `clawhub install postman-runner` |
| **[swagger-generator](https://github.com/openclaw/skills/tree/main/skills/openclaw/swagger-generator)** | Generate OpenAPI/Swagger docs from code. | `clawhub install swagger-generator` |
| **[graphql-client](https://github.com/openclaw/skills/tree/main/skills/openclaw/graphql-client)** | Query GraphQL APIs with introspection support. | `clawhub install graphql-client` |
| **[database-client](https://github.com/openclaw/skills/tree/main/skills/openclaw/database-client)** | Connect and query SQL/NoSQL databases. | `clawhub install database-client` |
| **[redis-manager](https://github.com/openclaw/skills/tree/main/skills/openclaw/redis-manager)** | Manage Redis instances and caches. | `clawhub install redis-manager` |
| **[docker-controller](https://github.com/openclaw/skills/tree/main/skills/openclaw/docker-controller)** | Manage Docker containers and images. | `clawhub install docker-controller` |
| **[kubernetes-cli](https://github.com/openclaw/skills/tree/main/skills/openclaw/kubernetes-cli)** | Interact with Kubernetes clusters. | `clawhub install kubernetes-cli` |

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

## Social Media & Community

Skills for managing social media presence, engagement, and community building.

| Skill | Description | Install |
|-------|-------------|---------|
| **[twitter-growth](https://clawhub.ai/ANVEAI/twitter-growth)** | X/Twitter automation for growth, engagement, and content scheduling. | `clawhub install twitter-growth` |
| **[linkedin-automation](https://github.com/openclaw/skills/tree/main/skills/openclaw/linkedin-automation)** | Automate LinkedIn outreach and posting. | `clawhub install linkedin-automation` |
| **[reddit-engagement](https://clawhub.ai/ANVEAI/reddit-engagement)** | Community engagement and content sharing on Reddit. | `clawhub install reddit-engagement` |
| **[youtube-manager](https://github.com/openclaw/skills/tree/main/skills/openclaw/youtube-manager)** | Manage YouTube uploads, comments, and analytics. | `clawhub install youtube-manager` |
| **[instagram-poster](https://github.com/openclaw/skills/tree/main/skills/openclaw/instagram-poster)** | Schedule and post to Instagram with AI-generated captions. | `clawhub install instagram-poster` |
| **[tiktok-automation](https://github.com/openclaw/skills/tree/main/skills/openclaw/tiktok-automation)** | Automate TikTok posting and engagement. | `clawhub install tiktok-automation` |
| **[community-manager](https://github.com/openclaw/skills/tree/main/skills/openclaw/community-manager)** | Manage online communities across platforms. | `clawhub install community-manager` |
| **[influencer-outreach](https://github.com/openclaw/skills/tree/main/skills/openclaw/influencer-outreach)** | Find and connect with influencers in your niche. | `clawhub install influencer-outreach` |

---

## Data & Databases

Skills for data management, processing, and database operations.

| Skill | Description | Install |
|-------|-------------|---------|
| **[data-cleaner](https://github.com/openclaw/skills/tree/main/skills/openclaw/data-cleaner)** | Clean and normalize messy datasets automatically. | `clawhub install data-cleaner` |
| **[csv-processor](https://github.com/openclaw/skills/tree/main/skills/openclaw/csv-processor)** | Process, transform, and analyze CSV files. | `clawhub install csv-processor` |
| **[json-transformer](https://github.com/openclaw/skills/tree/main/skills/openclaw/json-transformer)** | Transform and manipulate JSON data structures. | `clawhub install json-transformer` |
| **[spreadsheet-automation](https://github.com/openclaw/skills/tree/main/skills/openclaw/spreadsheet-automation)** | Automate Google Sheets and Excel operations. | `clawhub install spreadsheet-automation` |
| **[data-exporter](https://github.com/openclaw/skills/tree/main/skills/openclaw/data-exporter)** | Export data to various formats (CSV, JSON, XML, Parquet). | `clawhub install data-exporter` |
| **[etl-pipeline](https://github.com/openclaw/skills/tree/main/skills/openclaw/etl-pipeline)** | Build extract, transform, load workflows. | `clawhub install etl-pipeline` |
| **[data-validator](https://github.com/openclaw/skills/tree/main/skills/openclaw/data-validator)** | Validate data against schemas and rules. | `clawhub install data-validator` |
| **[backup-sync](https://github.com/openclaw/skills/tree/main/skills/openclaw/backup-sync)** | Synchronize and backup data across services. | `clawhub install backup-sync` |

---

## Finance & Crypto

Skills for financial management, cryptocurrency, and trading automation.

| Skill | Description | Install |
|-------|-------------|---------|
| **[crypto-tracker](https://github.com/openclaw/skills/tree/main/skills/openclaw/crypto-tracker)** | Track cryptocurrency prices and portfolio value. | `clawhub install crypto-tracker` |
| **[trading-bot](https://github.com/openclaw/skills/tree/main/skills/openclaw/trading-bot)** | Automated trading strategies for exchanges. | `clawhub install trading-bot` |
| **[expense-tracker](https://github.com/openclaw/skills/tree/main/skills/openclaw/expense-tracker)** | Track and categorize personal or business expenses. | `clawhub install expense-tracker` |
| **[invoice-generator](https://github.com/openclaw/skills/tree/main/skills/openclaw/invoice-generator)** | Create and send professional invoices. | `clawhub install invoice-generator` |
| **[budget-planner](https://github.com/openclaw/skills/tree/main/skills/openclaw/budget-planner)** | AI-powered budget planning and forecasting. | `clawhub install budget-planner` |
| **[tax-calculator](https://github.com/openclaw/skills/tree/main/skills/openclaw/tax-calculator)** | Calculate taxes and generate reports. | `clawhub install tax-calculator` |
| **[payment-processor](https://github.com/openclaw/skills/tree/main/skills/openclaw/payment-processor)** | Process payments via Stripe, PayPal, and more. | `clawhub install payment-processor` |
| **[defi-yield](https://github.com/openclaw/skills/tree/main/skills/openclaw/defi-yield)** | Track DeFi yields and liquidity pool performance. | `clawhub install defi-yield` |

---

## Home & IoT Automation

Skills for smart home control, IoT device management, and home automation.

| Skill | Description | Install |
|-------|-------------|---------|
| **[home-assistant](https://github.com/openclaw/skills/tree/main/skills/openclaw/home-assistant)** | Control Home Assistant devices and automations. | `clawhub install home-assistant` |
| **[smart-lights](https://github.com/openclaw/skills/tree/main/skills/openclaw/smart-lights)** | Control Philips Hue, LIFX, and other smart lights. | `clawhub install smart-lights` |
| **[thermostat-control](https://github.com/openclaw/skills/tree/main/skills/openclaw/thermostat-control)** | Manage Nest, Ecobee, and smart thermostats. | `clawhub install thermostat-control` |
| **[security-cameras](https://github.com/openclaw/skills/tree/main/skills/openclaw/security-cameras)** | View and manage security camera feeds. | `clawhub install security-cameras` |
| **[smart-lock](https://github.com/openclaw/skills/tree/main/skills/openclaw/smart-lock)** | Control smart locks and access systems. | `clawhub install smart-lock` |
| **[media-center](https://github.com/openclaw/skills/tree/main/skills/openclaw/media-center)** | Control Plex, Kodi, and media center applications. | `clawhub install media-center` |
| **[weather-station](https://github.com/openclaw/skills/tree/main/skills/openclaw/weather-station)** | Connect to personal weather stations. | `clawhub install weather-station` |
| **[irrigation-control](https://github.com/openclaw/skills/tree/main/skills/openclaw/irrigation-control)** | Automate garden and lawn irrigation systems. | `clawhub install irrigation-control` |

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

See [contributing.md](contributing.md) for detailed guidelines.

---

## Related Resources

- [OpenClaw Official Website](https://openclaw.ai)
- [ClawHub Registry](https://clawhub.ai)
- [AnveVoice Voice AI](https://anvevoice.com)
- [OpenClaw Documentation](https://docs.openclaw.ai)
- [Community Discord](https://discord.gg/openclaw)

---

<p align="center">
  <b>Made with ❤️ by the OpenClaw community</b><br>
  <sub>Special thanks to <a href="https://anvevoice.com">AnveVoice</a> for sponsoring this awesome list</sub>
</p>
