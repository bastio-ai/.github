```
██████   █████  ███████ ████████ ██  ██████
██   ██ ██   ██ ██         ██    ██ ██    ██
██████  ███████ ███████    ██    ██ ██    ██
██   ██ ██   ██      ██   ██    ██ ██    ██
██████  ██   ██ ███████    ██    ██  ██████
```

### Simple LLM Security, Compliance, and Cost Control

[![Website](https://img.shields.io/badge/bastio.com-blue?style=flat-square)](https://bastio.com) [![Docs](https://img.shields.io/badge/Docs-green?style=flat-square)](https://docs.bastio.com) [![X](https://img.shields.io/badge/@bastio__ai-000?style=flat-square&logo=x&logoColor=white)](https://x.com/bastio_ai) [![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/company/bastio-ai)

---

## The AI Gateway for Secure, Affordable LLM Operations

Bastio sits between your app and LLM providers — security, compliance, and cost control without code changes. Drop in our proxy and get protection from day one.

> "Make secure, affordable AI the default."

**One line change. Sub-10 ms latency. Full protection.**

---

## Why Bastio?

<table>
<tr>
<td width="50%" valign="top">

### :shield: Security

- Prompt injection blocking
- Jailbreak detection
- PII masking & redaction
- Tool call validation

</td>
<td width="50%" valign="top">

### :moneybag: Cost Control

- Response caching (30-70% savings)
- Multi-provider routing
- Usage analytics & dashboards
- Budget guardrails & alerts

</td>
</tr>
<tr>
<td width="50%" valign="top">

### :white_check_mark: Compliance

- SOC 2 Type II
- HIPAA ready
- GDPR compliant
- Full audit logging

</td>
<td width="50%" valign="top">

### :zap: Infrastructure

- Sub-10 ms proxy latency
- Automatic failover
- Real-time observability
- OpenAI-compatible API

</td>
</tr>
</table>

---

## Quick Start

**Before** — calling OpenAI directly:

```python
from openai import OpenAI

client = OpenAI(
    api_key="sk-...",
)
```

**After** — routed through Bastio:

```python
from openai import OpenAI

client = OpenAI(
    base_url="https://proxy.bastio.com/v1",  # <- just change this
    api_key="bastio-...",                     # <- just change this
)
```

That's it. Every request now gets security, caching, compliance, and failover.

[**Get Your API Key**](https://app.bastio.com/signup) | [**Read the Docs**](https://docs.bastio.com)

---

## Supported Providers

<p align="center">
<b>OpenAI</b> · <b>Anthropic</b> · <b>Google Gemini</b> · <b>AWS Bedrock</b> · <b>Azure OpenAI</b> · <b>and more</b>
</p>

One endpoint. If a provider goes down, Bastio fails over automatically.

---

## Feature Overview

| Feature | Description | Impact |
| :--- | :--- | :--- |
| **Prompt Injection Blocking** | Detect and block malicious prompt manipulation | Prevent data leaks and misuse |
| **PII Masking** | Redact sensitive data before it hits the LLM | Compliance without manual review |
| **Response Caching** | Semantic caching for repeated queries | 30-70% cost reduction |
| **Multi-Provider Routing** | Route by cost, latency, or capability | Optimize spend & reliability |
| **Budget Guardrails** | Spend limits per team, project, or key | No surprise bills |
| **Audit Logging** | Immutable logs of every request and decision | SOC 2 / HIPAA / GDPR ready |
| **Automatic Failover** | Reroute when a provider is down | Zero-downtime AI ops |
| **Real-Time Observability** | Dashboards for latency, tokens, and costs | Full LLM visibility |
| **OpenAI-Compatible API** | Drop-in proxy — any OpenAI SDK client | Integrate in minutes |

---

## Building in the Open

AI security tooling should be transparent — not a black box. We're working toward open-sourcing key components:

- :package: **Open-source SDKs** — Python, TypeScript, and Go clients
- :mag: **Transparent detection models** — inspect and audit the rules guarding your prompts
- :busts_in_silhouette: **Community rule sets** — share and contribute security policies

**Watch this org** to get notified when we ship new repos.

---

## 🌟 Open Source

### 🔧 [bast](https://github.com/bastio-ai/bast) — AI-Powered Terminal Assistant
Open-source CLI that brings security to AI-powered terminal operations. Describe tasks in plain English, get shell commands instantly. Features automatic PII redaction, jailbreak protection, and integrates with Bastio AI Security Gateway.

![Go](https://img.shields.io/badge/-Go-00ADD8?style=flat&logo=go&logoColor=white)
![MIT License](https://img.shields.io/badge/license-MIT-blue.svg)
[![GitHub](https://img.shields.io/github/stars/bastio-ai/bast?style=social)](https://github.com/bastio-ai/bast)

---

## Get Started

<p align="center">
:globe_with_meridians: <a href="https://bastio.com"><strong>Website</strong></a> &nbsp;·&nbsp;
:book: <a href="https://docs.bastio.com"><strong>Documentation</strong></a> &nbsp;·&nbsp;
:rocket: <a href="https://app.bastio.com/signup"><strong>Sign Up Free</strong></a> &nbsp;·&nbsp;
:email: <a href="mailto:contact@bastio.com"><strong>Contact Us</strong></a>
</p>

---

<p align="center">
<em>"Make secure, affordable AI the default."</em><br>
Founded by <a href="https://www.linkedin.com/in/dsjacobsen/">Daniel Jacobsen</a><br>
<a href="https://x.com/bastio_ai">X</a> · <a href="https://www.linkedin.com/company/bastio-ai">LinkedIn</a> · <a href="https://bastio.com">bastio.com</a>
</p>
