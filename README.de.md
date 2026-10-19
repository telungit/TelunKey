<div align="center">

<img src="./images/icon.png" width="112" alt="TelunKey-Symbol" />

# TelunKey

**Per Tastatur zu jedem Fenster. Per Geste an seinen Platz.**

Eine Taste halten, ein oder zwei Buchstaben tippen – schon bist du bei jedem Fenster jeder App. Einmal über das Trackpad wischen, und das Fenster sitzt.

[![Neueste Version](https://img.shields.io/github/v/release/telungit/TelunKey?label=release)](https://github.com/telungit/TelunKey/releases/latest)
![macOS 14+](https://img.shields.io/badge/macOS-14%2B-black?logo=apple)

[Website](https://www.telunkey.shop) · [Installation](#install) · [Feedback](#feedback)

[简体中文](./README.md) | [繁體中文](./README.zh-Hant.md) | [English](./README.en.md) | [日本語](./README.ja.md) | [한국어](./README.ko.md) | [Español](./README.es.md) | [Português](./README.pt.md) | [हिन्दी](./README.hi.md) | [Русский](./README.ru.md) | [Français](./README.fr.md) | Deutsch | [العربية](./README.ar.md)

</div>

## Zwei, drei Tasten bis zu jeder App

Halte eine Auslösetaste (linke / rechte Befehlstaste, linke / rechte Wahltaste oder Leertaste) und tippe ein bis drei Buchstaben. Läuft die App nicht, wird sie geöffnet; hat sie ein Fenster, kommt es nach vorn; hat sie mehrere, erscheint eine Auswahl. Solange du die Taste hältst, werden alle Zuweisungen angezeigt – nichts muss auswendig gelernt werden.

<img src="./images/en/hint.png" width="100%" alt="Hinweismenü mit allen Zuweisungen bei gehaltener Auslösetaste" />

## Das richtige Fenster auf einen Blick

Die Auswahl zeigt alle Fenster der App als Miniaturen. Eine Ziffer oder ein Buchstabe wählt ein Fenster, die Leertaste das zuletzt benutzte. Sind die Fenster auf mehrere Schreibtische verteilt, zeigt jede Karte, auf welchem es liegt.

<img src="./images/en/picker.png" width="100%" alt="Fensterauswahl mit Miniaturen" />

## Wischen, und das Fenster sitzt

- **Auslösegesten**: Auslösetaste halten und über das Trackpad wischen, um das Fenster unter dem Zeiger auf eine Hälfte, ein Viertel oder den ganzen Bildschirm zu legen.
- **Globale Gesten**: Wischen, Tippen oder Klicken mit drei Fingern mit Fensteraktionen, Tastenkürzeln oder einzelnen Tasten belegen.
- **Über Bildschirme hinweg**: Eine globale Geste über den Rand hinausziehen, um das Fenster unter Beibehaltung seiner Proportionen auf einen anderen Bildschirm zu verschieben.
- Jede Geste lässt sich neu belegen, und ein Übungsmodus zeigt Aktionen nur in der Vorschau, ohne sie auszuführen.

## Nativ und schlank

Komplett in Swift geschrieben, ohne Abhängigkeiten von Drittanbietern, lebt in der Menüleiste. Einstellungen bleiben auf deinem Mac und lassen sich importieren und exportieren; die Oberfläche gibt es in 12 Sprachen.

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

## Berechtigungen und Datenschutz

| Berechtigung | Wofür |
| --- | --- |
| Bedienungshilfen (erforderlich) | Auslösetasten und Gesten erkennen; Fenster wechseln und anordnen |
| Bildschirmaufnahme (optional) | Fenster-Miniaturen; ohne sie werden App-Symbole angezeigt, das Wechseln funktioniert weiterhin |

Einstellungen werden auf deinem Mac gespeichert, die Lizenzdaten im Schlüsselbund. TelunKey geht nur online, um die Lizenz zu prüfen und nach Updates zu suchen, und sammelt keine Nutzungsdaten.

## Kostenlos und lizenziert

Die kostenlose Version erlaubt bis zu 5 zugewiesene Apps, alle anderen Funktionen sind enthalten. Eine dauerhafte Lizenz über die [Website](https://www.telunkey.shop) hebt die Grenze auf.

<a id="feedback"></a>

## Feedback

- [GitHub Issues](https://github.com/telungit/TelunKey/issues)
- [Telegram](https://t.me/telungram)
