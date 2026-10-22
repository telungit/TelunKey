<div align="center">

<img src="./images/icon.png" width="112" alt="TelunKey-Symbol" />

# TelunKey

**Fensterwechsel für macOS · Tastatur und Trackpad**

Auslösetaste halten und ein bis drei Tasten tippen, um jede App und jedes Fenster zu erreichen. Mit einer Wischgeste auf dem Trackpad platzieren.

[![Neueste Version](https://img.shields.io/github/v/release/telungit/TelunKey?label=release)](https://github.com/telungit/TelunKey/releases/latest)
![macOS 14+](https://img.shields.io/badge/macOS-14%2B-black?logo=apple)

[telunkey.shop](https://www.telunkey.shop)

[Installation](#install) · [Feedback](#feedback)

[简体中文](./README.md) | [繁體中文](./README.zh-Hant.md) | [English](./README.en.md) | [日本語](./README.ja.md) | [한국어](./README.ko.md) | [Español](./README.es.md) | [Português](./README.pt.md) | [हिन्दी](./README.hi.md) | [Русский](./README.ru.md) | [Français](./README.fr.md) | Deutsch | [العربية](./README.ar.md)

</div>

## Direkte Tasten

Halte eine Auslösetaste (linke / rechte Befehlstaste, linke / rechte Wahltaste oder Leertaste) und drücke die ein bis drei Tasten, die einer App zugewiesen sind. Läuft die App nicht, wird sie geöffnet; ein Fenster kommt nach vorn; bei mehreren erscheint die Auswahl. Solange die Auslösetaste gehalten wird, sind alle Zuweisungen sichtbar.

<img src="./images/en/hint.png" width="100%" alt="Hinweismenü mit allen Zuweisungen bei gehaltener Auslösetaste" />

## Tastatur-Auswahl

Die Auswahl ordnet Fensterminiaturen wie die Tastatur an: 1–0, Q–P, A–L, Z–M, mit bis zu 36 Fenstern pro Seite. Die entsprechende Ziffer oder der Buchstabe wählt ein Fenster aus.

- Leertaste: zurück zum zuletzt genutzten Fenster
- Fenster auf anderen Schreibtischen zeigen ihren Schreibtisch
- [ und ] blättern, Esc bricht ab – oder einfach klicken

<img src="./images/en/picker.png" width="100%" alt="Fensterauswahl" />

## Auslösegesten

Halte die Auslösetaste und wische mit den aktivierten ein, zwei oder drei Fingern, um das Fenster unter dem Zeiger halb, geviertelt oder maximiert anzuordnen.

- Hoch, runter, links, rechts: Hälften. Vier Diagonalen: Viertel
- Hoch und wieder runter ohne abzusetzen: maximieren, Menüleiste und Dock bleiben
- In die Abbruchzone wischen bricht ab, zurückwischen wählt neu

<p align="center"><img src="./images/en/gestures.png" width="380" alt="Einstellungen für Auslösegesten" /></p>

## Globale Gesten mit drei und vier Fingern

Ohne Auslösetaste. Drei-Finger-Wisch- und Umkehrgesten sowie Tippen, Doppeltippen und physische Klicks mit drei oder vier Fingern lassen sich mit Tastenkürzeln, Einzeltasten, Mittelklicks oder Fensteraktionen belegen; langes Berühren ist für den Displaywechsel reserviert. Alle Aktionen wirken auf das unter dem Zeiger fixierte Fenster, ergänzt durch einen Übungsmodus zur Vorschau ohne Ausführung.

Bei Konflikten mit systemweiten Drei-Finger-Gesten zum Wischen, Bewegen oder Nachschlagen zeigt TelunKey nur die aktiven Optionen an, öffnet direkt die passende Seite der Systemeinstellungen und prüft bei der Rückkehr automatisch erneut, ohne selbst Systemeinstellungen zu ändern. Bis zur Lösung bleiben Drei-Finger-Wischen und langes Berühren inaktiv, während Tippen und Klicken verfügbar bleiben.

## Gedrückt halten zum Displaywechsel

Links, rechts oder oben? Langes Berühren öffnet eine Karte entsprechend Ihrer macOS-Displayanordnung; gleiten Sie zum gewünschten Display und heben Sie die Finger an, um das Fenster proportional zum nutzbaren Bereich zu verschieben.

- Mit vier Fingern lang berühren, um ein Display zu wählen (normales Vier-Finger-Wischen bleibt bei macOS); nach der Einrichtung funktionieren auch drei Finger oder die gehaltene Auslösetaste mit ein bis drei aktivierten Fingern
- Verschiebt das Fenster auf den aktuell sichtbaren Schreibtisch des Zieldisplays; Vollbildfenster und Displays mit einer Vollbild-App sind ausgeschlossen
- Vor dem Bestätigen jederzeit zurückgleiten; Anheben auf dem Quelldisplay oder im Leerraum, vorzeitiges Loslassen der Auslösetaste oder Esc bricht ab

## Betrieb und Einstellungen

TelunKey ist in Swift geschrieben, hat keine Abhängigkeiten von Drittanbietern und läuft in der Menüleiste. Einstellungen bleiben auf deinem Mac und lassen sich importieren und exportieren; die Oberfläche gibt es in 12 Sprachen.

https://github.com/user-attachments/assets/bf6afeee-3813-410c-87db-9696f364cea7

<a id="install"></a>

## Loslegen

Benötigt macOS 14 oder neuer sowie [Homebrew](https://brew.sh/):

```bash
brew install --cask telungit/tap/telunkey
```

Beim ersten Start führt dich ein Einrichtungsassistent durch Berechtigungen, Auslösetasten, Kürzel und Gesten. Aktualisieren kannst du direkt in der App oder mit:

```bash
brew upgrade --cask --greedy telungit/tap/telunkey
```

## Berechtigungen

| Berechtigung | Wofür |
| --- | --- |
| Bedienungshilfen (erforderlich) | Auslösetasten und Gesten erkennen; Fenster wechseln und anordnen |
| Bildschirmaufnahme (optional) | Fenster-Miniaturen; ohne sie werden App-Symbole angezeigt, das Wechseln funktioniert weiterhin |

<a id="feedback"></a>

## Feedback

- [GitHub Issues](https://github.com/telungit/TelunKey/issues)
- [Telegram](https://t.me/telungram)
