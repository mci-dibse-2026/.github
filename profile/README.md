<div align="center">

# DIBSE 2026

**Digital Business & Software Engineering · MCI Innsbruck**

Gemeinsamer Arbeitsbereich für Übungen, Hausarbeiten und Projekte unseres Jahrgangs.

</div>

---

### Grundregel

**Ein Repository pro Abgabe** — privat bis zur Benotung, danach optional öffentlich.

### Namensschema

`<lv-kuerzel>-<thema>[-<gruppe>]` — klein, Bindestriche, keine Umlaute.

```
swe1-designpatterns-gruppe03
ml-seminararbeit-anomaly-detection
dbs-uebung02-normalisierung
```

### Repo-Struktur

```
README.md     Ziel, Team, Setup, Ausführung
docs/         Ausarbeitung, Diagramme, Quellen
src/          Quellcode
tests/        Tests
```

### Workflow

Auf `main` wird nicht direkt gearbeitet: Branch → Commit → Pull Request → Review → Merge.
`main` ist damit jederzeit abgabefähig.

```bash
git switch -c feat/kapitel-3-methodik
git commit -m "feat(docs): Kapitel 3 Methodik ergaenzt"
git push -u origin feat/kapitel-3-methodik
```

Commit-Format nach [Conventional Commits](https://www.conventionalcommits.org/de/).

### Nicht committen

Zugangsdaten und `.env` · personenbezogene Daten · fremde Skripten und Vorlesungsunterlagen ·
generierte Ordner (`node_modules/`, `venv/`, `dist/`) · große Datensätze
→ [.gitignore-Vorlagen](https://github.com/github/gitignore)

> [!CAUTION]
> Ein einmal gepushtes Secret gilt als kompromittiert — auch nach dem Löschen des Commits.
> Keys und Tokens danach rotieren.

### Wissenschaftliche Praxis

Öffentliche Repos sind Referenz, keine Vorlage. Übernommenen Code kennzeichnen, Quellen zitieren,
KI-Einsatz so offenlegen, wie es die Lehrveranstaltung vorgibt. Maßgeblich sind immer die Vorgaben
der Lehrenden und die Prüfungsordnung des MCI.

---

<div align="center">

<sub>Zugang: Nachricht mit GitHub-Benutzernamen an ein Org-Mitglied · Fragen und Vorschläge → <a href="https://github.com/mci-dibse-2026/.github/issues">Issues</a></sub>

<sub>Studentische Initiative des Jahrgangs DIBSE 2026 — kein offizieller Auftritt des MCI Management Center Innsbruck.</sub>

</div>
