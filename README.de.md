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

Ohne Auslösetaste. Drei-Finger-Wisch- und Umkehrgesten sowie Tippen, Doppeltippen und physische Klicks mit drei oder vier Fingern lassen sich mit Tastenkürzeln, Einzeltasten, Mittelklicks oder Fensteraktionen belegen. Langes Berühren ist für den Displaywechsel reserviert. Aktionen verwenden das unter dem Zeiger fixierte Fenster.

Bei Neuinstallationen aktiviert; Updates behalten bestehende Einstellungen. Langes Berühren ist für Bildschirmwechsel reserviert, andere Gesten sind frei belegbar. Die Übung zeigt eine Vorschau ohne Ausführung.

Deaktiviere vor Dreifinger-Wischgesten und der Bildschirmauswahl durch langes Berühren das systemweite Bewegen mit drei Fingern. Stelle horizontales und vertikales Wischen auf vier Finger um oder deaktiviere es. TelunKey zeigt nur aktive Konflikte und führt zu Trackpad → Weitere Gesten oder Bedienungshilfen → Zeigersteuerung → Trackpad-Optionen. Bei deiner Rückkehr wird automatisch erneut geprüft; du kannst es auch später einrichten. Bis zur Lösung bleiben Dreifinger-Wischen und langes Berühren inaktiv, Tippen und Klicken bleiben verfügbar. Konflikte mit Nachschlagen werden separat angezeigt. TelunKey ändert keine Systemeinstellungen automatisch.

## Gedrückt halten zum Displaywechsel

Links, rechts oder oben? Langes Berühren öffnet eine Karte Ihrer macOS-Displayanordnung. Zum gewünschten Display gleiten und die Finger anheben, um das Fenster zu verschieben.

- Vier Finger ruhig halten, dann zum Zielbildschirm gleiten. Nach der Einrichtung gehen auch drei Finger oder die gehaltene Auslösetaste mit den aktivierten ein bis drei Fingern
- Nach Displayanordnung wählen; die Fensterposition wird proportional auf die nutzbaren Bereiche übertragen
- Vor dem Bestätigen zurückgleiten; Anheben auf dem Quelldisplay oder im Leerraum bricht ab. Mit Esc kannst du ebenfalls abbrechen.

Normales Vierfinger-Wischen bleibt bei macOS. Halte vier Finger zuerst ruhig auf dem Trackpad. Erst nach Beginn der Bildschirmauswahl übernimmt TelunKey vorübergehend diese Geste. Beim Abheben übernimmt wieder macOS.

Auf den aktuell sichtbaren Schreibtisch eines anderen Displays. Bei nur einem Display gibt es kein Ziel. Vollbildfenster und Displays mit einer Vollbild-App sind ausgeschlossen. Anheben auf dem Quelldisplay, im Leerraum oder auf einem nicht verfügbaren Display bricht ab. Bei Auslösegesten muss die Auslösetaste bis zum Anheben gehalten werden; früheres Loslassen bricht ebenfalls ab.

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
