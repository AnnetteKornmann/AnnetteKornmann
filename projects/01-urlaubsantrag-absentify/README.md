# Urlaubsantragsprozess mit Absentify

**Bereich:** Prozessautomatisierung · Power Automate · SharePoint · Microsoft Teams
**Organisation:** MDBM

## Ausgangslage

Urlaubsanträge liefen vorher manuell: [[z. B. per E-Mail, Papierform, Absprache mit Vorgesetzten]]. Der Prozess war intransparent – niemand hatte auf einen Blick einen Überblick über genehmigte Abwesenheiten, Anträge gingen zwischen Abteilungen verloren, und die Anbindung an Kalender und Urlaubslisten musste per Hand gepflegt werden. Ein früherer Lösungsversuch über eine SharePoint-Liste mit [[Flowmaster / Standard-Workflow]] funktionierte nicht zuverlässig und wurde von den Mitarbeitenden nicht angenommen.

## Meine Rolle

Ich habe den Prozess von Grund auf analysiert und mit **Absentify** neu aufgebaut – von der Tool-Auswahl über die Konfiguration bis zur Einführung im Team. Als Assistentin der Geschäftsleitung war ich dabei gleichzeitig Prozessverantwortliche, Ansprechpartnerin für alle Mitarbeitenden und Schnittstelle zur IT.

## Lösung

Digitale Urlaubsanträge über Absentify in Microsoft Teams:

1. **Antrag** direkt in Teams/Outlook gestellt – inkl. automatischer Resturlaubsanzeige
2. **Genehmigung** durch Führungskraft per Knopfdruck (mobile und am Desktop)
3. **Automatische Integration**: Genehmigungen landen automatisch im Kalender und in der Urlaubsübersicht – ohne manuelle Nachpflege
4. Unterstützend habe ich mit **Power Automate** einen Mini-Workflow gebaut, der bei neuen Einträgen in einer SharePoint-Liste automatisch Benachrichtigungs-E-Mails versendet – als Basis für weitere Automatisierungsideen im Team

```mermaid
flowchart LR
    A[Mitarbeiter: Antrag in Teams] --> B[Führungskraft: Genehmigung per Klick]
    B --> C[Automatisch: Kalender &amp; Urlaubsliste]
    C --> D[Team: transparente Abwesenheitsübersicht]
