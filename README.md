# Elements of Style Plugin

An English style editor based on Strunk's *The Elements of Style*. Reviews text for grammar, punctuation, clarity, and conciseness using 18 classic rules of usage and composition.

## What it does

This plugin adds an active editorial reviewer that checks English prose against Strunk's rules. It flags violations, explains the relevant rule, and suggests concrete corrections.

## Components

- **Skill: english-style-editor** — Automatically activates when you ask Claude to review, edit, proofread, or improve English writing
- **Command: /style-check** — Explicitly run a style review on text or a file

## Usage

Ask Claude to review your writing naturally:

- "Check this paragraph for style issues"
- "Proofread my blog post"
- "Tighten up this email"
- "Is this sentence too wordy?"

Or use the slash command:

- `/style-check` then paste your text
- `/style-check` and reference a file

## Rules covered

**Usage (1–7):** Possessives, Oxford comma, parenthetic expressions, compound sentences, comma splices, sentence fragments, dangling modifiers.

**Composition (8–18):** Paragraph structure, topic sentences, active voice, positive form, concrete language, conciseness, sentence variety, parallel construction, word proximity, tense consistency, emphasis placement.

**Words & Expressions:** 40+ commonly misused words and phrases with correct alternatives.

**Form & Spelling:** Numerals, quotations, references, titles, commonly misspelled words.
