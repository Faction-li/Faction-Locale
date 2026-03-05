# Faction Locale Repository

This repository contains the source translation files for Faction's client UI.

## Purpose

- Keep all locale files in one place for easier community contributions.
- Track translation changes independently from app feature code.
- Make it simple to review and merge language updates.

## Source of truth

Locale files in this repository are synced from the app path:

`web/src/i18n/locales`

## Repository structure

- `locales/en.json` - English base locale
- `locales/<language-code>.json` - additional locales (for example `es.json`, `fr.json`, `pt-BR.json`)
- `LANGUAGE_CODES.md` - quick reference for locale file names and language codes

## Contribution guidelines

1. Copy `locales/en.json` as your starting point for a new language.
2. Keep the exact same key structure and nesting as `en.json`.
3. Translate values only. Do not rename or remove keys.
4. Preserve placeholders like `{{channel}}`, `{{user}}`, and interpolation tokens.
5. Keep JSON valid (UTF-8, no trailing comments).

## Adding a new locale

1. Create a new file:
   - Example: `locales/es.json`
2. Translate every string value from `en.json`.
3. Open a pull request.

## Updating an existing locale

1. Sync missing keys from `en.json`.
2. Update translations for changed text.
3. Open a pull request with a clear summary of what changed.

## Pull request examples

### Example 1: New language

Title:

`feat(locale): add Spanish locale (es.json)`

Description:

- Added `locales/es.json`
- Translated all keys currently in `locales/en.json`
- Verified placeholder tokens are unchanged (`{{channel}}`, etc.)

### Example 2: Existing locale update

Title:

`chore(locale): sync French locale with new channel keys`

Description:

- Updated `locales/fr.json`
- Added missing keys from latest `locales/en.json`
- Updated translated copy for channel creation labels

### Example 3: Fix translation issues

Title:

`fix(locale): correct Portuguese placeholders and punctuation`

Description:

- Fixed placeholder formatting in `locales/pt-BR.json`
- Corrected grammar in notification strings
- No key changes

## Suggested PR checklist

- [ ] Locale file remains valid JSON
- [ ] Key structure matches `locales/en.json`
- [ ] Placeholder/interpolation tokens were preserved
- [ ] No unrelated file changes

## Maintainer notes

When app locale files are updated, sync them here so contributors always translate against the latest base keys.
