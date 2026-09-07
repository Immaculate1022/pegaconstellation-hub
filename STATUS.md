# PegaConstellation Status Pulse

**Last updated:** 2026-09-07 (AI-assisted)

## Overall Health

Public surface remains coherent and stable. Consistent IOF Attribution License, improved READMEs, hub with **WHAT_RUNS_TODAY.md**, AI Operations Charter in place. Geometry substrate (`tesseract-medium`) at **v0.3**. AHR-Endpoint v0.2.1 prototype. Möbius-Llama editable install verified. IOF-Resonance-Core is the primary showcase: local HTML works; GitHub Pages is the chosen public host and is one Settings click away from going live.

## Hosting decision (2026-09-07)

**Choice: GitHub Pages first.**  
- Workflow already present; URLs match existing docs.  
- Workflow now stages **only** the static demos (`index.html`, `ForensicTelemetry_Standalone.html`, `UnityProtocol_Visualizer.html` + `.nojekyll`) so the public site is clean.  
- Cloudflare Pages remains the natural backup if unlimited bandwidth or a non-github.io URL is wanted later.  
- Local HTML stays the always-available fallback.

**Remaining human step to go live:**  
IOF-Resonance-Core → **Settings → Pages → Source: GitHub Actions** → re-run (or wait for) the “Deploy GitHub Pages” workflow → approve `github-pages` environment if prompted.

## Core Projects

| Project | Health | Notes |
|---------|--------|-------|
| IOF-Resonance-Core | Strong | Local demos work; Pages workflow ready (awaiting Settings) |
| AHR-Endpoint | Good | v0.2.1 prototype; dry-run audit path |
| aetherius-nexus | Good | Full-stack foundation; interactive tools on roadmap |
| moebius-llama | Good | Editable install + import verified |
| iof-design-grammar | Good | Conceptual framework |
| IOF-Resonant-Hardware | Good | Spec present |
| **tesseract-medium** | **Strong** | **v0.3** — tensors, orientation, lattice |

## Prototype boundaries

| Project | Publicly supported today | Not yet established |
|---|---|---|
| **AHR-Endpoint** | Rust prototype, Aya/eBPF path, dry-run audit | Production enforcement |
| **Möbius-Llama** | Editable install, experimental adapter | Published model / stranger-run confirmation |
| **IOF-Resonance-Core** | Local HTML demos, smoke tests | Live Pages (until Settings flip) or measured photonic results |

## Human-Only Actions (minimal)

1. **Restore Pages** (highest leverage for demos): Settings → Pages → Source: **GitHub Actions**, then run the workflow once.  
2. **Pin 4–6 key repos** on the profile.  
3. Optional: GitHub org later; Cloudflare Pages later if needed.

Everything else continues under the standing charter.

---

*This file is intended to be updated periodically by supporting AI systems.*
