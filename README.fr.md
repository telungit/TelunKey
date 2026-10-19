<div align="center">

<img src="./images/icon.png" width="112" alt="Icône de TelunKey" />

# TelunKey

**Changement de fenêtre pour macOS · Clavier et trackpad**

Maintenez une touche de déclenchement et tapez une à trois touches pour atteindre n'importe quelle app ou fenêtre. Balayez le trackpad pour la placer.

[![Dernière version](https://img.shields.io/github/v/release/telungit/TelunKey?label=release)](https://github.com/telungit/TelunKey/releases/latest)
![macOS 14+](https://img.shields.io/badge/macOS-14%2B-black?logo=apple)

[telunkey.shop](https://www.telunkey.shop)

[Installer](#install) · [Retours](#feedback)

[简体中文](./README.md) | [繁體中文](./README.zh-Hant.md) | [English](./README.en.md) | [日本語](./README.ja.md) | [한국어](./README.ko.md) | [Español](./README.es.md) | [Português](./README.pt.md) | [हिन्दी](./README.hi.md) | [Русский](./README.ru.md) | Français | [Deutsch](./README.de.md) | [العربية](./README.ar.md)

</div>

## Touches directes

Maintenez une touche de déclenchement (Commande gauche / droite, Option gauche / droite ou Espace) et saisissez les touches attribuées à une app (une à trois). Si elle est fermée, elle s’ouvre ; avec une fenêtre, celle-ci passe au premier plan ; avec plusieurs, le sélecteur apparaît. Les attributions restent visibles tant que la touche de déclenchement est maintenue.

<img src="./images/en/hint.png" width="100%" alt="Menu d’aide listant tous les raccourcis pendant que la touche de déclenchement est maintenue" />

## Sélecteur au clavier

Le sélecteur dispose les miniatures dans l’ordre du clavier : 1–0, Q–P, A–L, Z–M, avec jusqu’à 36 fenêtres par page. Appuyez sur le chiffre ou la lettre correspondant à la fenêtre.

- Espace : retour à la dernière fenêtre utilisée
- Les fenêtres d'autres bureaux indiquent leur bureau
- [ et ] changent de page, Échap annule, ou cliquez simplement

<img src="./images/en/picker.png" width="100%" alt="Sélecteur de fenêtres" />

## Gestes de déclenchement

Maintenez la touche de déclenchement et balayez le trackpad à deux doigts pour placer la fenêtre sous le pointeur sur une moitié, un quart de l’écran, ou l’agrandir.

- Haut, bas, gauche, droite : moitiés. Quatre diagonales : quarts
- Haut puis bas sans lever les doigts : agrandir, en gardant la barre des menus et le Dock
- Entrez dans la zone d'annulation pour annuler ; revenez pour choisir à nouveau

### Gestes à trois doigts

Une fois activés, huit directions, allers-retours, toucher, double toucher, toucher long et clic peuvent chacun envoyer un raccourci, une touche seule, un clic central ou une action de fenêtre.

- Désactivés par défaut. En cas de conflit avec un geste système à trois doigts, les réglages l'indiquent et mènent à la solution
- D’un écran à l’autre : poursuivez le geste à trois doigts vers l’extérieur, au-delà de la zone d’annulation, pour déplacer la fenêtre vers un autre écran en conservant ses proportions.
- Chaque geste peut être réattribué, et un mode d’entraînement prévisualise les actions sans les exécuter.

<p align="center"><img src="./images/en/gestures.png" width="380" alt="Réglages des gestes de déclenchement" /></p>

## Fonctionnement et réglages

Écrit entièrement en Swift, sans dépendance tierce, il réside dans la barre des menus. Les réglages restent sur votre Mac et peuvent être importés ou exportés ; l’interface est disponible en 12 langues.

https://github.com/user-attachments/assets/bf6afeee-3813-410c-87db-9696f364cea7

<a id="install"></a>

## Bien démarrer

Nécessite macOS 14 ou ultérieur et [Homebrew](https://brew.sh/) :

```bash
brew install --cask telungit/tap/telunkey
```

Au premier lancement, un assistant vous guide pour les autorisations, les touches de déclenchement, les raccourcis et les gestes. Mettez à jour depuis l’app ou exécutez :

```bash
brew upgrade --cask --greedy telungit/tap/telunkey
```

## Autorisations

| Autorisation | Usage |
| --- | --- |
| Accessibilité (requise) | Détecter les touches de déclenchement et les gestes ; changer de fenêtre et la placer |
| Enregistrement de l’écran (facultatif) | Miniatures des fenêtres ; sans elle, les icônes des apps s’affichent et le changement fonctionne toujours |

<a id="feedback"></a>

## Retours

- [GitHub Issues](https://github.com/telungit/TelunKey/issues)
- [Telegram](https://t.me/telungram)
