# TelunKey
[简体中文](./README.md) | [繁體中文](./README.zh-Hant.md) | [English](./README.en.md) | [日本語](./README.ja.md) | [한국어](./README.ko.md) | [Español](./README.es.md) | [Português](./README.pt.md) | [हिन्दी](./README.hi.md) | [Русский](./README.ru.md) | [Français](./README.fr.md) | [Deutsch](./README.de.md) | [العربية](./README.ar.md)

TelunKey é um lançador de atalhos nativo do macOS que reúne ativação de apps e seleção de janelas em uma única sequência de teclas.

- Construído em Swift nativo para resposta rápida, baixo consumo e mínima interferência
- Suporta Command esquerdo/direito (atraso zero ou personalizado), Option esquerda/direita (atraso zero ou personalizado) e gatilho com Space (mínimo de 0,2 s para não atrapalhar a digitação diária)
- Otimizado para fluxos de trabalho de alta frequência e troca de janela mais suave
- Design local-first, sem dependência padrão de análise comportamental na nuvem

## Site

- Página inicial do Zeabur: https://telunkey.zeabur.app

> [!IMPORTANT]
> Se você não conseguir acessar o Zeabur com regularidade, é provável que não tenha um cenário real de uso para o TelunKey. Mas se tiver a capacidade e a paciência para contornar problemas de rede, não deixe de experimentar o TelunKey — tenho certeza de que ele aumentará significativamente a sua produtividade.

## Visualização da IU

https://github.com/user-attachments/assets/bf6afeee-3813-410c-87db-9696f364cea7

<img alt="Dica de ativação" src="./images/datishi.png?v=20260329" width="100%" />
<img alt="Cenário do Chrome" src="./images/chrome.png?v=20260329" width="100%" />
<img alt="Tela de ajustes" src="./images/shezhi.png?v=20260329" width="100%" />

## Requisitos do sistema

- macOS 14.0 ou posterior

## Instalação

Usuários com o [Homebrew](https://brew.sh/) instalado podem executar:

```bash
brew update
brew install --cask telungit/tap/telunkey
```

Após a instalação, abra o TelunKey a partir de «Aplicativos».

## Atualização

```bash
brew update
brew upgrade --cask --greedy telungit/tap/telunkey
```

Você também pode verificar atualizações diretamente pelo aplicativo.

## Permissões

TelunKey requer as seguintes permissões para funcionalidade completa:

- Acessibilidade: monitorar eventos globais do teclado
- Gravação de tela: gerar miniaturas de janelas

## Privacidade

TelunKey segue uma estratégia local-first. Os dados principais permanecem no seu dispositivo.

## Feedback

- Telegram: https://t.me/telungram
