# .local/ — Local-only files (NEVER publish)

Files here stay on this machine. They are **excluded** from ClawHub and GitHub
distribution per the `workbuddy-skill-publish` rules (§4 File Separation:
session-specific notes & internal review archives).

## Contents

- `agent-design-review.md` — Personal skill review archive. Contains references
  to internal Tencent Cloud materials and project-specific design critiques.
  This is a working/audit document, not part of the publishable skill.

## Why a dot-prefixed dir

`.local/` is dot-prefixed so it is skipped by default file scans and never
copied into the clean publish temp dir.
