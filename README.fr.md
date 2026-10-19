<div align="center">

<img src="./images/icon.png" width="112" alt="Icône de TelunKey" />

# TelunKey

**Atteignez n’importe quelle fenêtre au clavier. Placez-la d’un geste.**

Maintenez une touche et tapez une ou deux lettres pour aller droit à n’importe quelle fenêtre de n’importe quelle app. Un glissement sur le trackpad, et la fenêtre se met en place.

[![Dernière version](https://img.shields.io/github/v/release/telungit/TelunKey?label=release)](https://github.com/telungit/TelunKey/releases/latest)
![macOS 14+](https://img.shields.io/badge/macOS-14%2B-black?logo=apple)

[Site web](https://www.telunkey.shop) · [Installer](#install) · [Retours](#feedback)

[简体中文](./README.md) | [繁體中文](./README.zh-Hant.md) | [English](./README.en.md) | [日本語](./README.ja.md) | [한국어](./README.ko.md) | [Español](./README.es.md) | [Português](./README.pt.md) | [हिन्दी](./README.hi.md) | [Русский](./README.ru.md) | Français | [Deutsch](./README.de.md) | [العربية](./README.ar.md)

</div>

## Deux ou trois touches jusqu’à n’importe quelle app

Maintenez une touche de déclenchement (Commande gauche / droite, Option gauche / droite ou Espace) et tapez une à trois lettres. Si l’app n’est pas ouverte, elle s’ouvre ; avec une seule fenêtre, celle-ci passe au premier plan ; avec plusieurs, un sélecteur apparaît. Tant que la touche est maintenue, tous les raccourcis s’affichent : rien à mémoriser.

<img src="./images/en/hint.png" width="100%" alt="Menu d’aide listant tous les raccourcis pendant que la touche de déclenchement est maintenue" />

## Choisir la bonne fenêtre d’un coup d’œil

Le sélecteur affiche toutes les fenêtres de l’app en miniatures. Appuyez sur un chiffre ou une lettre pour en choisir une, ou sur Espace pour la plus récemment utilisée. Lorsque les fenêtres sont réparties sur plusieurs bureaux, chaque carte indique le bureau concerné.

<img src="./images/en/picker.png" width="100%" alt="Sélecteur de fenêtres avec miniatures" />

## Un glissement, et la fenêtre se met en place

- **Gestes de déclenchement** : maintenez la touche de déclenchement et glissez sur le trackpad pour placer la fenêtre sous le pointeur sur une moitié, un quart ou tout l’écran.
- **Gestes globaux** : associez balayages, touchers ou clics à trois doigts à des actions de fenêtre, des raccourcis clavier ou des touches seules.
- **D’un écran à l’autre** : prolongez un geste global au-delà du bord pour déplacer la fenêtre vers un autre écran en conservant ses proportions.
- Chaque geste peut être réattribué, et un mode d’entraînement prévisualise les actions sans les exécuter.

## Natif et léger

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

## Autorisations et confidentialité

| Autorisation | Usage |
| --- | --- |
| Accessibilité (requise) | Détecter les touches de déclenchement et les gestes ; changer de fenêtre et la placer |
| Enregistrement de l’écran (facultatif) | Miniatures des fenêtres ; sans elle, les icônes des apps s’affichent et le changement fonctionne toujours |

Les réglages sont stockés sur votre Mac et l’identifiant de licence dans le trousseau. TelunKey ne se connecte à Internet que pour vérifier la licence et rechercher des mises à jour, et ne collecte aucune donnée d’utilisation.

## Gratuit et sous licence

La version gratuite permet d’associer jusqu’à 5 apps, toutes les autres fonctions étant incluses. Une licence à vie sur le [site web](https://www.telunkey.shop) lève cette limite.

<a id="feedback"></a>

## Retours

- [GitHub Issues](https://github.com/telungit/TelunKey/issues)
- [Telegram](https://t.me/telungram)
