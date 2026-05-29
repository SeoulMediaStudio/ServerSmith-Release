<p align="center">
  <img src="assets/serversmith_logo.svg" alt="ServerSmith — Forge your server in one click." width="560">
</p>

<p align="center"><a href="README.md">English</a> · <strong>Deutsch</strong></p>

Discord: https://discord.gg/sd5MurR2fu

ServerSmith ist eine Windows-Desktop-App, mit der <em>jede*r</em> einen vollständig
konfigurierten Discord-Server gestalten und erstellen kann — Rollen, Kategorien,
Kanäle, Berechtigungen, Foren und Onboarding — auf Knopfdruck. Kein Terminal, keine
PowerShell, kein Bearbeiten von Code. Die App bringt wiederverwendbare Vorlagen mit,
speichert alles lokal und führt auch technisch unerfahrene Nutzer mit einer
integrierten Hilfe durch.

---

## Download

**[Neueste Version herunterladen »](https://github.com/SeoulMediaStudio/ServerSmith-Release/releases/latest)**

Lade `ServerSmith-Setup-<version>.exe` aus der neuesten Version herunter und führe
sie aus.

## Funktionen

- **Visuelle Editoren** — gestalte Rollen (Farben, separat anzeigen,
  erwähnbar, Berechtigungen), Kategorien und Kanäle (Text, Sprache, Bühne, Forum)
  mit Kanal-Themen, Slow-Mode, Berechtigungs-Overrides, Forum-Tags und Startbeiträgen.
- **Fertige Vorlagen** — sechs eingebaute Startpunkte (Freunde/Hangout,
  Hobby/Club, Community, Gaming, Creator/Streamer, Dev-Studio/Produkt) sowie eigene.
  Setups lassen sich importieren und exportieren, um sie zu teilen.
- **Vorschau vor dem Erstellen** — ein Testlauf zeigt genau, was erstellt oder
  geändert wird, bevor irgendetwas an deinem Server passiert.
- **Live-Protokoll** — verfolge den Fortschritt in Echtzeit mit klaren,
  verständlichen Meldungen und einem „Log kopieren"-Button.
- **Standardmäßig sicher** — Builds aktualisieren nur und löschen nie etwas; die
  Lösch-Option ist hinter einer klaren doppelten Bestätigung verborgen.
- **Discord Community optional** — vollständige Builds funktionieren auch ohne;
  Community-exklusive Funktionen (Bühnenkanäle, Onboarding, Ankündigungskanäle)
  sind klar gekennzeichnet und werden sauber übersprungen, wenn Community aus ist.
- **Sicher** — dein Bot-Token liegt im Windows-Anmeldeinformationsmanager, nie im
  Klartext und nie in der Datenbank der App.
- **Bleibt aktuell** — prüft beim Start auf neue Versionen und installiert sie mit
  einem Klick (deine Vorlagen und Einstellungen bleiben erhalten).
- **Englisch & Deutsch** — die Sprache lässt sich jederzeit umschalten.

## Systemvoraussetzungen

- Windows 10 oder 11 (64-Bit)
- Ein Discord-Konto und ein Bot-Token (die App leitet dich durch die Erstellung)

## Installation

1. Lade `ServerSmith-Setup-<version>.exe` aus der
   [neuesten Version](https://github.com/SeoulMediaStudio/ServerSmith-Release/releases/latest)
   herunter.
2. Führe den Installer aus. Die Installation erfolgt pro Benutzer — es werden keine
   Administratorrechte benötigt.
3. Starte **ServerSmith** und folge der Ersteinrichtung, um deinen Bot zu verbinden
   und deinen Server auszuwählen.

> **Hinweis:** Da der Installer aus dem Internet geladen wird, kann Windows
> SmartScreen beim ersten Start eine Meldung anzeigen. Wähle **Weitere Informationen
> → Trotzdem ausführen**, um fortzufahren.

## Updates

ServerSmith prüft beim Start automatisch auf Updates. Ist eine neue Version
verfügbar, siehst du, was neu ist, und kannst sie mit einem Klick installieren —
deine gespeicherten Vorlagen, Profile und Einstellungen bleiben erhalten. Die
automatische Prüfung kannst du unter **Hilfe → Beim Start auf Updates prüfen**
abschalten oder jederzeit manuell über **Hilfe → Auf Updates prüfen…** auslösen.

## Download überprüfen (optional)

Jede Version enthält eine `SHA256SUMS`-Datei. Um zu bestätigen, dass dein Download
unverändert ist, führe in PowerShell aus:

```powershell
(Get-FileHash -Algorithm SHA256 .\ServerSmith-Setup-<version>.exe).Hash
```

und vergleiche das Ergebnis (Groß-/Kleinschreibung egal) mit der passenden Zeile in
`SHA256SUMS`.

## Erste Schritte

Nach der Installation öffnest du ServerSmith, und die integrierte Anleitung führt
dich durch:

1. Einen Bot erstellen und sein Token einfügen (sicher auf deinem PC gespeichert).
2. Den Bot auf einen von dir erstellten, leeren Server einladen.
3. Eine Vorlage wählen (oder eine eigene erstellen), eine Vorschau ansehen und auf
   **Erstellen** klicken.

Der **Hilfe**-Tab in der App erklärt alles im Detail.

## Support

Fragen, Feedback oder Probleme? Schreib an **info@seoulmediastudio.com** oder
erstelle ein Issue in diesem Repository.

## Lizenz

Copyright © 2026 **Seoul Media Studio**. Alle Rechte vorbehalten. Siehe
[`LICENSE.txt`](LICENSE.txt).
