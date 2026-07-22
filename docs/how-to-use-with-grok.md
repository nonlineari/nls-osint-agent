# How to use NLS OSINT Agent with Grok

## Method 1 — Custom Instructions / System Prompt (Recommended)

1. Open a new Grok conversation (grok.x.ai or X app).
2. Go to custom instructions / persona settings if available, or simply paste at the top of the first message:
   ```
   [paste full content of agent/SYSTEM_PROMPT_EN.md or SYSTEM_PROMPT_FR.md]
   ```
3. Then chat normally. The Agent stays in character for the whole conversation.
4. For bilingual sessions: start in one language; say "switch to French" or just write in the other language.

## Method 2 — Context Injection (one-shot or multi-turn)

Paste relevant modules + prompt excerpt as needed:

```
Load NLS OSINT Agent modules.
[paste index.json summary or specific module]
You are the NLS OSINT Agent...
```

## Method 3 — GitHub + Local / Studio

```bash
git clone https://github.com/nonlineari/nls-osint-agent.git
# Then feed files into your CIM / Sexy Sequence / local LLM / RAG pipeline
```

Ideal for Xserve rack or Mac Mini cluster knowledge base.

## Method 4 — Grok Tasks / Scheduled

Create a recurring Grok task that runs OSINT monitoring using the Agent persona (e.g. weekly digest of new OSINT resources or HK media competitor signals).

## Pro Tips for @nlsrecords

- Combine with your existing WhatsApp Noise / SMWARP / Wireshark OSINT setups.
- Use for music industry pivots: artist leaks, label competitor GEOINT, vinyl market SOCMINT, TVB/ViuTV monitoring.
- Feed CTF writeups back into the modules as new nodules.
- Keep the French prompt for hybrid HK work / international collabs.
- When live-coding: treat modules as association layers in the Common Information Model.

---

Constructor mode activated.  
`sudo nls-osint-agent`
