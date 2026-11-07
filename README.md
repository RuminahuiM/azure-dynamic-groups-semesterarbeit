# Azure Dynamic Groups: Access Governance Concept

| | |
| :--- | :--- |
| Titel der Semesterarbeit | Azure Dynamic Groups: Access Governance Concept |
| Name | Dodoe Rumiñahui Mannale |
| Studiengang | Dipl. Informatiker/in HF, ITCNE25, TBZ |
| Semester | Semester 1 |

Dieses Repository enthält die Dokumentation meiner 1. Semesterarbeit: Konzept und Proof of Concept für automatische Berechtigungen und Mailverteiler über dynamische Gruppen in Azure.

**Lesen:** <https://ruminahuim.github.io/azure-dynamic-groups-semesterarbeit/>

Teil meines Portfolios: <https://ruminahuim.github.io/>

## Hinweis zur Veröffentlichung

Die Arbeit entstand in einer realen Arbeitsumgebung. In dieser öffentlichen Fassung sind Namen von Organisation, Tenant, Domains, Azure-Ressourcen und beteiligten Personen ersetzt bzw. entfernt. Die PowerShell-Skripte unter `docs/resources/documents/` sind generalisiert (Platzhalter `contoso`, `stpowerbisync`) und nicht direkt lauffähig, ohne die Platzhalter anzupassen. Screenshots mit internen Ressourcen-IDs sind nicht enthalten.

## Aufbau

| Pfad | Inhalt |
| --- | --- |
| `docs/index.md` | Startseite mit Überblick |
| `docs/documents/01_Einleitung/` | Ausgangslage, Anforderungen, Ziele, Abgrenzung |
| `docs/documents/02_Projektplanung/` | Konzept, Projektplan, Risikomanagement |
| `docs/documents/03_Projektdurchfuehrung/` | Environment, Produkte und Skripte, Herausforderungen, Sprint Reviews |
| `docs/documents/04_Ergebnisse/` | Ergebnisse und Zielerreichung |
| `docs/documents/05_Fazit/` | Fazit und Ausblick |
| `docs/documents/06_Anhaenge/` | Skripte und Glossar |
| `docs/resources/` | Bilder und Skripte |

## Lokal ansehen (PowerShell)

```powershell
py -m venv .venv
.\.venv\Scripts\Activate.ps1
pip install -r requirements.txt
mkdocs serve
```

Die Seite wird bei jedem Push auf `main` automatisch mit GitHub Actions gebaut (`mkdocs build --strict`) und auf GitHub Pages veröffentlicht.
