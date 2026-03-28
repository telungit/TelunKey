# TelunKey
[简体中文](./README.md) | [繁體中文](./README.zh-Hant.md) | [English](./README.en.md) | [日本語](./README.ja.md) | [한국어](./README.ko.md) | [Español](./README.es.md) | [Português](./README.pt.md) | [हिन्दी](./README.hi.md) | [Русский](./README.ru.md) | [Français](./README.fr.md) | [Deutsch](./README.de.md) | [العربية](./README.ar.md)

TelunKey é um iniciador de atalhos nativo do macOS que completa a ativação do aplicativo e a seleção de janelas em um fluxo de teclas.

- Construído com Swift nativo para resposta rápida, baixa sobrecarga e interrupção mínima
- Suporta comando Esquerdo/Direito (atraso 0 ou atraso personalizado), opção Esquerda/Direita (atraso 0 ou atraso personalizado) e gatilho de espaço (atraso mínimo de 0,2s para evitar afetar a digitação normal)
- Otimizado para fluxos de trabalho de alta frequência e troca de janela mais suave
- Prioridade local por design, sem dependência padrão de análise de comportamento na nuvem

## Site

- Página inicial do Zeabur: https://telunkey.zeabur.app

> [!IMPORTANTE]
> Se você não conseguir acessar o Zeabur, o TelunKey pode não se adequar ao seu ambiente atual. Se você puder resolver problemas de rede do seu lado, vale a pena tentar o TelunKey e pode melhorar sua eficiência.

## Visualização da IU

https://github.com/user-attachments/assets/762f43e0-eac3-4ffa-ba33-f68f720d2627

![Trigger hint](./images/datishi.png)
![Chrome scenario](./images/chrome.png)
![Settings](./images/shezhi.png)

## Requisitos do sistema

- macOS 14.0 ou posterior

## Download

- Versão mais recente (DMG): https://github.com/telungit/TelunKey/releases/latest/download/TelunKey.dmg
- Todos os lançamentos: https://github.com/telungit/TelunKey/releases

## Instalação

1. Baixe e abra `TelunKey.dmg`
2. Arraste `TelunKey.app` para aplicativos
3. Não abra o app ainda. Primeiro, clique duas vezes em `一键修复.command` dentro do DMG
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

TelunKey segue uma estratégia local. Os dados principais permanecem em sua máquina.

## Opinião

- Telegrama: https://t.me/telungram
