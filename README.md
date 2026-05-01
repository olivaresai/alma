<div align="center">

<img src="alma-banner.png" alt="Alma by olivares.ai" width="600" />

<br>
<br>

### The AI that remembers

Every AI conversation starts from scratch.
Weeks of context, preferences, decisions — gone the moment you close the tab.

**Alma changes that.**

<br>

[![Website](https://img.shields.io/badge/olivares.ai-FE9A37?style=for-the-badge&logoColor=1A1A19)](https://olivares.ai)
[![Launch App](https://img.shields.io/badge/Launch_Alma-1A1A19?style=for-the-badge)](https://alma.olivares.ai)
[![Documentation](https://img.shields.io/badge/Docs-2E2E2C?style=for-the-badge)](https://olivares.ai/docs)

</div>

<br>

Alma is a persistent memory layer for AI. It captures facts, preferences, decisions, and behavioral patterns from your conversations — and makes them available across every session, every tool, every platform.

Day 1 and day 100 feel completely different. Your AI stops forgetting. It starts *understanding*.

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
When reviewing code -> check errors first
Use bullet points for technical topics
Always suggest tests for new functions
```

</td>
</tr>
</table>

<br>

### Soul Engine

All three layers feed into the **Soul Engine** — a structured personality and context framework with 12 configurable blocks organized into three sections:

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

**Chat with Memory**
Full streaming chat powered by Claude. Tool use, web search, document generation, canvas artifacts — all with your complete memory context. Conversation folders, tags, pinning, search.

**Environments**
Separate memory spaces for different contexts — work, personal, projects. Each environment has its own soul, its own memories, its own knowledge.

**Voice**
Speech-to-text via Deepgram Nova-2. Text-to-speech via ElevenLabs. Talk to your AI naturally, and it remembers what you said.

</td>
<td width="50%" valign="top">

**Powered by Claude**
Three Anthropic Claude models: Haiku (fast, everyday tasks), Sonnet (balanced quality and speed), and Opus (deep reasoning, complex work). Switch models mid-conversation.

**Image Studio**
Generate images with Replicate Flux Pro and Leonardo AI. Style presets, size options, and a full generation history gallery. BYOK supported.

**Video Studio**
Generate videos with Runway Gen-4. Text-to-video and image-to-video. Project management with scene planning, stitching, and YouTube metadata generation.

**Music Studio**
Generate music with ElevenLabs Music. Studio-grade audio up to 10 minutes. Vocals, lyrics, genre presets. Separate subscription tiers.

**Audio Generation**
Create music and audio with MiniMax Music 1.5. Up to 4 minutes per generation with vocals and lyrics support. Included in Pro and Max plans.

**Export Everything**
Conversations to PDF, DOCX, HTML, Markdown. Memories to JSON and XLSX. Full data dumps in the portable `.alma` format with import and deduplication.

**Bring Your Own Keys**
Use your own API keys for Anthropic, Replicate, and Leonardo. BYOK keys encrypted at rest with AES-256-GCM. Available on the Max plan.

</td>
</tr>
</table>

<br>

<table>
<tr>
<td width="33%" valign="top">

**Code Workspace**
Agent-powered code workspace. Write, review, test, explain, refactor, and debug code — all with your memory context. File management, search, Git operations, and skill execution.

</td>
<td width="33%" valign="top">

**Flashcards**
Spaced repetition learning with SM-2 algorithm. Create flashcards from your conversations and memories. Due date tracking and performance stats.

</td>
<td width="33%" valign="top">

**Ideas & Tasks**
Quick notes with reminders. Scheduled tasks that execute automatically — summaries, reports, reminders, and custom prompts on your schedule.

</td>
</tr>
</table>

<br>

---

<br>

## Get Alma

<table>
<tr><th>Platform</th><th>Access</th><th>Best For</th></tr>
<tr>
<td><strong>Web App</strong></td>
<td><a href="https://alma.olivares.ai">alma.olivares.ai</a></td>
<td>Everyone — sign up and chat instantly</td>
</tr>
<tr>
<td><strong>MCP Server</strong></td>
<td><a href="https://www.npmjs.com/package/@olivaresai/alma-mcp"><code>npm i @olivaresai/alma-mcp</code></a></td>
<td>Claude Desktop, Cursor, Windsurf</td>
</tr>
<tr>
<td><strong>VSCode Extension</strong></td>
<td><a href="https://marketplace.visualstudio.com/items?itemName=olivares.alma-vscode">VS Code Marketplace</a></td>
<td>Development workflow</td>
</tr>
<tr>
<td><strong>JavaScript SDK</strong></td>
<td><a href="https://www.npmjs.com/package/@olivaresai/alma-sdk"><code>npm i @olivaresai/alma-sdk</code></a></td>
<td>Node.js / TypeScript integrations</td>
</tr>
<tr>
<td><strong>REST API</strong></td>
<td><a href="https://olivares.ai/developers">Developer Docs</a></td>
<td>Backend integrations (Max plan)</td>
</tr>
<tr>
<td><strong>Android / iOS</strong></td>
<td>Coming Soon</td>
<td>Mobile — full chat with biometric auth</td>
</tr>
</table>

<br>

---

<br>

## Models

**3 chat tiers** — all from Anthropic Claude.

| Tier | Model | Context | Starter | Pro | Max |
|------|-------|---------|:-------:|:---:|:---:|
| Fast | Claude Haiku 4.5 | 200K | Yes | Yes | Yes |
| Balanced | Claude Sonnet 4.6 | 200K | Yes | Yes | Yes |
| Powerful | Claude Opus 4.7 | 1M | — | Yes | Yes |

**Image generation:**

| Provider | Model | Cost/Image |
|----------|-------|------------|
| Replicate | Flux Pro 1.1 | ~$0.04 |
| Leonardo AI | Lucid Origin | ~$0.02 |

**Video generation:**

| Provider | Models | Pricing |
|----------|--------|---------|
| Runway | Gen-4 Turbo, Gen-4.5 | Credit-based |

**Audio & Music:**

| Provider | Model | Included In |
|----------|-------|-------------|
| MiniMax Music 1.5 (via Replicate) | Up to 4 min, vocals | Pro and Max plans |
| ElevenLabs Music | Up to 10 min, studio-grade | Pro and Max plans |

All AI features consume from a single cost-weighted weekly USD budget. BYOK available on the Max plan.

<br>

---

<br>

## Plans

Three plans. One weekly USD AI budget that covers chat, voice, images, video and music from a single pool. Resets every Monday.

| | Starter | Pro | Max |
|---|:---:|:---:|:---:|
| **Price** | $14/mo | $29/mo | $99/mo |
| **Weekly AI budget** | $2 | $5 | $15 |
| **Chat models** | Haiku + Sonnet | + Opus 1M | + Opus 1M |
| **Memories / episodes / procedures** | Unlimited | Unlimited | Unlimited |
| **Image Studio** (Flux Pro + Leonardo) | Included | Included | Included |
| **Voice** (STT + TTS) | Included | Included | Included |
| **Video Studio** (Runway Gen-4 + HeyGen) | — | Included | Included |
| **Audio** (MiniMax Music 1.5) | — | Included | Included |
| **Studio-grade Music** (ElevenLabs Music) | — | Included | Included |
| **REST API · VSCode · MCP · SDK** | — | — | Included |
| **Bring Your Own Keys (BYOK)** | — | — | Included |
| **Top-ups** | Yes | Yes | Yes |
| **Support SLA** | 72h | 48h | 24h |

Annual billing saves 2 months on all plans. All paid features share a single weekly budget — no separate add-ons.

Billing is processed by **Polar Software, Inc.** as our Merchant of Record (Polar uses Stripe as a card-network provider).

[**Compare plans in detail &rarr;**](https://olivares.ai/pricing)

<br>

---

<br>

## REST API

100+ endpoints covering every aspect of the memory system. JSON responses. Streaming chat via SSE. Requires the **Max** plan.

**Base URL**
```
https://alma.olivares.ai/api/v1
```

**Authentication:**
```bash
# API Key (recommended)
curl -H "X-API-Key: alma_sk_..." https://alma.olivares.ai/api/v1/memories

# JWT Bearer
curl -H "Authorization: Bearer eyJ..." https://alma.olivares.ai/api/v1/memories
```

### Endpoints

<details>
<summary><strong>Context Assembly</strong> — Build AI context from memory</summary>

```http
POST   /context/assemble         Build the full AI context
POST   /context/continue         Continue an existing session
POST   /context/focus            Update the active context focus
POST   /context/preview          Preview the assembled system prompt
```
</details>

<details>
<summary><strong>Memories</strong> — CRUD + semantic search</summary>

```http
GET    /memories                 List memories with filters
GET    /memories/search          Search (keyword, semantic, or hybrid)
GET    /memories/:id             Get a specific memory
POST   /memories                 Create a memory
PUT    /memories/:id             Update a memory
DELETE /memories/:id             Delete a memory
POST   /memories/extract         AI-powered extraction from text
```
</details>

<details>
<summary><strong>Chat</strong> — Streaming conversations with memory</summary>

```http
GET    /chat/models              List available models
GET    /chat/budget              Current budget status
POST   /chat/conversations       Create a conversation
GET    /chat/conversations       List conversations
POST   /chat/conversations/:id/messages  Send message (SSE streaming)
POST   /chat/conversations/:id/retry     Retry last response
POST   /chat/conversations/:id/fork      Fork conversation
```
</details>

<details>
<summary><strong>Episodes & Procedures</strong></summary>

```http
GET    /episodes                 List episode summaries
POST   /episodes                 Create an episode
GET    /procedures               List learned procedures
POST   /procedures               Create a procedure
POST   /procedures/:id/success   Mark successful execution
```
</details>

<details>
<summary><strong>Soul & Blocks</strong> — Personality configuration</summary>

```http
GET    /blocks                   List all memory blocks
POST   /blocks/preset            Apply a soul preset
PUT    /blocks/:label            Update a block
POST   /soul/versions/snapshot   Create a version snapshot
POST   /soul/versions/:id/restore  Restore a previous version
```
</details>

<details>
<summary><strong>Media</strong> — Images, Video, Voice, Audio, Music</summary>

```http
POST   /images/generate          Generate an image
POST   /video/generate           Generate a video
POST   /voice/transcribe         Speech-to-text
POST   /voice/synthesize         Text-to-speech
POST   /audio/generate           Generate audio/music
POST   /music/generate           Music Studio generation
```
</details>

<details>
<summary><strong>More</strong> — Environments, Files, Export, Teams, BYOK, Auth</summary>

```http
# Environments
GET    /environments             List memory spaces
POST   /environments             Create a new environment

# Files & Export
POST   /files/upload             Upload files (images, docs, text)
GET    /export/all               Full GDPR data export

# Teams
POST   /teams                    Create a team
POST   /teams/:id/invitations    Invite members

# BYOK
PUT    /byok/:provider           Save encrypted API key
GET    /byok/:provider/test      Test a provider key

# Auth (JWT, OAuth, 2FA, API Keys)
POST   /auth/register            Create account (Turnstile)
POST   /auth/login               Sign in
POST   /auth/2fa/enable          Enable TOTP 2FA
```
</details>

<br>

### Quick Example

```bash
# Save a memory
curl -X POST https://alma.olivares.ai/api/v1/memories \
  -H "X-API-Key: alma_sk_..." \
  -H "Content-Type: application/json" \
  -d '{"content": "User prefers dark mode", "category": "preference", "importance": 8}'

# Search memories
curl "https://alma.olivares.ai/api/v1/memories/search?q=preferences&mode=hybrid" \
  -H "X-API-Key: alma_sk_..."

# Assemble context for your AI
curl -X POST https://alma.olivares.ai/api/v1/context/assemble \
  -H "X-API-Key: alma_sk_..." \
  -H "Content-Type: application/json" \
  -d '{"maxTokens": 4000}'
```

<br>

---

<br>

## MCP Server

Connect any MCP-compatible AI to Alma's memory layer.

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

**35 tools** — memory, context, chat, search, episodes, procedures, environments, image generation, video, code workspace, and more.

**10 resources** — soul, memories, environments, conversations, budget, blocks, episodes, procedures, video budget, memories by category.

Compatible with **Claude Desktop**, **Cursor**, **Windsurf**, and any MCP-compatible client.

<br>

---

<br>

## VSCode Extension

**Install:** [`alma-vscode`](https://marketplace.visualstudio.com/items?itemName=olivares.alma-vscode) on the VS Code Marketplace

- **Sidebar chat** with streaming responses and full memory context
- **Memory browser** — search, filter, and manage memories from the IDE
- **Soul block editor** — configure AI personality with presets
- **Context focus** — Alma knows what file and project you're working on
- **Environment switching** — jump between memory spaces from the command palette
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

// Assemble context
const context = await alma.context.assemble({ maxTokens: 4000 });

// Save a memory
await alma.memories.create({
  content: 'User prefers TypeScript',
  category: 'preference',
  importance: 8,
});

// Stream a chat message
await alma.chat.sendMessage(conversationId, {
  content: 'Hello',
  onToken: (token) => process.stdout.write(token),
});
```

<br>

---

<br>

## Agent Tools

When chatting with Alma, the AI has access to specialized tools:

| Tool | Description |
|------|-------------|
| `update_memory_block` | Edit soul blocks — worldview, style guide, user profile |
| `search_memories` | Semantic search across long-term memory |
| `search_conversations` | Search past conversation episodes |
| `save_memory` | Save new facts to long-term memory |
| `web_search` | Search the web (Brave + Tavily) |
| `deep_research` | Comprehensive multi-source web research |
| `create_document` | Generate files (DOCX, XLSX, PPTX, MD, TXT, HTML, SVG) |
| `open_canvas` | Create interactive canvas artifacts |
| `edit_canvas` | Edit existing canvas artifacts |

Tools execute transparently with real-time streaming feedback.

<br>

---

<br>

## Internationalization

15 fully localized languages across the entire interface:

Arabic, Chinese, Dutch, English, French, German, Hindi, Italian, Japanese, Korean, Portuguese, Russian, Spanish, Turkish, Ukrainian

<br>

---

<br>

## Security & Privacy

Your cognitive data is the most personal data there is. We treat it that way.

- **Encryption** — All data encrypted at rest and in transit. BYOK keys use AES-256-GCM with per-record key derivation
- **Authentication** — PBKDF2-SHA512 (100K iterations). API keys hashed with HMAC-SHA256. JWT with httpOnly cookies
- **2FA** — TOTP with recovery codes. Lockout protection after 5 failed attempts
- **OAuth** — Sign in with Google or GitHub
- **CSRF** — Origin validation on all state-changing requests
- **Rate Limiting** — Per-minute and per-day limits with IP-based protection. Durable Objects for atomic enforcement
- **Isolation** — Memories isolated per account and per environment
- **No tracking** — No tracking cookies, no third-party analytics, no data selling
- **GDPR** — Full data export and deletion. No retention after deletion
- **Audited** — 13 comprehensive security audits. Swiss-grade quality principles

<br>

---

<br>

## Infrastructure

Built on Cloudflare's global edge network.

| Component | Technology |
|-----------|-----------|
| **API** | Cloudflare Workers (Hono 4) |
| **Database** | Cloudflare D1 (96 migrations) |
| **Vector Search** | Cloudflare Vectorize (2 indexes) |
| **Embeddings** | OpenAI + Cloudflare Workers AI fallback |
| **File Storage** | Cloudflare R2 |
| **Cache & Rate Limiting** | Cloudflare KV |
| **Budget Coordination** | Cloudflare Durable Objects |
| **Background Jobs** | Cloudflare Queues + DLQ |
| **Frontend** | React 19, Vite 6, Tailwind 4 |
| **Billing** | Polar (Merchant of Record) — subscriptions + top-ups |

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
| **Pricing** | [olivares.ai/pricing](https://olivares.ai/pricing) |
| **Philosophy** | [olivares.ai/philosophy](https://olivares.ai/philosophy) |
| **SDK** | [@olivaresai/alma-sdk](https://www.npmjs.com/package/@olivaresai/alma-sdk) |
| **MCP** | [@olivaresai/alma-mcp](https://www.npmjs.com/package/@olivaresai/alma-mcp) |
| **VSCode** | [alma-vscode](https://marketplace.visualstudio.com/items?itemName=olivares.alma-vscode) |
| **Types** | [@olivaresai/alma-types](https://www.npmjs.com/package/@olivaresai/alma-types) |
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
