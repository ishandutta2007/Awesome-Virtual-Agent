# Awesome-Virtual-Agent

# Top Virtual Agent Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on Conversational AI, Customer Service Automation & Agentic Assistants*  
**Last updated: October 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Virtual Agents**. These tools enable organizations to deploy AI-powered conversational agents that handle customer support, employee service, lead qualification, and task automation across chat, voice, email, and social channels.

**Examples** include ServiceNow Virtual Agent, Ada, Kore.ai, Cognigy, Yellow.ai, Amelia, IBM watsonx Assistant, Drift, LivePerson, and Microsoft Copilot Studio (the category leaders).

**Open-source emphasis**: This section is heavily expanded with active projects for self-hosted conversational AI platforms, chatbot builders, and agent frameworks — ideal for developers, enterprises, and teams building sovereign virtual agent infrastructure without per-conversation pricing lock-in.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-products)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

- **[ServiceNow Virtual Agent](https://www.servicenow.com/)**  
  AI-powered virtual agent for ITSM and enterprise service management with NLU, pre-built conversation topics, multi-channel support (Slack, Teams, web), and agentic AI capabilities for multi-step task execution; a limited "Virtual Agent Lite" keyword-based version exists for ITSM Standard customers .

- **[Ada](https://www.ada.cx/)**  
  AI Agent platform for customer support automation with knowledge base learning, API-driven Actions, multi-step Processes, handoff integrations to Zendesk/Salesforce, and channels spanning chat, voice, email, and social messaging .

- **[Kore.ai](https://kore.ai/)**  
  Enterprise conversational AI platform with the XO Platform for building virtual assistants, AgentAssist for agent coaching and real-time guidance, and integrations with Salesforce, Zendesk, Genesys, and major messaging channels .

- **[Cognigy](https://www.cognigy.com/)**  
  AI-first CX platform with Agentic AI + deterministic NLU (Hybrid AI), AI Agent Studio visual flow editor, Knowledge AI with RAG, native voice gateway, multimodal xApps, and contact center integrations .

- **[Yellow.ai](https://yellow.ai/)**  
  Agentic AI platform for customer and employee support with AI Agent Builder, Agentic RAG, multi-LLM architecture (GPT, Claude, DeepSeek), voice AI with emotion detection, and 100+ integrations including Salesforce, SAP, and ServiceNow .

- **[Amelia](https://amelia.ai/)**  
  Agentic AI platform (now part of SoundHound) with process-specific instructions for task accuracy, response streaming for reduced latency, custom on-premise LLM support, and visual parsing of documents for knowledge ingestion .

- **[IBM watsonx Assistant](https://www.ibm.com/products/watsonx-assistant)**  
  Enterprise virtual agent available as SaaS or on-premises, with generative AI answers, skills-based actions, conversational search, telephony integrations (Genesys, Twilio, NICE), and web chat customization .

- **[Drift](https://www.drift.com/)**  
  Conversational marketing platform for B2B website chat, lead qualification, and meeting booking; now closed to new customers as Salesloft has transitioned from Drift to 1mind, with existing users served under Salesloft Chat Agents .

- **[LivePerson](https://www.liveperson.com/)**  
  Conversational AI platform for messaging and voice, with LivePerson Sync for CRM/CCaaS integration (Salesforce, Microsoft, ServiceNow), event-driven orchestration, and AI enrichment for agent workspaces .

- **[Microsoft Copilot Studio](https://www.microsoft.com/en-us/microsoft-copilot/microsoft-copilot-studio)**  
  SaaS agent platform with low-code authoring canvas, generative answers from internal/external sources, generative actions for dynamic plugin selection, voice/IVR support, and integration with Microsoft 365 Copilot and Power Platform governance .

## Open-Source GitHub Projects

- **[Rasa](https://github.com/RasaHQ/rasa)**  
  Leading open-core conversational AI framework (Python) for building context-aware assistants with flows for business logic, automatic conversation repair, LLM integration, and built-in security controls; free developer license available, paid license for larger production use .

- **[Botpress](https://github.com/botpress/botpress)**  
  Open-source chatbot platform (AGPLv3 for source, proprietary for binaries) with visual dialog management, native NLU engine (intent classification, entity extraction, slot tagging), multi-channel support (Slack, Teams, Telegram, web), and self-hosted deployment on Linux/Mac/Windows .

- **[Typebot](https://github.com/baptisteArno/typebot.io)**  
  Open-source chatbot and conversational form builder with visual drag-and-drop editor, 30+ block types, native OpenAI/LLM integration, conditional logic, and embed anywhere (websites, WhatsApp); 10,000+ GitHub stars, self-hostable with no per-chat limits under Fair Source License .

- **[Tock](https://github.com/theopenconversationkit/tock)**  
  Open-source conversational AI toolkit (Kotlin) from the Open Conversation Kit project; provides a complete platform for building chatbots with NLU, stories, and multi-channel connectors; ~500 GitHub stars with active development .

- **[Chatwoot](https://github.com/chatwoot/chatwoot)**  
  Open-source customer support platform (MIT) with multi-channel inbox (web, email, social), conversation management, and extensible APIs; can serve as the human handoff layer for AI virtual agents; self-hostable via Docker/Kubernetes .

- **[Lobe Chat](https://github.com/lobehub/lobe-chat)**  
  Open-source chatbot framework and interface with modern UI, plugin support, multi-modal interactions, and multiple AI model integrations; health score of 76/100 with 10 active maintainers and contributors from 759 organizations .

- **[Libre Chat](https://github.com/vemonet/libre-chat)**  
  Open-source and free chatbot powered by LangChain and llama.cpp; provides a web UI and REST API for chatting with local LLMs, with optional vectorstore QA retrieval; MIT licensed and pip-installable .

### Additional Strong Open-Source Options

- **Pickle-Bot** — Lightweight multi-agent AI assistant with web tools, skills as markdown files, cron jobs, memory system, and multi-platform support (CLI, Telegram, Discord) .
- **Open Conversation Kit (tock-docker)** — Docker Compose deployment for the Tock toolkit, simplifying self-hosted conversational AI setup .
- **tock-react-kit / tock-vue-kit** — React and Vue components for embedding Tock chatbots into web interfaces .

**Frameworks for building custom systems**: Combine **Rasa** for NLU and dialogue management, **Botpress** or **Typebot** for visual flow building, **Chatwoot** for human handoff and support ticketing, and **Libre Chat** or **Lobe Chat** for LLM-powered conversational interfaces in a fully self-hosted virtual agent stack.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- Virtual agents handling customer data must comply with applicable privacy regulations (GDPR, CCPA, etc.) and industry-specific requirements.
- Self-hosted open-source solutions require proper security hardening, NLU training, and ongoing conversation quality monitoring.
- Verify license terms for commercial use; Rasa uses an open-core model with production licensing requirements, Botpress has AGPLv3/proprietary dual licensing, and Typebot uses Fair Source License with premium feature restrictions .

---

**Made for customer experience teams, conversational AI developers, contact center managers, and digital service builders.**  
Let's make virtual agents more open, controllable, and helpful.
