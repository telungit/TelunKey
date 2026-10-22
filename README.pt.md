<div align="center">

<img src="./images/icon.png" width="112" alt="Ícone do TelunKey" />

# TelunKey

**Troca de janelas no macOS · Teclado e trackpad**

Segure uma tecla de gatilho e digite de uma a três teclas para chegar a qualquer app ou janela. Deslize no trackpad para posicioná-la.

[![Versão mais recente](https://img.shields.io/github/v/release/telungit/TelunKey?label=release)](https://github.com/telungit/TelunKey/releases/latest)
![macOS 14+](https://img.shields.io/badge/macOS-14%2B-black?logo=apple)

[telunkey.shop](https://www.telunkey.shop)

[Instalar](#install) · [Feedback](#feedback)

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

Segure a tecla de ativação e deslize com um, dois ou três dedos habilitados para posicionar a janela sob o cursor em metades, quartos ou maximizá-la.

- Cima, baixo, esquerda, direita: metades. Quatro diagonais: quartos
- Para cima e depois para baixo sem levantar: maximizar, mantendo a barra de menus e o Dock
- Entre na zona de cancelamento para cancelar; volte para escolher de novo

<p align="center"><img src="./images/en/gestures.png" width="380" alt="Ajustes de gestos de gatilho" /></p>

## Gestos globais com três e quatro dedos

Sem tecla de ativação. Associe deslizes e movimentos de ida e volta com três dedos, bem como toques, duplos toques e cliques físicos com três ou quatro dedos a atalhos, teclas individuais, cliques do meio ou operações de janela. O toque prolongado está reservado para mover entre ecrãs. As ações usam a janela fixada sob o cursor.

Ativado em novas instalações; atualizações preservam seus ajustes. O toque prolongado é reservado à mudança de tela. Os demais gestos podem ser remapeados; a prática mostra sem executar.

Antes de usar deslizes com três dedos ou manter o toque para escolher uma tela, desative o arrasto do sistema com três dedos e altere os deslizes horizontais e verticais para quatro dedos, ou desative-os. O TelunKey lista apenas conflitos ativos e leva a Trackpad → Mais Gestos ou Acessibilidade → Controle do Cursor → Opções do Trackpad. A verificação é automática ao voltar; você também pode configurar depois. Enquanto houver conflitos, os deslizes e o toque prolongado com três dedos ficam inativos; toques e cliques continuam disponíveis. Conflitos com a consulta do sistema são indicados separadamente. O TelunKey nunca altera os ajustes do sistema automaticamente.

## Mantenha o toque para mudar de ecrã

À esquerda, à direita ou acima? Um toque prolongado abre um mapa que segue a disposição de ecrãs do macOS. Deslize até ao ecrã pretendido e levante os dedos para mover a janela.

- Mantenha quatro dedos parados e deslize para escolher a tela. Também funcionam três dedos após a configuração ou a tecla de ativação pressionada com um a três dedos habilitados
- Escolha pela disposição dos ecrãs; a janela mantém a posição proporcional nas áreas utilizáveis
- Pode voltar antes de confirmar; levante os dedos no ecrã de origem ou num espaço vazio para cancelar. Você também pode cancelar com Esc.

Os deslizes comuns com quatro dedos continuam no macOS. Primeiro mantenha quatro dedos parados. O TelunKey assume temporariamente esse gesto somente depois que a seleção de tela começa; ao levantar os dedos, o controle volta ao sistema.

Para a secretária atualmente visível noutro ecrã. Um só ecrã não oferece destino. Janelas em ecrã completo e ecrãs com apps em ecrã completo ficam excluídos. Levantar os dedos na origem, num espaço vazio ou num ecrã indisponível cancela. Nos gestos de ativação, mantenha a tecla até levantar os dedos; soltá-la antes também cancela.

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

## Permissões

| Permissão | Para quê |
| --- | --- |
| Acessibilidade (obrigatória) | Detectar teclas de gatilho e gestos; alternar e posicionar janelas |
| Gravação de tela (opcional) | Miniaturas das janelas; sem ela, aparecem os ícones dos apps e a troca continua funcionando |

<a id="feedback"></a>

## Feedback

- [GitHub Issues](https://github.com/telungit/TelunKey/issues)
- [Telegram](https://t.me/telungram)
