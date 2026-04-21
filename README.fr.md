# TelunKey
[简体中文](./README.md) | [繁體中文](./README.zh-Hant.md) | [English](./README.en.md) | [日本語](./README.ja.md) | [한국어](./README.ko.md) | [Español](./README.es.md) | [Português](./README.pt.md) | [हिन्दी](./README.hi.md) | [Русский](./README.ru.md) | [Français](./README.fr.md) | [Deutsch](./README.de.md) | [العربية](./README.ar.md)

TelunKey est un lanceur de raccourcis natif pour macOS qui réunit l’activation d’apps et la sélection de fenêtres dans une seule séquence de touches.

- Construit en Swift natif pour une réponse rapide, une faible consommation et une interruption minimale
- Prend en charge Command gauche/droite (délai nul ou personnalisé), Option gauche/droite (délai nul ou personnalisé) et le déclenchement avec Space (minimum 0,2 s pour ne pas perturber la saisie quotidienne)
- Optimisé pour les flux de travail à haute fréquence et un changement de fenêtre plus fluide
- Conçu en local-first, sans dépendance par défaut à l’analyse comportementale dans le cloud

## Site web

- Page d'accueil de Zeabur : https://telunkey.zeabur.app

> [!IMPORTANT]
> Si vous ne pouvez pas du tout accéder à Zeabur, TelunKey peut ne pas convenir à votre environnement actuel. Si vous parvenez à résoudre les problèmes de réseau de votre côté, TelunKey vaut la peine d'être essayé et peut améliorer votre efficacité.

## Aperçu de l'interface utilisateur

https://github.com/user-attachments/assets/bf6afeee-3813-410c-87db-9696f364cea7

<img alt="Indice de déclenchement" src="./images/datishi.png?v=20260329" width="100%" />
<img alt="Scénario Chrome" src="./images/chrome.png?v=20260329" width="100%" />
<img alt="Écran des réglages" src="./images/shezhi.png?v=20260329" width="100%" />

## Configuration système requise

- macOS 14.0 ou version ultérieure

## Télécharger

- Dernière version (DMG) : https://github.com/telungit/TelunKey/releases/latest/download/TelunKey.dmg
- Toutes les versions : https://github.com/telungit/TelunKey/releases

## Installation

1. Téléchargez et ouvrez « TelunKey.dmg »
2. Faites glisser « TelunKey.app » dans les applications
3. N’ouvrez pas encore l’app. Double-cliquez d’abord sur `2. Run Once After Install.command` dans le DMG
4. Une fois la réparation terminée, ouvrez TelunKey
5. Exécutez la commande suivante manuellement dans Terminal uniquement si le script échoue

```bash
xattr -dr com.apple.quarantine /Applications/TelunKey.app
```

## Autorisations

TelunKey nécessite les autorisations suivantes pour bénéficier de toutes les fonctionnalités :

- Accessibilité : écouter les événements globaux du clavier
- Enregistrement d'écran : générer des vignettes de fenêtre

## Confidentialité

TelunKey suit une stratégie local-first. Les données essentielles restent sur votre machine.

## Retours

- Telegram : https://t.me/telungram
