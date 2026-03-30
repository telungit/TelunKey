# TelunKey
[简体中文](./README.md) | [繁體中文](./README.zh-Hant.md) | [English](./README.en.md) | [日本語](./README.ja.md) | [한국어](./README.ko.md) | [Español](./README.es.md) | [Português](./README.pt.md) | [हिन्दी](./README.hi.md) | [Русский](./README.ru.md) | [Français](./README.fr.md) | [Deutsch](./README.de.md) | [العربية](./README.ar.md)

TelunKey é um lançador de atalhos nativo do macOS que reúne ativação de apps e seleção de janelas em uma única sequência de teclas.

- Construído em Swift nativo para resposta rápida, baixo consumo e mínima interferência
- Suporta Command esquerdo/direito (atraso zero ou personalizado), Option esquerda/direita (atraso zero ou personalizado) e gatilho com Space (mínimo de 0,2 s para não atrapalhar a digitação diária)
- Otimizado para fluxos de trabalho de alta frequência e troca de janela mais suave
- Design local-first, sem dependência padrão de análise comportamental na nuvem

## Site

- Página inicial do Zeabur: https://telunkey.zeabur.app

> [!IMPORTANTE]
> Se você não conseguir acessar o Zeabur, o TelunKey pode não se adequar ao seu ambiente atual. Se você puder resolver problemas de rede do seu lado, vale a pena tentar o TelunKey e pode melhorar sua eficiência.

## Visualização da IU

https://github.com/user-attachments/assets/bf6afeee-3813-410c-87db-9696f364cea7

<img alt="Dica de ativação" src="./images/datishi.png?v=20260329" width="100%" />
<img alt="Cenário do Chrome" src="./images/chrome.png?v=20260329" width="100%" />
<img alt="Tela de ajustes" src="./images/shezhi.png?v=20260329" width="100%" />

## Requisitos do sistema

- macOS 14.0 ou posterior

## Download

- Versão mais recente (DMG): https://github.com/telungit/TelunKey/releases/latest/download/TelunKey.dmg
- Todos os lançamentos: https://github.com/telungit/TelunKey/releases

## Instalação

1. Baixe e abra `TelunKey.dmg`
2. Arraste `TelunKey.app` para aplicativos
3. Não abra o app ainda. Primeiro, clique duas vezes em `2. Run Once After Install.command` dentro do DMG
4. Abra o TelunKey depois que a correção terminar
5. Somente se o script falhar, execute o seguinte comando manualmente no Terminal

```bash
xattr -dr com.apple.quarantine /Applications/TelunKey.app
```

## Permissões

TelunKey requer as seguintes permissões para funcionalidade completa:

- Acessibilidade: ouça eventos globais de teclado
- Gravação de tela: gere miniaturas de janelas

## Privacidade

TelunKey segue uma estratégia local-first. Os dados principais permanecem no seu dispositivo.

## Feedback

- Telegram: https://t.me/telungram
