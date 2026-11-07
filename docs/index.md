# Azure Dynamic Groups: Access Governance Concept

| | |
| :--- | :--- |
| Titel der Semesterarbeit | Azure Dynamic Groups: Access Governance Concept |
| Name | Dodoe Rumiñahui Mannale |
| Studiengang | Dipl. Informatiker/in HF, ITCNE25, TBZ |
| Semester | Semester 1 |
| Themenfelder | Azure, Microsoft 365, PowerShell, Automatisierung, Access Governance |

Diese Seite ist die Dokumentation meiner 1. Semesterarbeit.

## Worum geht es?

In einer hybriden Azure-Umgebung wurden Berechtigungen und Mailverteiler bisher grösstenteils von Hand gepflegt. Das führt zu uneinheitlichen Zugriffsrechten, doppelten Gruppen und Compliance-Risiken. In dieser Arbeit habe ich ein Konzept und einen Proof of Concept erarbeitet, das Berechtigungen automatisch über dynamische Gruppen vergibt. Grundlage ist eine zentrale Abteilungsliste mit Abteilungscodes, die PowerShell-Runbooks in Azure Automation und eine Logic App auswerten.

## Ziele

| Ziel | Kurz |
| --- | --- |
| Automatisierte Berechtigungsverwaltung | Dynamische Gruppen vergeben Berechtigungen anhand des Abteilungscodes (z.B. SharePoint, Intune, Mailverteiler) |
| Prozesse für Änderungen | Klare Abläufe für neue Abteilungen, Rollen und Mailverteiler |
| Pilotphase | Test des Konzepts mit einer Abteilung |

Details in der [Einleitung](documents/01_Einleitung/index.md).

## Aufbau dieser Dokumentation

| Bereich | Inhalt |
| --- | --- |
| [Einleitung](documents/01_Einleitung/index.md) | Ausgangslage, Anforderungen, Ziele, Abgrenzung |
| [Projektplanung](documents/02_Projektplanung/index.md) | Konzept und Architektur, Projektplan, Risikomanagement |
| [Projektdurchführung](documents/03_Projektdurchfuehrung/index.md) | Environment Setup, Produkte und Skripte, Herausforderungen, Sprint Reviews |
| [Ergebnisse](documents/04_Ergebnisse/index.md) | Ergebnisse und Bewertung der Zielerreichung |
| [Fazit](documents/05_Fazit/index.md) | Fazit und Ausblick |
| [Anhänge](documents/06_Anhaenge/index.md) | Skripte und Glossar |

## Hinweis zur Veröffentlichung

Die Arbeit entstand in einer realen Arbeitsumgebung. Für diese öffentliche Fassung sind Namen von Organisation, Tenant, Domains und Azure-Ressourcen durch Platzhalter ersetzt (z.B. `contoso`, `stpowerbisync`). Screenshots mit internen Ressourcen-IDs sind nicht enthalten. Inhalt und Aufbau der Arbeit sind sonst unverändert.

Teil meines Portfolios: [ruminahuim.github.io](https://ruminahuim.github.io/)
