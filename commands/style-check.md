---
name: style-check
description: Review text for style, grammar, and clarity using Strunk's Elements of Style
allowed_tools:
  - Read
  - Edit
  - Write
  - Glob
  - Grep
---

# /style-check

Review the user's text against Strunk's *The Elements of Style* rules.

## Instructions

1. Identify what text to review:
   - If the user provided text inline after the command, use that
   - If the user referenced a file, read it
   - If neither, ask what text to review

2. Load the english-style-editor skill and follow its review workflow:
   - Read all four reference files for a thorough review
   - Scan for violations of the 18 rules
   - Check for commonly misused words and expressions
   - Check formatting and form

3. Present findings using the skill's output format:
   - Errors (clear violations)
   - Improvements (style strengthening)
   - Notes (minor preferences)

4. Offer a clean revised version of the full text.

5. If the text is in a file and the user wants changes applied, use Edit to apply them directly.
