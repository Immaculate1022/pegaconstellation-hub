# What Runs Today

**Last checked:** 2026-09-07  
Honest snapshot of the public PegaConstellation surface. Prototypes and research code only — not production systems or measured physical results.

## Quick map

| Project | What you can actually do right now | Notes |
|---------|------------------------------------|-------|
| **IOF-Resonance-Core** | Open HTML files locally; run Python smoke tests | Pages currently 404. Local demos work. |
| **AHR-Endpoint** | `cargo build --release` + `cargo test`; dry-run audit script | v0.2.1 prototype. Isolate before any enforcement. |
| **moebius-llama** | `pip install -e .` then `from moebius_llama import patch_any_model` | Experimental adapter. No published model or benchmark claim. |
| **tesseract-medium** | Import and run geometry / tensor examples (v0.3) | Strongest recent geometry substrate. |
| **aetherius-nexus** | Full-stack foundation present | Still early; most interactive features on the TODO list. |
| **iof-design-grammar** | Read the conceptual framework | Systems language, not a runtime. |
| **Hub + STATUS** | This file + [STATUS.md](STATUS.md) | Living map. |

## Concrete commands that work

### IOF-Resonance-Core (local demos)
```bash
git clone https://github.com/Immaculate1022/IOF-Resonance-Core.git
cd IOF-Resonance-Core
# Open in browser:
#   ForensicTelemetry_Standalone.html
#   UnityProtocol_Visualizer.html
bash scripts/smoke_all.sh   # if present
```

### AHR-Endpoint (userspace prototype)
```bash
git clone https://github.com/Immaculate1022/AHR-Endpoint.git
cd AHR-Endpoint
cargo build --release
cargo test
python3 scripts/dry_run_audit.py   # source-level safety check, no agent launch
```
Use only in an isolated environment. Do not point at production hosts.

### Möbius-Llama (editable install)
```bash
git clone https://github.com/Immaculate1022/moebius-llama.git
cd moebius-llama
pip install -e . --no-deps   # or full deps if you have torch/transformers
python -c "from moebius_llama import patch_any_model; print('ok')"
```

### Tesseract Medium
```bash
git clone https://github.com/Immaculate1022/tesseract-medium.git
cd tesseract-medium
# Follow its README for v0.3 lattice / tensor examples
```

## Attribution (required for public use)

```
Infinite Optical Fabric by Gregory Scott Davis, Princeton, NC.
```

## What is *not* claimed

- No measured photonic hardware performance
- No production ransomware containment numbers
- No published model weights or stranger-validated reasoning gains for Möbius-Llama
- No active GitHub Pages demos for Resonance-Core until re-enabled in Settings

For the living pulse and next steps, see **[STATUS.md](STATUS.md)**.
