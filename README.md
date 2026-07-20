# Heldenpfade

[![Regelwerk bauen](https://github.com/mtilsner/heldenpfade/actions/workflows/build-regelwerk.yml/badge.svg)](https://github.com/mtilsner/heldenpfade/actions/workflows/build-regelwerk.yml)
[![Letztes Release](https://img.shields.io/github/v/release/mtilsner/heldenpfade)](https://github.com/mtilsner/heldenpfade/releases/latest)

**Heldenpfade** ist ein Fantasy-Pen-&-Paper-Rollenspiel mit einem leicht zugänglichen Regelsystem, taktischen Kämpfen und einem starken Fokus auf gemeinsames Erzählen.

Das Projekt befindet sich in aktiver Entwicklung. Ziel ist ein vollständiges Regelwerk, das sowohl für Einsteiger als auch für erfahrene Rollenspieler geeignet ist.

## Aktuelles Regelwerk

Das aktuelle Regelwerk kann direkt im Browser geöffnet werden:

**[Heldenpfade-Regelwerk als PDF öffnen](https://mtilsner.github.io/heldenpfade/Heldenpfade-Regelwerk.pdf)**

Dauerhaft archivierte Fassungen stehen unter [GitHub Releases](https://github.com/mtilsner/heldenpfade/releases) bereit. Die PDF wird automatisch aus den LaTeX-Quellen erzeugt und nicht im Repository versioniert.

Für jeden Pull Request mit Änderungen am Regelwerk wird eine eigene PDF-Vorschau gebaut. Den zugehörigen Link hinterlegt GitHub Actions automatisch im Pull Request.

## Projektstatus

Heldenpfade befindet sich in aktiver Entwicklung. Regeln, Inhalte und Layout werden kontinuierlich erweitert, getestet und überarbeitet.

## Das Spiel

In Heldenpfade übernimmt ein Spieler die Rolle der Spielleitung und führt die Gruppe durch ein Abenteuer. Alle anderen Spieler verkörpern ihre eigenen Helden und entscheiden selbst, wie diese handeln.

Gemeinsam erkundet ihr geheimnisvolle Orte, löst Rätsel, kämpft gegen gefährliche Gegner und erzählt eure eigene Geschichte. Das Ziel ist nicht, gegeneinander zu gewinnen, sondern gemeinsam spannende Abenteuer zu erleben.

## Schwerpunkte

- Einfach verständliche Regeln
- Taktische Kämpfe mit bedeutungsvollen Entscheidungen
- Gemeinsames Erzählen statt Wettbewerb
- Modulares Regelsystem
- Langfristige Charakterentwicklung

## Versionierung

Veröffentlichte Fassungen folgen dem Schema `MAJOR.MINOR.PATCH`.

- Jeder Merge nach `main` erhöht automatisch die Patch-Version und erstellt ein GitHub Release.
- Neue Major- oder Minor-Reihen werden bewusst über ein manuell veröffentlichtes GitHub Release begonnen.
- Pull-Request-Vorschauen tragen die nächste Patch-Version und die PR-Nummer, beispielsweise `0.0.2-PR14`.

Die veröffentlichte PDF zeigt ihre Versionsnummer und das Veröffentlichungsdatum unten auf der Titelseite.

## Repository-Struktur

```text
Regelwerk/
├── chapters/       # Kapitel des Regelwerks
├── appendices/     # Anhänge und Nachschlagewerke
├── assets/         # Bilder, Symbole und weitere Gestaltungselemente
├── build/          # Lokale Build-Ausgabe; wird nicht versioniert
└── main.tex        # Einstiegspunkt des Regelwerks
```

## Entwicklung

Das Regelwerk wird vollständig in **LaTeX** geschrieben.

GitHub Actions übernimmt:

- PDF-Vorschauen für Pull Requests,
- die automatische Patch-Versionierung nach Merges,
- die Veröffentlichung der aktuellen PDF über GitHub Pages,
- und die Archivierung veröffentlichter Versionen über GitHub Releases.

## Lizenz

Die Lizenz wird zu einem späteren Zeitpunkt ergänzt.
