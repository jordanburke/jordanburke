# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with the jordanburke GitHub profile repository.

## Overview
This is Jordan Burke's GitHub profile repository. The `README.md` file in this repository appears on the GitHub profile page at https://github.com/jordanburke.

## Purpose
- **Profile README**: Professional summary, featured projects, and contact details
- **Public face**: Represents Jordan's public presence on GitHub
- **Project showcase**: Highlights the public OSS portfolio anchoring the ecosystem

## Repository Structure
```
jordanburke/
├── README.md    # GitHub profile README (displayed on profile page)
└── CLAUDE.md    # This file - guidance for Claude Code
```

## Positioning Source of Truth

Positioning and narrative for this README are driven by:
- **`~/IdeaProjects/personal/docs/ECOSYSTEM_VISION.md`** — Three Pillars narrative (Functional Foundations → MCP Protocol Layer → AI-First Platforms)
- **`~/IdeaProjects/personal/repositories/REGISTRY.md`** — Authoritative list of repos with tier (Flagship / Maintained / Archive) and status

When updating the README, reconcile against those two files first. Every Flagship, public repo in the Vision should be represented here.

## Featured Project Categories (Three Pillars)

1. **Functional Foundations** — functype, functype-log, functype-os, eslint-functype, ts-builds, ts-builds-template, typescript-library-template, ts-case-convert, supabase-typed-query
2. **MCP Protocol Layer** — Personal (reddit, joplin, microsoft-todo, mcp-proxy, dakboard, duckpond) and SapientsAI life-sciences servers (ms-365, dokploy, somamcp, biomcp, openfda, patents, edgartools, NCCN, ncats-translator)
3. **Utilities** — edl, timecode-converter, envpkt

Note: the AI-First Platforms pillar from `ECOSYSTEM_VISION.md` is intentionally omitted from the public README. cQuenced and Civala are private; agent-todo is already covered in the MCP section, so a separate pillar section would just duplicate it.

## Maintenance Guidelines

### When Updating README.md
1. Keep tone professional and concise — no emojis unless explicitly requested
2. Add new Flagship-tier public repos promptly (cross-check against REGISTRY.md)
3. Verify every link resolves before committing
4. Maintain Three Pillars grouping rather than flat lists
5. **Never list private repos** (cQuenced, Civala, cquenced-dev/*, civala-ai/*, etc.) — this README is public and must contain only public OSS

### What NOT to include
- Archived / Dormant repos from the registry (e.g., kuzudb-mcp-server, old eslint-config-functype splits)
- Precise counts that go stale quickly (prefer qualitative phrasing like "extensive portfolio")
- Scala certification or other pre-2020 credentials — positioning is current AI/FP work

## Related Repositories (for cross-reference)

Local paths on this machine — useful when pulling details for README updates:
- `/Users/jordanburke/IdeaProjects/functype/` — Core FP library
- `/Users/jordanburke/IdeaProjects/reddit-mcp-server/`
- `/Users/jordanburke/IdeaProjects/joplin-mcp-server/`
- `/Users/jordanburke/IdeaProjects/microsoft-todo-mcp-server/`
- `/Users/jordanburke/IdeaProjects/mcp-proxy/`
- `/Users/jordanburke/IdeaProjects/personal/` — Knowledge base (vision + registry live here)

## Notes for Claude
- Treat this repository as a professional portfolio piece
- First impression for potential collaborators, clients, and employers
- Updates should maintain consistency with Jordan's current technical focus (functional TS, MCP ecosystem, AI-first platforms)
- When in doubt about what belongs: check `ECOSYSTEM_VISION.md` and `REGISTRY.md` in the personal repo
