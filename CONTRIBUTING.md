# Contributing to CROSSL

Thanks for your interest in improving CROSSL (Competitive Robotics Open-Source Software Licenses). This repository contains license texts and supporting documentation intended for use in RECF-related robotics software, with special attention to student-centered participation.

## Scope of Contributions

You can contribute to:

- License texts in `licenses/` (wording, structure, clarity)
- Documentation in `README.md` and supporting guides
- Examples and FAQs (especially around competition/student-centered scenarios)
- Typos, formatting, and consistency improvements

You should **not** contribute:

- Legal advice for specific individuals/teams/organizations (keep docs general)
- Content that encourages rule evasion or undermines student-centered participation

## Ground Rules

- Be respectful and constructive.
- Optimize for clarity and practical usability.
- Avoid ambiguous normative language where possible; prefer testable wording.
- Keep changes minimal when editing license texts (small diffs are easier to review).
- Don’t add requirements that conflict with RECF policies or vendor terms (e.g., VEX EULA/TOU).

## Quick Start

1. Fork the repo.
2. Create a branch:
   - `feature/<short-description>` for new work
   - `fix/<short-description>` for corrections
3. Make your changes.
4. Open a pull request (PR) with a clear description (see below).

## Repository Layout (typical)

- `licenses/` - license texts (canonical content)
- `README.md` - high-level overview and summaries
- `CONTRIBUTING.md` - contribution process (this file)

## Making Changes to License Texts

License texts are sensitive. When proposing changes to anything in `licenses/`:

- Explain *why* the change is needed (clarity, enforceability, consistency, etc.).
- Include examples of how real teams/mentors would interpret the old vs new wording.
- Keep formatting consistent (headings, numbering, capitalization).
- Do not rename the license or imply a modified text is an “official CROSSL” version unless you are the steward (see license versioning section in the license itself).

### Compatibility Notes

If your change affects:

- license compatibility with other licenses
- rules around combining codebases
- termination/cure mechanics
- student vs adult obligations

call this out explicitly in your PR description.

## Documentation Changes

For `README.md` and other docs:

- Prefer short bullets where possible.
- Avoid jargon; if you must use it, define it once.
- Keep statements aligned with the actual license text (quote sections if needed).

## Pull Request Checklist

Before opening a PR, ensure:

- [ ] Your change is scoped and focused (one topic per PR when possible)
- [ ] License text references (section numbers) still match after edits
- [ ] `README.md` reflects the current license behavior (no drift)
- [ ] Spelling/formatting is clean and consistent
- [ ] You didn’t introduce contradictory requirements across documents

## PR Template (include in the description)

### What changed?
-

### Why?
-

### Which files / sections?
-

### Impact on users
- Students:
- Adults/mentors:
- Event/competition context:
- Non-competition use:

### Compatibility / distribution notes (if applicable)
-

## Reporting Issues / Requesting Clarifications

If something is confusing or potentially inconsistent:

- Open an issue describing the exact confusing text
- Include a suggested rewrite (even rough is fine)
- If relevant, include a realistic scenario (student team, mentor review, library distribution, etc.)

## Style Guide (lightweight)

- Use `CROSSL-P-1.0` consistently (including hyphenation and version)
- Use “Program” and other defined terms exactly as the license defines them
- Prefer “must” / “may” / “must not” over “should” for requirements
- Avoid abbreviations like “re:” in user-facing docs; use “regarding” instead

## Code of Conduct

Be kind, act in good faith, and assume others are here to help students and the community. Harassment or hostility isn’t welcome.

## Security / Sensitive Reports

If you discover an issue that could cause harm (e.g., clearly exploitable ambiguity intended to enable rule evasion), open a private communication channel if the repository supports it; otherwise, open a normal issue and keep details high-level until maintainers respond.
