# Easytel CRM — Claude Rules

## ⚠️ HARD RULES — NEVER SKIP

1. **NEVER push to git without explicit user confirmation.** Always stop and ask before running any `git push`. Batch all pending changes together and wait for the user to say "push it" or equivalent before pushing.
2. **NEVER write any code until the user explicitly says to go ahead.** Always plan changes first, confirm the user understands and agrees, then write.
3. **Check for clashes/conflicts before applying changes** and warn the user if any are found.

## Project Overview

Single-file CRM (`index.html`) for a small Australian Telco. Supabase backend, GitHub Pages hosting, GitHub Actions deploy.

## How to Apply Changes

- Always edit `index.html` only
- Keep credentials as placeholders (`__SUPABASE_URL__`, `__SUPABASE_ANON__`)
- Adding a field: ALTER TABLE in Supabase → add modal input → add to payload → add to display
