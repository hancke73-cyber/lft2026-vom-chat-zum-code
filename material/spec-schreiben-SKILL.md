---
name: spec-schreiben
description: Interviewt die Lehrkraft zu einer neuen Funktion der Lern-App und schreibt daraus eine Spezifikation mit Zielen, Akzeptanzkriterien und Fehlerfällen. Verwenden, bevor eine neue Funktion gebaut wird (z. B. "Quiz-Modus", "Fortschritt", "Lernstufen").
---
# Spezifikation schreiben

Du hilfst einer Lehrkraft (keine Programmierkenntnisse), eine Funktion der Lern-App **vor** dem Bauen genau zu beschreiben.

## Ablauf
1. Frage nach dem Wunsch der Lehrkraft in einem Satz.
2. Stelle **höchstens fünf** Rückfragen, jeweils eine auf einmal, in einfacher Sprache:
   - Wer nutzt die Funktion, in welcher Unterrichtssituation?
   - Was soll die Funktion können? Was ausdrücklich nicht?
   - Woran erkenne ich, dass sie fertig und richtig ist?
   - Was kann schiefgehen (leere Eingabe, Tippfehler, Umlaute, Groß-/Kleinschreibung)?
   - Welche Haltung gilt (ermutigende Rückmeldung, Niveau A1/A2)?
3. Schreibe die Datei `spezifikation/<funktionsname>.md` mit genau diesen Abschnitten:
   - **Ziel** (ein Satz)
   - **Nutzergeschichte** („Als Schüler/in möchte ich …, damit …")
   - **Funktionen** (nummerierte Liste)
   - **Akzeptanzkriterien** (messbare Aussagen, jede mit „Gegeben … Wenn … Dann …")
   - **Fehlerfälle** (Situation → gewünschtes Verhalten)
   - **Nicht Teil dieser Funktion**
4. Zeige die Spezifikation der Lehrkraft und frage: „Fehlt etwas? Ist etwas falsch?" Erst nach Freigabe ist sie gültig.
