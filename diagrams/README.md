# Diagrams Index

| DIA | File | Type | Visualizes |
|---|---|---|---|
| DIA-001 | `01-system-context.puml` | component/deployment | WF-001…WF-004 — all repos/services/channels |
| DIA-002 | `02-usecases.puml` | use case | UC-001…UC-014 grouped by actor |
| DIA-003 | `03-erd.puml` | ERD | Cases / Messages / Analyses / Solutions / ConfidenceMatches schema |
| DIA-004 | `04-case-status-state.puml` | state machine | Case status lifecycle across WF-001…WF-004 |
| DIA-005 | `05-intake-analysis-seq.puml` | sequence | WF-001 — LINE intake → AI CENTER analysis → Teams notify |
| DIA-006 | `06-techsupport-reply-seq.puml` | sequence | WF-002/WF-003 — Teams reply → solution analysis → LINE reply |
| DIA-007 | `07-confidence-suggestion-seq.puml` | sequence | WF-004 — confidence match → suggestion → confirm/reinforce (Planned) |

## How to view

- VS Code: install the "PlantUML" extension, open any `.puml` file, `Alt+D` to preview.
- CLI: `java -jar plantuml.jar -tsvg diagrams/*.puml` (needs Graphviz + Java).
- `requirement.html` renders all of these inline via the public plantuml.com server — no local setup needed there.
