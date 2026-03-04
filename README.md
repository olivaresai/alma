<div align="center">

<img src="alma-banner.png" alt="Alma by olivares.ai" width="600" />

<br>
<br>

### Persistent Memory for AI

Every AI conversation starts from scratch.
Weeks of context, preferences, decisions — gone the moment you close the tab.

**Alma changes that.**

<br>

[![Website](https://img.shields.io/badge/olivares.ai-FE9A37?style=for-the-badge&logoColor=1A1A19)](https://olivares.ai)
[![Launch App](https://img.shields.io/badge/Launch_App-1A1A19?style=for-the-badge)](https://alma.olivares.ai)
[![Documentation](https://img.shields.io/badge/Docs-2E2E2C?style=for-the-badge)](https://olivares.ai/docs)

</div>

<br>

Alma is a persistent memory layer that captures facts, preferences, decisions, and behavioral patterns from your AI conversations — and makes them available across every session, every tool, every platform.

Day 1 and day 100 no longer feel the same. Your AI stops forgetting. It starts *understanding*.

<br>

---

<br>

## Why Alma

<table>
<tr>
<td width="50%" valign="top">

**Not just a vector database** — A cognitive system

Vector databases store and retrieve embeddings. Alma understands context at multiple levels — facts, experiences, and behavioral patterns. It doesn't just find similar text; it builds a structured understanding of who you are.

**Not just RAG** — Contextual intelligence

RAG fetches relevant chunks. Alma goes further: it maintains episodic memory, learns procedures over time, and assembles context that includes not just what's relevant, but what's important to *you* specifically.

</td>
<td width="50%" valign="top">

**Not a black box** — Full transparency

Every memory is visible, editable, and deletable. You see exactly what the AI knows about you. Review episode summaries, modify procedures, export your entire cognitive profile. No hidden data, no opaque processes.

**Not locked in** — Your data is yours

Export everything in portable formats at any time. `.alma` bundles, JSON, XLSX, PDF, DOCX, Markdown. Full GDPR-compliant data export. Delete your account and everything goes with it — no retention, no dark patterns.

</td>
</tr>
</table>

<br>

---

<br>

## Three-Layer Memory

Alma organizes knowledge into three complementary layers — mirroring how humans process and retain information.

<table>
<tr>
<td width="33%" valign="top">

### Memories
Discrete facts — preferences, decisions, technical context, personal details. Each memory has a category, importance ranking, and confidence score. Semantically indexed for keyword, embedding, and hybrid search.

```
User prefers TypeScript over JavaScript
Project uses PostgreSQL 16
Prefers concise explanations
```

</td>
<td width="33%" valign="top">

### Episodes
Compressed summaries of past conversations. Episodes capture the arc of a discussion — what was decided, what changed, what matters. No need to replay full transcripts.

```
Debugged auth middleware issue
Designed new database schema
Reviewed API architecture decisions
```

</td>
<td width="33%" valign="top">

### Procedures
Learned behavioral patterns and workflows. Procedures are trigger-action pairs that the AI picks up from observing how you work — from communication style to multi-step processes.

```
When reviewing code → check errors first
Use bullet points for technical topics
Always suggest tests for new functions
```

</td>
</tr>
</table>

<br>

### Soul Engine

All three layers feed into the **Soul Engine** — a structured personality and context framework with 13 configurable blocks organized into three sections:

- **Identity** — who the AI is, its worldview, its principles
- **Style** — communication patterns, anti-patterns, formatting rules
- **Context** — active project awareness, recent learnings, current goals

The Soul Engine assembles the optimal context for every interaction — selecting the most relevant memories, recent episodes, and applicable procedures, then rendering them into a structured system prompt. Four presets (Balanced, Creative, Technical, Mentor) or fully custom configuration. Version history with snapshots and restore.

<br>

---

<br>

## Features

<table>
<tr>
<td width="50%" valign="top">

**Persistent Memory**
Facts, preferences, decisions, and patterns — remembered across every conversation. No more repeating yourself. Day 100 is fundamentally different from day 1.

**Context Assembly**
Hybrid search (keyword + semantic) surfaces the right context for each interaction. Memories, episodes, and procedures assembled in milliseconds within a configurable token budget.

**Background Processing**
Learns while you chat. Memories are extracted, episodes are summarized, and procedures are refined — seamlessly in the background with zero latency impact.

**Smart Deduplication**
Semantic similarity detection prevents redundant memories. When a fact is restated, the existing memory is reinforced instead of duplicated.

**Environments**
Separate memory spaces for different contexts — work, personal, projects. Each environment has its own soul, its own memories, its own knowledge.

</td>
<td width="50%" valign="top">

**Multi-Model**
Powered by Anthropic's Claude (Haiku, Sonnet, Opus). The architecture supports multiple providers — switch models without losing memory or context continuity.

**Image Generation** `Coming Soon`
Multi-provider image generation from chat with persistent memory of your visual preferences. Claude can already generate SVG illustrations inline.

**Voice**
Speech-to-text via Deepgram Nova-2. Text-to-speech via ElevenLabs. Talk to your AI naturally, and it remembers what you said.

**Export Everything**
Conversations to PDF, DOCX, HTML, Markdown. Memories to JSON and XLSX. Full data dumps in the portable `.alma` format with import and deduplication.

**Bring Your Own Keys**
Use your own API keys for Anthropic, OpenAI, Google, DeepSeek, xAI, or Ollama. BYOK keys are encrypted at rest with AES-256-GCM. Available on Advanced plans and above.

</td>
</tr>
</table>

<br>

---

<br>

## Get Started

The fastest way to use Alma is through the **web app** — sign up and start chatting in seconds. No downloads, no configuration.

| Path | Status | Best For |
|------|--------|----------|
| [**Web App**](https://alma.olivares.ai) | Available | Everyone — sign up and chat instantly |
| [**REST API**](https://olivares.ai/developers) | Available | Backend integrations (Advanced plan) |
| [**JavaScript SDK**](https://www.npmjs.com/package/@olivaresai/alma-sdk) | Available | Node.js / TypeScript (Advanced plan) |
| [**MCP Server**](https://olivares.ai/docs/mcp) | Beta | Claude Desktop, Cursor, Windsurf |
| [**VSCode Extension**](https://olivares.ai/docs/vscode) | Beta | Development workflow |
| **Mobile Apps** | Coming Soon | iOS and Android |

<br>

---

<br>

## Models

**3 intelligence tiers** powered by Anthropic's Claude models.

| Tier | Model | Context | Free | Paid |
|------|-------|---------|:----:|:----:|
| Normal | Claude Haiku 4.5 | 200K | Yes | Yes |
| Advanced | Claude Sonnet 4.6 | 200K | | Yes |
| Complex | Claude Opus 4.6 | 200K | | Yes |

The platform architecture supports additional providers (OpenAI, Google, DeepSeek, xAI). New models are added based on demand and quality standards.

<br>

---

<br>

## Plans

Start free. Upgrade when you need more.

| | Free | Pro | Advanced | Ultimate | Ultimate Max |
|---|:---:|:---:|:---:|:---:|:---:|
| **Price** | $0 | $19/mo | $49/mo | $149/mo | $249/mo |
| **Memories** | 500 | 10,000 | 50,000 | Unlimited | Unlimited |
| **Episodes** | 50 | Unlimited | Unlimited | Unlimited | Unlimited |
| **Procedures** | 10 | 100 | 500 | Unlimited | Unlimited |
| **Environments** | 1 | 2 | 3 | Unlimited | Unlimited |
| **Chat Models** | Haiku | All 3 | All 3 | All 3 | All 3 |
| **Voice / Day** | 5 min | 60 min | 300 min | No cap* | No cap* |
| **Web Search / Day** | 5 | 100 | 500 | No cap* | No cap* |
| **BYOK** | | | Yes | Yes | Yes |
| **API & MCP** | | | Yes | Yes | Yes |
| **Buy Credits** | | Yes | Yes | Yes | Yes |

\* All AI features (chat, voice, web search) consume from a weekly budget that resets automatically. "No cap" means no daily limit — usage is still governed by the weekly budget. Pro plans and above can purchase additional credit packs that never expire.

[**Compare plans in detail**](https://olivares.ai/pricing)

<br>

---

<br>

## REST API

160+ endpoints covering every aspect of the memory system. All responses are JSON. Streaming chat via SSE. Requires an **Advanced** plan or above.

**Base URL**
```
https://alma.olivares.ai/api/v1/
```

**Authentication** — API key or JWT bearer token:
```bash
# API Key (recommended for scripts and integrations)
curl -H "X-API-Key: alma_sk_..." https://alma.olivares.ai/api/v1/memories

# JWT Bearer (for web applications)
curl -H "Authorization: Bearer eyJ..." https://alma.olivares.ai/api/v1/memories
```

### Endpoints

<details>
<summary><strong>Context Assembly</strong></summary>

```http
POST   /context/assemble         Build the full AI context
POST   /context/continue         Continue an existing conversation context
POST   /context/focus            Update the active context focus
POST   /context/preview          Preview the system prompt the LLM would see
```
</details>

<details>
<summary><strong>Memories</strong></summary>

```http
GET    /memories                 List memories with filters
GET    /memories/search          Search via keyword, semantic, or hybrid
GET    /memories/:id             Get a specific memory
POST   /memories                 Create a memory
PUT    /memories/:id             Update a memory
DELETE /memories/:id             Delete a memory
POST   /memories/extract         AI-powered memory extraction from text
```
</details>

<details>
<summary><strong>Chat</strong></summary>

```http
GET    /chat/models              List available models
GET    /chat/budget              Get current budget status
GET    /chat/usage/history       Usage history
POST   /chat/estimate            Estimate message cost
POST   /chat/conversations       Create a conversation
GET    /chat/conversations       List conversations
GET    /chat/conversations/:id   Get conversation details
PUT    /chat/conversations/:id   Update conversation
DELETE /chat/conversations/:id   Delete conversation
POST   /chat/conversations/:id/messages  Send message (SSE streaming)
```
</details>

<details>
<summary><strong>Episodes</strong></summary>

```http
GET    /episodes                 List episodes
GET    /episodes/search          Search episodes by topic
GET    /episodes/:id             Get a specific episode
POST   /episodes                 Create an episode
PUT    /episodes/:id             Update an episode
DELETE /episodes/:id             Delete an episode
```
</details>

<details>
<summary><strong>Procedures</strong></summary>

```http
GET    /procedures               List procedures
GET    /procedures/:id           Get a specific procedure
POST   /procedures               Create a procedure
POST   /procedures/:id/success   Mark successful execution
PUT    /procedures/:id           Update a procedure
DELETE /procedures/:id           Delete a procedure
```
</details>

<details>
<summary><strong>Soul & Blocks</strong></summary>

```http
GET    /blocks                   List memory blocks
GET    /blocks/:label            Get a specific block
POST   /blocks                   Create a custom block
POST   /blocks/preset            Apply a soul preset
POST   /blocks/init              Reset blocks to defaults
PUT    /blocks/:label            Update a block
DELETE /blocks/:label            Delete a custom block

GET    /soul/versions/list       List soul version history
POST   /soul/versions/snapshot   Create a manual snapshot
GET    /soul/versions/:id        Get a specific version
POST   /soul/versions/:id/restore  Restore to a previous version
```
</details>

<details>
<summary><strong>Voice</strong></summary>

```http
GET    /voice/capabilities       Check available voice features
POST   /voice/transcribe         Voice-to-text (Deepgram Nova-2)
POST   /voice/synthesize         Text-to-speech (ElevenLabs)
```
</details>

<details>
<summary><strong>Environments</strong></summary>

```http
GET    /environments             List environments
POST   /environments             Create an environment
GET    /environments/:id         Get environment details
PUT    /environments/:id         Update an environment
POST   /environments/:id/default Set as default
DELETE /environments/:id         Delete an environment
```
</details>

<details>
<summary><strong>BYOK</strong></summary>

```http
GET    /byok                     List configured providers
PUT    /byok/:provider           Save a provider key (AES-256-GCM encrypted)
GET    /byok/:provider/test      Test a provider key
DELETE /byok/:provider           Remove a provider key
```

Providers: `anthropic`, `openai`, `google`, `deepseek`, `xai`, `ollama`
</details>

<details>
<summary><strong>Export</strong></summary>

```http
GET    /export/conversation/:id  Export conversation (md, html, pdf, docx)
GET    /export/memories          Export memories (json, md, xlsx)
GET    /export/soul              Export soul configuration (json, md)
GET    /export/all               Full GDPR data export

GET    /admin/export/alma        Full .alma portable export
POST   /admin/import/alma        Import from .alma file with dedup
```
</details>

<details>
<summary><strong>Auth, Billing, Teams & more</strong></summary>

```http
# Authentication (16 endpoints)
POST   /auth/register, /auth/login, /auth/logout, /auth/logout-all
GET    /auth/me, /auth/sessions, /auth/limits
PUT    /auth/password
DELETE /auth/account

# Two-Factor Authentication
POST   /auth/2fa/enable, /auth/2fa/verify, /auth/2fa/disable

# OAuth
GET    /auth/oauth/google, /auth/oauth/github
GET    /auth/oauth/providers, /auth/oauth/accounts

# API Keys
GET    /auth/api-keys
POST   /auth/api-keys
DELETE /auth/api-keys/:id

# Billing (12 endpoints)
POST   /billing/checkout, /billing/portal, /billing/upgrade, /billing/cancel
GET    /billing/status, /billing/invoices
POST   /billing/credits/purchase
GET    /billing/credits/balance, /billing/credits/history, /billing/credits/packages

# Teams (15+ endpoints)
Full team management: create, invite, roles, billing, environments
```
</details>

<br>

### Quick Example

```bash
# 1. Assemble context for your AI
curl -X POST https://alma.olivares.ai/api/v1/context/assemble \
  -H "X-API-Key: alma_sk_..." \
  -H "Content-Type: application/json" \
  -d '{"maxTokens": 4000}'

# 2. Save a memory
curl -X POST https://alma.olivares.ai/api/v1/memories \
  -H "X-API-Key: alma_sk_..." \
  -H "Content-Type: application/json" \
  -d '{
    "content": "User prefers dark mode and minimal UI",
    "category": "preference",
    "importance": 8
  }'

# 3. Search memories
curl "https://alma.olivares.ai/api/v1/memories/search?q=preferences&mode=hybrid" \
  -H "X-API-Key: alma_sk_..."
```

<br>

---

<br>

## MCP Server `Beta`

Connect any MCP-compatible AI to Alma's memory layer.

**Package:** `@olivaresai/alma-mcp` on npm

```json
{
  "mcpServers": {
    "alma": {
      "command": "npx",
      "args": ["@olivaresai/alma-mcp"],
      "env": { "ALMA_API_KEY": "alma_sk_..." }
    }
  }
}
```

**20 tools** including `get_context`, `search_memories`, `create_memory`, `chat`, `update_block`, `search_episodes`, `create_procedure`, `preview_context`, `export_data`, and more.

**7 resources:** soul, memories, environments, conversations, budget, memories by category, blocks.

Compatible with Claude Desktop, Cursor, Windsurf, and any MCP-compatible client.

<br>

---

<br>

## VSCode Extension `Beta`

**Extension:** `alma-vscode` on the VSCode Marketplace

- **Sidebar chat** with streaming responses and full memory context
- **Memory browser** — search, filter, and manage memories without leaving the IDE
- **Soul block editor** — configure AI personality with presets
- **Context focus** — Alma knows what file and project you're working on
- **Right-click to save** — select any text and save it as a memory
- **Budget display** — remaining AI budget in the status bar

<br>

---

<br>

## JavaScript SDK

Full TypeScript client for the Alma API. ESM, Node.js 18+.

```bash
npm install @olivaresai/alma-sdk
```

```typescript
import { AlmaClient } from '@olivaresai/alma-sdk';

const alma = new AlmaClient({ apiKey: 'alma_sk_...' });

// Assemble context for your AI
const context = await alma.context.assemble({ maxTokens: 4000 });

// Save a memory
await alma.memories.create({
  content: 'User prefers TypeScript',
  category: 'preference',
  importance: 8
});

// Search memories
const results = await alma.memories.search({ q: 'preferences', mode: 'hybrid' });

// Stream a chat message
await alma.chat.sendMessage(conversationId, {
  content: 'Hello',
  onToken: (token) => process.stdout.write(token)
});
```

<br>

---

<br>

## Security & Privacy

Your cognitive data is the most personal data there is. We treat it that way.

- **Encryption** — All data encrypted at rest and in transit. BYOK keys use AES-256-GCM with per-record key derivation
- **Authentication** — Passwords hashed with scrypt. API keys hashed with a one-way function. JWT sessions with httpOnly cookies
- **2FA** — TOTP-based two-factor authentication with recovery codes
- **OAuth** — Sign in with Google or GitHub
- **Isolation** — Memories are isolated per account and per environment
- **No tracking** — No tracking cookies, no third-party analytics, no data selling
- **GDPR** — Full data export and deletion at any time. No retention after deletion
- **Rate limiting** — Per-minute and per-day limits to prevent abuse
- **Transparency** — Every memory, episode, and procedure is visible and inspectable

If you downgrade or cancel, your data is never deleted automatically. You maintain read access to everything you've built.

<br>

---

<br>

## Report Issues

Found a bug? Have a feature request? We welcome your feedback.

- [**Open an issue**](https://github.com/olivaresai/alma/issues/new) — Bug reports and feature requests
- [**Discussions**](https://github.com/olivaresai/alma/discussions) — Questions, ideas, and community

When reporting an issue, please include:
- What you expected vs. what happened
- Steps to reproduce (if applicable)
- Plan tier and client (web app, VSCode, MCP, API)

<br>

---

<br>

## Links

| | |
|---|---|
| **Website** | [olivares.ai](https://olivares.ai) |
| **App** | [alma.olivares.ai](https://alma.olivares.ai) |
| **Documentation** | [olivares.ai/docs](https://olivares.ai/docs) |
| **API Reference** | [olivares.ai/developers](https://olivares.ai/developers) |
| **Philosophy** | [olivares.ai/philosophy](https://olivares.ai/philosophy) |
| **SDK** | [@olivaresai/alma-sdk](https://www.npmjs.com/package/@olivaresai/alma-sdk) |
| **MCP** | [@olivaresai/alma-mcp](https://www.npmjs.com/package/@olivaresai/alma-mcp) |
| **Privacy** | [olivares.ai/privacy](https://olivares.ai/privacy) |
| **Terms** | [olivares.ai/terms](https://olivares.ai/terms) |
| **Contact** | hello@olivares.ai |

<br>

---

<div align="center">

<br>

Alma is proprietary software. All rights reserved.
This repository serves as public documentation and a point of contact for issue reporting.

<br>

*Built by [olivares.ai](https://olivares.ai)*

*Give your AI a soul.*

</div>
