# successive-relearning

Ein Lern-Skill für Claude (und andere Agenten mit SKILL.md-Unterstützung), der auf der Methode **Successive Relearning** basiert: Abrufübung (Retrieval Practice) bis zu einem Kriterium, verteilt über mehrere Tage (Spaced Practice).

Die Lernforschung bewertet genau diese beiden Techniken am höchsten (Dunlosky et al. 2013). Ergänzt wird das durch Elaboration bzw. Selbsterklärung (Ursache-Wirkungs-Ketten), konkrete Beispiele, Dual Coding (Text + Diagramm) und Interleaving (gemischte Aufgaben).

## Was der Skill macht

| Modus | Wofür |
|---|---|
| Build | Skript oder Notizen in einen Lernleitfaden mit verborgenen Antworten umwandeln |
| Coach | Abfrage, eine Frage nach der anderen, mit Korrektur |
| Relearn | Wiederholungssitzung bis zum Kriterium |
| Plan | Lernplan bis zur Prüfung |
| Teach-back | Thema ohne Notizen erklären, Lücken finden |
| Diagnose | Gemischter Test zum Finden der Schwachstellen |

## Installation

Ordner `successive-relearning/` in das Skills-Verzeichnis kopieren (z. B. `~/.claude/skills/`) oder in claude.ai als Skill hochladen.

## Quellen

Siehe [`references/evidence.md`](references/evidence.md).

## Herkunft und Lizenz

Abgeleitet von [learn-anything-fast](https://github.com/zgl610329-wq/learn-anything-fast) (MIT, © 2026 zgl&hxr). Erweiterungen: Successive Relearning mit Abrufkriterium, Spacing-Plan, Interleaving, Wirkungsketten, Dual Coding, Format für Lernleitfäden. MIT-Lizenz, siehe `LICENSE` und `LICENSE.upstream`.
