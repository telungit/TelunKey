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

Maintenez la touche de déclenchement et balayez avec un, deux ou trois doigts activés pour placer la fenêtre sous le pointeur sur une moitié, un quart ou la maximiser.

- Haut, bas, gauche, droite : moitiés. Quatre diagonales : quarts
- Haut puis bas sans lever les doigts : agrandir, en gardant la barre des menus et le Dock
- Entrez dans la zone d'annulation pour annuler ; revenez pour choisir à nouveau

<p align="center"><img src="./images/en/gestures.png" width="380" alt="Réglages des gestes de déclenchement" /></p>

## Gestes globaux à trois et quatre doigts

Sans touche de déclenchement. Associez les balayages et allers-retours à trois doigts, ainsi que les touchers, doubles touchers et clics physiques à trois ou quatre doigts à des raccourcis, touches seules, clics du milieu ou opérations de fenêtre ; l’appui prolongé est réservé au changement d’écran. Toutes les actions ciblent la fenêtre verrouillée sous le pointeur, avec un mode d’entraînement qui prévisualise sans exécuter.

En cas de conflit avec le balayage, le glissement ou la définition système à trois doigts, TelunKey liste uniquement les options actives et ouvre directement la page correspondante des Réglages Système, puis revérifie automatiquement à votre retour sans jamais modifier vos réglages lui-même. Tant que le conflit persiste, les balayages et l’appui prolongé à trois doigts restent inactifs, tandis que les touchers et clics demeurent disponibles.

## Appui prolongé pour changer d’écran

À gauche, à droite ou au-dessus ? Un appui prolongé révèle une carte fidèle à la disposition de vos écrans macOS ; glissez vers l’écran voulu, puis relevez les doigts pour y déplacer la fenêtre en conservant ses proportions.

- Maintenez quatre doigts pour choisir un écran (les balayages ordinaires à quatre doigts restent à macOS) ; trois doigts une fois prêts, ou la touche de déclenchement maintenue avec un à trois doigts activés, fonctionnent aussi
- Déplace la fenêtre vers le bureau actuellement visible sur l’écran cible ; les fenêtres en plein écran et les écrans affichant une app en plein écran sont exclus
- Revenez en arrière à tout moment avant de confirmer ; relevez les doigts sur l’écran source ou dans le vide, relâchez la touche de déclenchement plus tôt ou appuyez sur Esc pour annuler

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
