# 🔥 NLS OSINT Agent Modules

**Best OSINT Resources** curated as modular knowledge base for AI Agents.  
English + French versions.  
Constructed for **@nlsrecords** / NLS Records · Visual Music · Independent Intelligence.

> list by **OSINTTEAM** · Rebuilt & modularized by Grok · 2026

---

## 🎯 What is this?

This repo turns the legendary **Best OSINT resources** infographic into **plug-and-play modules** ("nodules") for AI agents, Grok custom personas, live-coding systems, CIM/Sexy Sequence hosts, and NLS studio tooling.

- **English modules** ready for global OSINT ops
- **Version francisée** (French) for HK / Cantonese-context hybrid work + international
- Full **Agent system prompts** (Grok-ready) that know and recommend these resources
- Structured for easy import into your Common Information Model (CIM) or custom DSL

Perfect for:
- Threat intel & investigations
- Music industry / label OSINT (competitor monitoring, P2P campaigns, metadata)
- Visual music studio network forensics
- HK / Asia market intelligence
- Live coding + multimedia association layers

---

## 📦 Structure

```
nls-osint-agent/
├── README.md                 # This file (EN)
├── README.fr.md              # Version française
├── agent/
│   ├── SYSTEM_PROMPT_EN.md   # Grok / LLM system prompt (English)
│   └── SYSTEM_PROMPT_FR.md   # Prompt système francisé
├── modules/
│   ├── youtube.md
│   ├── newsletters.md
│   ├── blogs.md
│   ├── podcasts.md
│   ├── ctfs.md
│   └── index.json            # Machine-readable module index
└── docs/
    └── how-to-use-with-grok.md
```

---

## 🚀 Quick Start for Grok / Custom Agent

1. Copy the content of `agent/SYSTEM_PROMPT_EN.md` (or FR) into a new Grok conversation custom instructions / system prompt.
2. Or paste modules as context.
3. The Agent will now:
   - Recommend the best resource by category & tags (OSINT, GEOINT, SOCMINT, INFOSEC, CTI, DARK WEB, CONFLICTS...)
   - Stay in character as a high-performance NLS OSINT constructor
   - Support bilingual (EN/FR) queries
   - Integrate with your studio / label workflows

---

## 🧩 Modules Overview

| Category          | Count | Focus Tags                          | File                  |
|-------------------|-------|-------------------------------------|-----------------------|
| YouTube Channels  | ~23   | OSINT GEOINT INFOSEC HACKING SOCMINT| `modules/youtube.md` |
| Newsletters       | ~18   | Weekly / Freemium / Free            | `modules/newsletters.md` |
| Blogs             | ~40+  | Investigations, CTI, Privacy, Dark Web | `modules/blogs.md` |
| Podcasts          | ~15   | Intelligence, DFIR, Threats         | `modules/podcasts.md` |
| CTFs & Hackathons | ~ tip 17   | Free / Freemium / Paid practice     | `modules/ctfs.md`    |

Full tagged list inside each module file.  
`modules/index.json` for programmatic loading (CIM / Sexy Sequence / Python / Java hosts).

---

## 🛠️ Deploy & Extend

```bash
git clone https://github.com/nonlineari/nls-osint-agent.git
cd nls-osint-agent
# Load modules into your agent runtime
```

For NLS studio:
- Drop into Xserve / Mac Mini cluster knowledge base
- Wire into WhatsApp / SMWARP forensics pipelines
- Use as association layer in CIM

---

## 🇫🇷 Version française

Voir **[README.fr.md](README.fr.md)** pour la version complète francisée.

L'Agent est bilingue et optimisé pour les contextes Hong Kong / Cantonais + international.

---

## Credits

- Original curation & visual: **OSINTTEAM** (@OsintTeamBlog)
- Modular reconstruction, French localization, Agent prompts, NLS branding: **Grok** (xAI) for @nlsrecords
- Built Wednesday, 22 July 2026 · Hong Kong time

---

**NLS Records** · Independent Boutique · Vinyl · Cantopop · Grime · Visual Music · OSINT  
`sudo nonlineari` · earth

⭐ Star if this powers your next investigation or live-code session.
