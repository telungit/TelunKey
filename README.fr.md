# TelunKey
[简体中文](./README.md) | [繁體中文](./README.zh-Hant.md) | [English](./README.en.md) | [日本語](./README.ja.md) | [한국어](./README.ko.md) | [Español](./README.es.md) | [Português](./README.pt.md) | [हिन्दी](./README.hi.md) | [Русский](./README.ru.md) | [Français](./README.fr.md) | [Deutsch](./README.de.md) | [العربية](./README.ar.md)

TelunKey est un lanceur de raccourcis natif pour macOS qui effectue l'activation de l'application et la sélection des fenêtres en un seul flux de touches.

- Construit avec Swift natif pour une réponse rapide, une faible surcharge et une interruption minimale
- Prend en charge la commande gauche/droite (délai 0 ou délai personnalisé), l'option gauche/droite (délai 0 ou délai personnalisé) et le déclencheur spatial (délai minimum de 0,2 s pour éviter d'affecter la saisie normale)
- Optimisé pour les flux de travail à haute fréquence et un changement de fenêtre plus fluide
- Local d'abord par conception, sans dépendance par défaut sur l'analyse du comportement du cloud

## Site web

- Page d'accueil de Zeabur : https://telunkey.zeabur.app

> [!IMPORTANT]
> Si vous ne pouvez pas du tout accéder à Zeabur, TelunKey peut ne pas convenir à votre environnement actuel. Si vous parvenez à résoudre les problèmes de réseau de votre côté, TelunKey vaut la peine d'être essayé et peut améliorer votre efficacité.

## Aperçu de l'interface utilisateur

https://github.com/user-attachments/assets/bf6afeee-3813-410c-87db-9696f364cea7

![Trigger hint](./images/datishi.png)
![Chrome scenario](./images/chrome.png)
![Settings](./images/shezhi.png)

## Configuration système requise

- macOS 14.0 ou version ultérieure

## Télécharger

- Dernière version (DMG) : https://github.com/telungit/TelunKey/releases/latest/download/TelunKey.dmg
- Toutes les versions : https://github.com/telungit/TelunKey/releases

## Installation

1. Téléchargez et ouvrez « TelunKey.dmg »
2. Faites glisser « TelunKey.app » dans les applications
3. N’ouvrez pas encore l’app. Double-cliquez d’abord sur `一键修复.command` dans le DMG
4. Une fois la réparation terminée, ouvrez TelunKey
5. Exécutez la commande suivante manuellement dans Terminal uniquement si le script échoue

```bash
xattr -dr com.apple.quarantine /Applications/TelunKey.app
```

## Autorisations

TelunKey nécessite les autorisations suivantes pour bénéficier de toutes les fonctionnalités :

- Accessibilité : écoutez les événements mondiaux du clavier
- Enregistrement d'écran : générer des vignettes de fenêtre

## Confidentialité

TelunKey suit une stratégie axée sur le local. Les données de base restent sur votre machine.

## Retour

- Télégramme : https://t.me/telungram
