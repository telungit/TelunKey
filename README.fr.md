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
> Si vous ne parvenez pas du tout à accéder à Zeabur, vous n'aurez probablement pas d'usage pour TelunKey. Mais si vous avez la capacité et la patience de surmonter ces contraintes réseau, essayez absolument TelunKey : je suis convaincu qu'il améliorera considérablement votre productivité.

## Aperçu de l'interface utilisateur

https://github.com/user-attachments/assets/bf6afeee-3813-410c-87db-9696f364cea7

<img alt="Indice de déclenchement" src="./images/datishi.png?v=20260329" width="100%" />
<img alt="Scénario Chrome" src="./images/chrome.png?v=20260329" width="100%" />
<img alt="Écran des réglages" src="./images/shezhi.png?v=20260329" width="100%" />

## Configuration système requise

- macOS 14.0 ou version ultérieure

## Installation

Les utilisateurs ayant installé [Homebrew](https://brew.sh/) peuvent exécuter :

```bash
brew update
brew install --cask telungit/tap/telunkey
```

Après l'installation, ouvrez TelunKey depuis « Applications ».

## Mise à jour

```bash
brew update
brew upgrade --cask --greedy telungit/tap/telunkey
```

Vous pouvez également vérifier les mises à jour directement depuis l'application.

## Autorisations

TelunKey nécessite les autorisations suivantes pour bénéficier de toutes les fonctionnalités :

- Accessibilité : écouter les événements globaux du clavier
- Enregistrement d'écran : générer des vignettes de fenêtre

## Confidentialité

TelunKey suit une stratégie local-first. Les données essentielles restent sur votre machine.

## Retours

- Telegram : https://t.me/telungram
