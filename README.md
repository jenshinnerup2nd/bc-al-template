# [APP NAVN]

Publisher: Vibrant Color Development
BC Version: 26.0.0.0
Prefix: VCD

## Beskrivelse
<!-- Kort beskrivelse af hvad appen gør — udfyldes af Claude -->

## Installation

1. Download `.app` filen fra [Releases](../../releases)
2. Upload i BC: **Udvidelsesstyring → Overfør udvidelse**
3. Se `DOCS.md` for opsætningsvejledning

## Publish til BC (udvikling)

```powershell
# Via VS Code: F5
# Via PowerShell:
Publish-NAVApp -ServerInstance BC -Path *.app -SkipVerification
```

## Struktur

```
src/           AL kode
.github/       AL-Go CI/CD workflows
app.json       App manifest
APP_REQUEST.md Beskriv hvad du ønsker
PROJECT.md     Teknisk spec (udfyldes af Claude)
DOCS.md        Brugerdokumentation (udfyldes af Claude)
```

## Versioner

| Version | Dato | Ændringer |
|---------|------|-----------|
| 1.0.0.0 | | Første version |
