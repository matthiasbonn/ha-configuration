# Home Assistant – Öffentliche Beispielkonfiguration

[![Home Assistant Config Check](https://github.com/matthiasbonn/ha-configuration/actions/workflows/check-config.yml/badge.svg)](https://github.com/matthiasbonn/ha-configuration/actions/workflows/check-config.yml)
[![YAML Lint](https://github.com/matthiasbonn/ha-configuration/actions/workflows/lint-yaml.yml/badge.svg)](https://github.com/matthiasbonn/ha-configuration/actions/workflows/lint-yaml.yml)
[![Prettier](https://github.com/matthiasbonn/ha-configuration/actions/workflows/prettier.yml/badge.svg)](https://github.com/matthiasbonn/ha-configuration/actions/workflows/prettier.yml)
[![Secrets Scan](https://github.com/matthiasbonn/ha-configuration/actions/workflows/secrets-scan.yml/badge.svg)](https://github.com/matthiasbonn/ha-configuration/actions/workflows/secrets-scan.yml)

---

## Übersicht

Dies ist das **öffentliche Read-Only-Repository** für eine reale Home Assistant Konfiguration.  
**Achtung:** Dieses Repository wird **automatisch aus einem privaten, produktiven Repository exportiert**.  
Enthalten sind ausschließlich geprüfte und für die Community freigegebene Konfigurationsdateien – **keine Passwörter,
keine Datenbanken, keine privaten Backups!**

---

## Was ist enthalten?

- Haupt-Konfigurationsdateien (`configuration.yaml`, `automations.yaml`, `scripts.yaml` usw.)
- Modularisierte Konfigurationen in `/packages/` (soweit freigegeben)
- Arbeitskonfigurationen für VSCode (`.vscode/`)
- Beispiel-Snippets, Tasks, Workflows (sofern nicht sicherheitsrelevant)
- **Keine sensiblen Dateien:**
  - Keine `secrets.yaml`, keine Backups/Snapshots, keine `.storage`, keine Datenbanken, keine privaten Custom Components

---

## Qualitätssicherung

Jede Änderung wird automatisch von GitHub Actions geprüft:

- **[Config Check](.github/workflows/check-config.yml):** Gültigkeit der Konfiguration für Home Assistant
- **[YAML Lint](.github/workflows/lint-yaml.yml):** Einrückungen, Style, Fehlerfreiheit der YAML-Dateien
- **[Prettier](.github/workflows/prettier.yml):** Einheitliche Formatierung aller YAML-/JSON-/MD-Dateien
- **[Secrets Scan](.github/workflows/secrets-scan.yml):** Überprüfung auf versehentlich eingecheckte Zugangsdaten

---

## Wie wird dieses Repository gepflegt?

Dieses Repository wird **automatisch** aus dem privaten Produktiv-Repository
[<DEINPRIVATEREPO>](https://github.com/<DEINUSER>/<DEINPRIVATEREPO>) synchronisiert und überschrieben.  
**Pull Requests werden grundsätzlich abgelehnt. Issues können als Feedback genutzt werden, führen aber nicht direkt zu
Änderungen.**

---

## Warum ein öffentliches Repository?

- Als **Beispiel** für professionelle Home Assistant Projektstruktur
- Für den Wissensaustausch und als Vorlage für eigene Konfigurationen
- Als **Demo** für Teams oder Kunden

---

## Sicherheit & Datenschutz

- **Sämtliche sensiblen oder personenbezogenen Daten werden durch den automatisierten Export ausgeschlossen!**
- Die `.gitignore` ist so eingestellt, dass keine geheimen Informationen im Repo landen können.
- Siehe auch den Abschnitt „Was ist enthalten?“.

---

## Lizenz

Dieses Repository dient ausschließlich zu **Demonstrations- und Community-Zwecken**.  
Eigene Nutzung auf eigenes Risiko. Kein Support für die vollständige Übernahme in Produktivsysteme.

---

> Dieses Public Repository ist ein automatisch gepflegter, read-only Export des privaten Repos.  
> Letztes Update: 28.07.2025  
> Maintainer: Matthias Bonn
