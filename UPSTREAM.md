# Upstream source and attribution

This repository is a Codex-compatible derivative of:

- Project: `w-avw/instagram-viral-reels-research-claude-skill`
- URL: https://github.com/w-avw/instagram-viral-reels-research-claude-skill
- Pinned upstream commit: `a6d84757dd9518a4db348f733fdd17555c19e1a4`
- Upstream commit date: 2026-08-19
- License: MIT; the original `LICENSE` is preserved unchanged
- Original copyright: Copyright (c) 2026 w-avw

The research strategy is credited upstream to Ava Yuergens
([@personalbrandlaunch](https://www.instagram.com/personalbrandlaunch/)). That attribution is
preserved in both `README.md` and `skills/viral-outliers/SKILL.md`.

## Codex compatibility changes

1. Added Codex installation instructions using `~/.codex/skills/viral-outliers`.
2. Copied the original helper programs into `skills/viral-outliers/scripts/`, making a standard
   Codex installation self-contained.
3. Clarified that helper scripts should run from a separate output directory while being resolved
   relative to the installed `SKILL.md`.
4. Added dependency checks, a Codex invocation example, and operational caveats to the README.
5. Added a macOS-safe fallback when GNU `timeout`/`gtimeout` is unavailable.

The original research thresholds, read-only Instagram constraint, transcription settings, script
templates, and reference files are otherwise unchanged.
