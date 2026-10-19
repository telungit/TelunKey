<div align="center">

<img src="./images/icon.png" width="112" alt="Ícone do TelunKey" />

# TelunKey

**Troca de janelas no macOS · Teclado e trackpad**

Segure uma tecla de gatilho e digite de uma a três teclas para chegar a qualquer app ou janela. Deslize no trackpad para posicioná-la.

[![Versão mais recente](https://img.shields.io/github/v/release/telungit/TelunKey?label=release)](https://github.com/telungit/TelunKey/releases/latest)
![macOS 14+](https://img.shields.io/badge/macOS-14%2B-black?logo=apple)

[Site](https://www.telunkey.shop) · [Instalar](#install) · [Feedback](#feedback)

[简体中文](./README.md) | [繁體中文](./README.zh-Hant.md) | [English](./README.en.md) | [日本語](./README.ja.md) | [한국어](./README.ko.md) | [Español](./README.es.md) | Português | [हिन्दी](./README.hi.md) | [Русский](./README.ru.md) | [Français](./README.fr.md) | [Deutsch](./README.de.md) | [العربية](./README.ar.md)

</div>

## Teclas diretas

Mantenha pressionada uma tecla de gatilho (Command esquerda / direita, Option esquerda / direita ou Espaço) e digite de uma a três teclas atribuídas a um app. Se não estiver aberto, ele abre; com uma janela, ela vem para a frente; com várias, aparece o seletor. As atribuições ficam visíveis enquanto a tecla de gatilho estiver pressionada.

<img src="./images/en/hint.png" width="100%" alt="Menu de dicas listando todas as atribuições enquanto a tecla de gatilho está pressionada" />

## Seletor pelo teclado

O seletor organiza as miniaturas na ordem do teclado: 1–0, Q–P, A–L, Z–M, com até 36 janelas por página. Pressione o número ou a letra correspondente para selecionar uma janela.

- Espaço: volta para a última janela usada
- Janelas de outras mesas mostram em qual mesa estão
- [ e ] trocam de página, Esc cancela, ou é só clicar

<img src="./images/en/picker.png" width="100%" alt="Seletor de janelas" />

## Gestos de gatilho

Mantenha a tecla de gatilho pressionada e deslize dois dedos no trackpad para posicionar a janela sob o ponteiro em metade da tela, um quarto ou maximizada.

- Cima, baixo, esquerda, direita: metades. Quatro diagonais: quartos
- Para cima e depois para baixo sem levantar: maximizar, mantendo a barra de menus e o Dock
- Entre na zona de cancelamento para cancelar; volte para escolher de novo

### Gestos com três dedos

Depois de ativados, oito direções, idas e voltas, toque, toque duplo, toque longo e clique podem enviar um atalho, uma única tecla, um clique do meio ou uma ação de janela.

- Desativados por padrão. Se houver conflito com um gesto de três dedos do sistema, os Ajustes mostram e indicam como resolver
- Entre monitores: continue um gesto de três dedos para fora, além da zona de cancelamento, para mover a janela a outro monitor mantendo suas proporções.
- Todo gesto pode ser reatribuído, e um modo de prática pré-visualiza as ações sem executá-las.

<p align="center"><img src="./images/en/gestures.png" width="380" alt="Ajustes de gestos de gatilho" /></p>

## Funcionamento e configurações

Escrito inteiramente em Swift, sem dependências de terceiros, e fica na barra de menus. As configurações ficam no seu Mac e podem ser importadas e exportadas; a interface está disponível em 12 idiomas.

https://github.com/user-attachments/assets/bf6afeee-3813-410c-87db-9696f364cea7

<a id="install"></a>

## Primeiros passos

Requer macOS 14 ou posterior e [Homebrew](https://brew.sh/):

```bash
brew install --cask telungit/tap/telunkey
```

Na primeira abertura, um assistente guia você pelas permissões, teclas de gatilho, atalhos e gestos. Atualize pelo próprio app ou execute:

```bash
brew upgrade --cask --greedy telungit/tap/telunkey
```

## Permissões e privacidade

| Permissão | Para quê |
| --- | --- |
| Acessibilidade (obrigatória) | Detectar teclas de gatilho e gestos; alternar e posicionar janelas |
| Gravação de tela (opcional) | Miniaturas das janelas; sem ela, aparecem os ícones dos apps e a troca continua funcionando |

TelunKey prioriza o local e não coleta conteúdo de pressionamento de tecla ou telemetria de comportamento de janela.

A Dodo Payments processa pagamentos, e-mails de compra, chaves e ativações. A ativação envia a chave e o nome do dispositivo para gerenciar o limite de dois Macs. A chave e o registro local ficam nas Chaves do sistema. Não armazenamos cartões nem criamos contas no site.

## Versão gratuita e Atualizações vitalícias

A versão gratuita permite atribuir até 5 apps, com todos os recursos, sem limite de tempo nem conta. O plano Atualizações vitalícias custa US$3.99 em pagamento único e inclui atribuições ilimitadas e futuras atualizações.

Depois de concluir o pagamento, procure o e-mail da Dodo Payments com a chave de licença e digite-a na página Licença dos ajustes do TelunKey. Não é preciso conta. Você pode usar em 2 Macs; desative o antigo antes de trocar.

[Planos e termos](https://www.telunkey.shop/pt/terms)

<a id="feedback"></a>

## Feedback

- [GitHub Issues](https://github.com/telungit/TelunKey/issues)
- [Telegram](https://t.me/telungram)
