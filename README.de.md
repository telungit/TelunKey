# TelunKey
[简体中文](./README.md) | [繁體中文](./README.zh-Hant.md) | [English](./README.en.md) | [日本語](./README.ja.md) | [한국어](./README.ko.md) | [Español](./README.es.md) | [Português](./README.pt.md) | [हिन्दी](./README.hi.md) | [Русский](./README.ru.md) | [Français](./README.fr.md) | [Deutsch](./README.de.md) | [العربية](./README.ar.md)

TelunKey ist ein nativer macOS-Shortcut-Launcher, mit dem App-Aktivierung und Fensterauswahl in einer Tastenfolge erledigt werden.

- Entwickelt mit nativem Swift für schnelle Reaktion, geringen Overhead und minimale Unterbrechung
- Unterstützt linken/rechten Command (0 Verzögerung oder benutzerdefiniert), linken/rechten Option (0 Verzögerung oder benutzerdefiniert) sowie Space-Trigger (mindestens 0,2 Sekunden Verzögerung, damit normales Tippen nicht beeinträchtigt wird)
- Optimiert für hochfrequente Workflows und flüssigeres Umschalten zwischen Fenstern
- Local-first Design, ohne standardmäßige Abhängigkeit von Cloud-Verhaltensanalysen

## Website

- Zeabur-Homepage: https://telunkey.zeabur.app

> [!IMPORTANT]
> Wenn Sie dauerhaft keinen Zugriff auf Zeabur haben, gibt es für Sie vermutlich keinen passenden Anwendungsfall für TelunKey. Wenn Sie jedoch das Know-how und die Geduld mitbringen, Netzwerkprobleme zu lösen, sollten Sie TelunKey unbedingt ausprobieren – ich bin überzeugt, dass es Ihre Effizienz spürbar steigern wird.

## UI-Vorschau

https://github.com/user-attachments/assets/bf6afeee-3813-410c-87db-9696f364cea7

<img alt="Trigger-Hinweis" src="./images/datishi.png?v=20260329" width="100%" />
<img alt="Chrome-Szenario" src="./images/chrome.png?v=20260329" width="100%" />
<img alt="Einstellungsfenster" src="./images/shezhi.png?v=20260329" width="100%" />

## Systemanforderungen

- macOS 14.0 oder höher

## Installation

Benutzer mit installiertem [Homebrew](https://brew.sh/) können folgenden Befehl ausführen:

```bash
brew update
brew install --cask telungit/tap/telunkey
```

Öffnen Sie TelunKey nach der Installation über „Programme“.

## Aktualisierung

```bash
brew update
brew upgrade --cask --greedy telungit/tap/telunkey
```

Sie können Updates auch direkt in der App suchen.

## Berechtigungen

Für die volle Funktionalität benötigt TelunKey die folgenden Berechtigungen:

- Bedienungshilfen: globale Tastaturereignisse erfassen
- Bildschirmaufzeichnung: Fenster-Miniaturansichten generieren

## Datenschutz

TelunKey verfolgt eine Local-First-Strategie. Kerndaten bleiben auf Ihrem Computer.

## Rückmeldung

- Telegram: https://t.me/telungram
