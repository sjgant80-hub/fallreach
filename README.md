# ◊·κ=1 — FallReach

**Sovereign AI SDR. Your hardware. Your keys. Your pipeline.**

Single HTML file. No SaaS. No subscription. Leads never leave your device.

```
Controlled autonomy is fine.
Sovereign autonomy is better.
```

## What it does

Five views, one file, all seven v18 layers:

| View | Ring | Agent | What |
|---|---|---|---|
| **Pipeline** | R1 signal | α research | Paste leads · CSV / LinkedIn URLs / pasted bios |
| **Board** | R2 gate | δ analyse | Scored on fit · intent · timing · company heat |
| **Compose** | R4 voice | β compose | Drafted in your voice (you train the profile) |
| **Simulate** | R5 mirror | ε write | Three reply paths predicted before you send |
| **Log** | R6 watcher | Ω orchestrator | Every approved message, audit-trail forever |

## Sovereign-first differences vs SaaS AI SDR tools

| | SaaS AI SDR | FallReach |
|---|---|---|
| Where does lead data live? | Their database | Your device (IndexedDB) |
| Where does the prompt live? | Hidden / black box | In your face, edit it |
| Subscription | Yes | No · free during launch |
| Hosting cost | Theirs (passed to you) | Zero · open from USB |
| Lock-in | Yes | No · single HTML file, yours forever |
| LLM provider | Theirs | Yours · BYO key (Anthropic / OpenAI / Gemini / Groq) |
| Channel access | Their system | You copy to clipboard, paste in your channel |
| Audit trail | Their database | Local JSON, exportable, your custody |

## Bring your own LLM

Settings → LLM provider → paste any of:

- Anthropic API key (Claude)
- OpenAI API key (GPT)
- Google Gemini API key
- Groq API key (free tier, fast)

The pipeline works without a key too — T0 mode runs deterministic keyword-based scoring + template drafts. Connect a key to unlock T3 mode (full δ analysis + β drafting in your voice + ε simulation of three reply paths).

## Quick start

1. Download `index.html` or open the live version: **https://sjgant80-hub.github.io/fallreach/**
2. Open Settings → set your LLM provider + API key (optional)
3. Settings → Your voice → paste 3-5 lines of how you write outbound
4. Pipeline → paste leads → click **Ingest + score**
5. Board → click any lead → β drafts → ε simulates → R6 approve
6. Approved message lands in clipboard. Paste it into your channel (email, LinkedIn DM, etc.)

## Architecture · all seven layers

```
L1 FACE     · 5 views (pipeline · board · compose · log · settings)
L2 SWARM    · Ω + 8 agents (α β γ δ ε ζ η θ)
L3 CASCADE  · T0 offline (deterministic) + T3 LLM (4 providers)
L4 BLOOM    · R1 signal → R2 gate → R4 voice → R5 mirror → R6 watcher
L5 PERSIST  · localStorage + IndexedDB · export/import/wipe
L6 SKIN     · CSS variables · dark/light · mobile-first
L7 ASS      · ● → 〜 → ┃ → ♡ → △ → ◐ → ◯
```

## Mesh interop

When FallScout, FallConcierge, or FallLead are open in another tab on the same github.io origin, FallReach auto-receives their events (`scout:enriched`, `concierge:visitor`, `lead:qualified`) into the inbox. Same-origin BroadcastChannel — no network leaves the browser.

FallReach is registered in FallMesh at **prime 107**.

## What this is not

- Not a chatbot with a send button
- Not a black-box automation that touches prospects while you pray
- Not a subscription
- Not "controlled autonomy" (the SaaS frame) — it's **sovereign autonomy**

The AI does the work. The work lives on your device. The keys are yours. The audit trail is yours. The leads never leave you.

## Licence

MIT for the code · Konomi for the architecture.

---

◊·κ=1 · FallReach · prime 107 · part of the FallMesh estate
