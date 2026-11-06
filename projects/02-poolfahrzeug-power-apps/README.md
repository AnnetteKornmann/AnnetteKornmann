

```markdown
# Poolfahrzeug-Buchung mit Power Apps

**Bereich:** Low-Code-Entwicklung · Power Apps · SharePoint
**Organisation:** [[MDBM]]

## Ausgangslage

Die firmeneigenen Poolfahrzeuge wurden vorher über [[eine Excel-Liste / telefonische Absprachen]] gebucht. Die Folge: niemand wusste zuverlässig, welches Fahrzeug wann frei ist, Doppelbuchungen waren an der Tagesordnung, und die Pflege der Übersicht lag bei einer einzelnen Person. Ein klassischer Fall für eine einfache, digitale Lösung – ohne teure Individualentwicklung.

## Meine Rolle

Ich habe die Anforderungen aus dem Alltag gesammelt (Wer bucht? Wie? Welche Infos braucht die Verwaltung?), die App mit **Power Apps** konzipiert und umgesetzt und sie im Team eingeführt – inklusive kurzer Einführung für die Nutzerinnen und Nutzer.

## Lösung

Eine Canvas-App als zentrale Buchungsplattform für alle Poolfahrzeuge:

1. **Übersicht:** Auf einen Blick sichtbar, welches Fahrzeug in welchem Zeitraum frei oder belegt ist
2. **Buchung:** Start, Ende und Zweck in einer einfachen Maske – wenige Sekunden pro Buchung
3. **Datenbasis:** SharePoint-Liste im Hintergrund – [[bitte prüfen/ergänzen, ob das stimmt]]
4. **Verlässlichkeit:** Doppelbuchungen werden durch die Zeitlogik [[bzw. durch Validierung]] ausgeschlossen

```mermaid
flowchart LR
    A[Mitarbeiter öffnet App] --> B[Freie Fahrzeuge &amp; Zeiträume sehen]
    B --> C[Buchung mit Zeitraum &amp; Zweck]
    C --> D[SharePoint-Liste: zentrale Datenbasis]

Ergebnis





Doppelbuchungen praktisch ausgeschlossen, [[wenn möglich mit Zahl, z. B. „von X Vorfällen pro Monat auf 0"]]



Buchung dauert [[wenige Sekunden statt bisher ca. X Minuten mit Rückfragen]]



Entlastung der Verwaltung: keine manuelle Pflege einer zentralen Liste mehr



Das Team hat eine Lösung im Werkzeugkasten gesehen, die es vorher für „Programmierer-Sachen" hielt – Low-Code demystifiziert

Lessons Learned





Low-Code ist ein Türöffner: Ich habe gemerkt, dass Automatisierung keine IT-Abteilung braucht – sondern jemanden, der den Prozess versteht



Einfach gewinnt: Die App wird genutzt, weil sie mit drei Klicks funktioniert



Datenpflege zählt: Eine saubere, zentrale Datenbasis (SharePoint) ist das Fundament jeder weiteren Automatisierung

Screenshots

Anonymisierte Screenshots folgen.
