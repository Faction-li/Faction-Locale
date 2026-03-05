# Language Codes Reference

Use this file when naming locale files so contributors do not need to look up codes.

## File naming format

- Preferred format: `locales/<code>.json`
- Language-only code: `es`, `fr`, `de`
- Language + region code (BCP 47): `pt-BR`, `en-GB`, `zh-CN`
- Keep region part uppercase: `en-US`, `es-MX`
- Keep script part title case: `zh-Hans`, `zh-Hant`

Examples:

- `locales/es.json`
- `locales/pt-BR.json`
- `locales/zh-Hant.json`

## Common language codes

| Code | Language |
|---|---|
| af | Afrikaans |
| ar | Arabic |
| bg | Bulgarian |
| bn | Bengali |
| bs | Bosnian |
| ca | Catalan |
| cs | Czech |
| cy | Welsh |
| da | Danish |
| de | German |
| el | Greek |
| en | English |
| es | Spanish |
| et | Estonian |
| fa | Persian |
| fi | Finnish |
| fil | Filipino |
| fr | French |
| ga | Irish |
| gu | Gujarati |
| he | Hebrew |
| hi | Hindi |
| hr | Croatian |
| hu | Hungarian |
| hy | Armenian |
| id | Indonesian |
| is | Icelandic |
| it | Italian |
| ja | Japanese |
| ka | Georgian |
| kk | Kazakh |
| km | Khmer |
| kn | Kannada |
| ko | Korean |
| lt | Lithuanian |
| lv | Latvian |
| mk | Macedonian |
| ml | Malayalam |
| mn | Mongolian |
| mr | Marathi |
| ms | Malay |
| mt | Maltese |
| nb | Norwegian Bokmal |
| ne | Nepali |
| nl | Dutch |
| nn | Norwegian Nynorsk |
| pa | Punjabi |
| pl | Polish |
| pt | Portuguese |
| ro | Romanian |
| ru | Russian |
| sk | Slovak |
| sl | Slovenian |
| sq | Albanian |
| sr | Serbian |
| sv | Swedish |
| sw | Swahili |
| ta | Tamil |
| te | Telugu |
| th | Thai |
| tr | Turkish |
| uk | Ukrainian |
| ur | Urdu |
| vi | Vietnamese |
| zh | Chinese |

## Common region variants

Use these when the language differs significantly by region.

| Code | Language (Region) |
|---|---|
| en-US | English (United States) |
| en-GB | English (United Kingdom) |
| en-CA | English (Canada) |
| en-AU | English (Australia) |
| es-ES | Spanish (Spain) |
| es-MX | Spanish (Mexico) |
| es-AR | Spanish (Argentina) |
| pt-BR | Portuguese (Brazil) |
| pt-PT | Portuguese (Portugal) |
| fr-FR | French (France) |
| fr-CA | French (Canada) |
| de-DE | German (Germany) |
| de-AT | German (Austria) |
| it-IT | Italian (Italy) |
| nl-NL | Dutch (Netherlands) |
| nl-BE | Dutch (Belgium) |
| ar-SA | Arabic (Saudi Arabia) |
| ar-EG | Arabic (Egypt) |
| zh-CN | Chinese (Mainland China) |
| zh-TW | Chinese (Taiwan) |
| zh-HK | Chinese (Hong Kong) |
| zh-Hans | Chinese (Simplified script) |
| zh-Hant | Chinese (Traditional script) |
| sr-Latn | Serbian (Latin script) |
| sr-Cyrl | Serbian (Cyrillic script) |

## Quick recommendation

- Start with language-only (`es.json`, `fr.json`) unless your translation is region-specific.
- Use region/script variants if wording differs a lot or if users expect a specific locale.
