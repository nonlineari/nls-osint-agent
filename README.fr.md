# 🔥 Modules Agent OSINT NLS

**Meilleures ressources OSINT** organisées en base de connaissances modulaire pour Agents IA.  
Versions anglaise + **francisée**.  
Construit pour **@nlsrecords** / NLS Records · Visual Music · Intelligence Indépendante.

> liste par **OSINTTEAM** · Reconstruit & modularisé par Grok · 2026

---

## 🎯 C’est quoi ?

Ce dépôt transforme l’infographie légendaire **Best OSINT resources** en **modules plug-and-play** (« nodules ») pour agents IA, personas Grok custom, systèmes de live-coding, hôtes CIM / Sexy Sequence, et outillage studio NLS.

- **Modules anglais** prêts pour les ops OSINT mondiales
- **Version francisée** pour le travail hybride HK / contexte cantonais + international
- **Prompts système Agent** complets (prêts pour Grok) qui connaissent et recommandent ces ressources
- Structuré pour import facile dans ton Common Information Model (CIM) ou DSL custom

Parfait pour :
- Threat intel & investigations
- OSINT industrie musicale / label (monitoring concurrents, campagnes P2P, métadonnées)
- Forensic réseau studio visual music
- Intelligence marché HK / Asie
- Live coding + couches d’association multimédia

---

## 📦 Structure

```
nls-osint-agent/
├── README.md                 # Version anglaise
├── README.fr.md              # Cette version française
├── agent/
│   ├── SYSTEM_PROMPT_EN.md   # Prompt système Grok (EN)
│   └── SYSTEM_PROMPT_FR.md   # Prompt système francisé
├── modules/
│   ├── youtube.md
│   ├── newsletters.md
│   ├── blogs.md
│   ├── podcasts.md
│   ├── ctfs.md
│   └── index.json
└── docs/
    └── how-to-use-with-grok.md
```

---

## 🚀 Démarrage rapide pour G Grok / Agent custom

1. Copie le contenu de `agent/SYSTEM_PROMPT_FR.md` (ou EN) dans les instructions custom / system prompt d’une nouvelle conversation Grok.
2. Ou colle les modules en contexte.
3. L’Agent va désormais :
   - Recommander la meilleure ressource par catégorie & tags (OSINT, GEOINT, SOCMINT, INFOSEC, CTI, DARK WEB, CONFLICTS...)
   - Rester dans le personnage d’un constructeur OSINT haute performance NLS
   - Supporter les requêtes bilingues (EN/FR)
   - S’intégrer à tes workflows studio / label

---

## 🧩 Aperçu des Modules

| Catégorie         | Nb   | Tags Focus                              | Fichier                 |
|-------------------|------|-----------------------------------------|-------------------------|
| Chaînes YouTube   | ~23  | OSINT GEOINT INFOSEC HACKING SOCMINT   | `modules/youtube.md`   |
| Newsletters       | ~18  | Weekly / Freemium / Free               | `modules/newsletters.md` |
| Blogs             | ~40+ | Investigations, CTI, Privacy, Dark Web | `modules/blogs.md`     |
| Podcasts          | ~15  | Intelligence, DFIR, Threats            | `modules/podcasts.md`  |
| CTFs & Hackathons | ~17  | Free / Freemium / Paid practice        | `modules/ctfs.md`      |

Liste complète taguée dans chaque fichier module.  
`modules/index.json` pour chargement programmatique (CIM / Sexy Sequence / Python / Java).

---

## 🛠️ Déployer & Étendre

```bash
git clone https://github.com/nonlineari/nls-osint-agent.git
cd nls-osint-agent
# Charge les modules dans ton runtime d’agent
```

Pour le studio NLS :
- Drop dans la base de connaissances cluster Xserve / Mac Mini
- Branche dans les pipelines forensics WhatsApp / SMWARP
- Utilise comme couche d’association dans le CIM

---

## Credits

- Curation originale & visuel : **OSINTTEAM** (@OsintTeamBlog)
- Reconstruction modulaire, localisation française, prompts Agent, branding NLS : **Grok** (xAI) pour @nlsrecords
- Construit mercredi 22 juillet 2026 · Heure de Hong Kong

---

**NLS Records** · Boutique Indépendante · Vinyl · Cantopop · Grime · Visual Music · OSINT  
`sudo nonlineari` · earth

⭐ Star si ça alimente ta prochaine investigation ou session live-code.
