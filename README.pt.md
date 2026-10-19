<div align="center">

<img src="./images/icon.png" width="112" alt="Ícone do TelunKey" />

# TelunKey

**Chegue a qualquer janela pelo teclado. Posicione-a com um gesto.**

Mantenha uma tecla pressionada e digite uma ou duas letras para ir direto a qualquer janela de qualquer app. Deslize no trackpad e a janela se encaixa no lugar.

[![Versão mais recente](https://img.shields.io/github/v/release/telungit/TelunKey?label=release)](https://github.com/telungit/TelunKey/releases/latest)
![macOS 14+](https://img.shields.io/badge/macOS-14%2B-black?logo=apple)

[Site](https://www.telunkey.shop) · [Instalar](#install) · [Feedback](#feedback)

[简体中文](./README.md) | [繁體中文](./README.zh-Hant.md) | [English](./README.en.md) | [日本語](./README.ja.md) | [한국어](./README.ko.md) | [Español](./README.es.md) | Português | [हिन्दी](./README.hi.md) | [Русский](./README.ru.md) | [Français](./README.fr.md) | [Deutsch](./README.de.md) | [العربية](./README.ar.md)

</div>

## Duas ou três teclas até qualquer app

Mantenha pressionada uma tecla de ativação (Command esquerda / direita, Option esquerda / direita ou Espaço) e digite de uma a três letras. Se o app não estiver aberto, ele abre; com uma janela, ela vem para a frente; com várias, aparece um seletor. Enquanto a tecla estiver pressionada, todas as atribuições ficam listadas, então não é preciso decorar nada.

<img src="./images/en/hint.png" width="100%" alt="Menu de dicas listando todas as atribuições enquanto a tecla de ativação está pressionada" />

## Escolha a janela num relance

O seletor mostra todas as janelas do app em miniatura. Pressione um número ou uma letra para escolher, ou Espaço para a usada mais recentemente. Quando as janelas estão espalhadas por várias mesas, cada cartão indica em qual delas está.

<img src="./images/en/picker.png" width="100%" alt="Seletor de janelas com miniaturas" />

## Deslize e a janela se encaixa

- **Gestos de ativação**: mantenha a tecla de ativação e deslize no trackpad para levar a janela sob o ponteiro a metade da tela, um quarto ou tela cheia.
- **Gestos globais**: atribua deslizes, toques ou cliques com três dedos a ações de janela, atalhos de teclado ou teclas avulsas.
- **Entre monitores**: leve um gesto global além da borda para mover a janela a outro monitor, mantendo as proporções.
- Todo gesto pode ser reatribuído, e um modo de prática pré-visualiza as ações sem executá-las.

## Nativo e leve

Escrito inteiramente em Swift, sem dependências de terceiros, e fica na barra de menus. As configurações ficam no seu Mac e podem ser importadas e exportadas; a interface está disponível em 12 idiomas.

https://github.com/user-attachments/assets/bf6afeee-3813-410c-87db-9696f364cea7

<a id="install"></a>

## Primeiros passos

Requer macOS 14 ou posterior e [Homebrew](https://brew.sh/):

```bash
brew install --cask telungit/tap/telunkey
```

Na primeira abertura, um assistente guia você pelas permissões, teclas de ativação, atalhos e gestos. Atualize pelo próprio app ou execute:

```bash
brew upgrade --cask --greedy telungit/tap/telunkey
```

## Permissões e privacidade

| Permissão | Para quê |
| --- | --- |
| Acessibilidade (obrigatória) | Detectar teclas de ativação e gestos; alternar e posicionar janelas |
| Gravação de tela (opcional) | Miniaturas das janelas; sem ela, aparecem os ícones dos apps e a troca continua funcionando |

As configurações ficam no seu Mac e a credencial da licença, nas Chaves. O TelunKey só se conecta à internet para verificar a licença e procurar atualizações, e não coleta dados de uso.

## Gratuito e licenciado

A versão gratuita permite atribuir até 5 apps, com todos os outros recursos incluídos. Uma licença vitalícia no [site](https://www.telunkey.shop) remove o limite.

<a id="feedback"></a>

## Feedback

- [GitHub Issues](https://github.com/telungit/TelunKey/issues)
- [Telegram](https://t.me/telungram)
