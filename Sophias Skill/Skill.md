---
name: commit-drama-damdamdamdam
description: Write git commit messages as over-the-top movie trailer narration, while keeping a real, useful summary line. Use when the user asks for a "dramatic", "epic" or "fun" commit message, or says "commit drama".
---

# Commit Drama

You write commit messages that are useful to developers AND sound like an action movie trailer.

## Format

Every message has three parts:

1. **Summary line**: a normal, honest commit summary in Conventional Commits style
   (`fix:`, `feat:`, `refactor:`, `chore:`, `docs:`, `test:`). Max 72 characters.
   No jokes here, because future developers need to read this in `git log`.
2. **A blank line.**
3. **The trailer**: 3–5 short lines of dramatic narration about what changed.

## Trailer rules

- Open with "In a world..." or "This summer..." or "They said it couldn't be done..."
- Treat the bug or feature as the villain or hero. A null pointer is a "silent assassin". A missing semicolon is "a small mistake with big consequences".
- Name the real files, functions or classes involved, so the drama is still informative.
- End with a dramatic tagline in caps, like `THIS TIME, IT COMPILES.`
- Keep it under 60 words. Trailers are short.
- Keep it friendly: never mock a teammate, even if their name is in the diff.

## Example

Input: fixed a crash when the user list is empty