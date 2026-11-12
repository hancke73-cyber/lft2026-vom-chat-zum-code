# CLAUDE.md – Vokabeltrainer

> Diese Datei liegt im Hauptordner des Projekts. Claude Code lädt sie bei **jeder** Sitzung automatisch.
> Sie ist das Gedächtnis des Projekts: kurz, klar, nur das, was Claude wirklich wissen muss.

## Projekt
Eine kleine Lern-App (eine HTML-Datei, läuft offline im Browser) zum Üben von Vokabeln aus einer eigenen Wortliste
(Englisch, Klasse 6, Haupt-/Realschule Hessen). Zielgruppe: Schülerinnen und Schüler, Niveau A1/A2.

## Ordnerstruktur
- `daten/vokabeln.json` – die Vokabeln (Felder: unit, p, en, de)
- `app/vokabeltrainer.html` – die App (HTML, CSS und JavaScript in einer Datei)
- `spezifikation/` – Spezifikationen je Funktion (Level 3)
- `.claude/skills/`, `.claude/rules/`, `.claude/agents/` – wiederverwendbare Bausteine (Level 4/5)

## Pädagogische Haltung (verbindlich)
- Fehler werden **ermutigend erklärt, nicht bloßgestellt** („Fast! Richtig ist: …", nie „Falsch!").
- Kurze Sätze, einfache Wörter, Niveau A1/A2. Anweisungen in der App auf Deutsch.
- Immer ein sichtbarer Fortschritt (z. B. Fortschrittsbalken), kein Zeitdruck als Standard.

## Technische Regeln
- Keine externen Bibliotheken, kein Internet nötig. Alles in einer Datei.
- Keine personenbezogenen Daten. Fortschritt nur lokal im Browser speichern (localStorage).
- Große, gut lesbare Schrift (mind. 18 px), hoher Kontrast, bedienbar mit Tastatur und Touch.
- Bestehende Funktionen nicht verändern, wenn die Aufgabe sie nicht betrifft.

## Arbeitsweise
- Bei größeren Änderungen zuerst einen **Plan** vorlegen und auf Freigabe warten.
- Nach jeder Änderung die App kurz selbst testen und sagen, was geprüft wurde.
- Unsicher? Nachfragen, nicht raten.

## Fertig heißt
Die Akzeptanzkriterien in `spezifikation/` sind erfüllt und von der Lehrkraft geprüft.
