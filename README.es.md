# TelunKey
[简体中文](./README.md) | [繁體中文](./README.zh-Hant.md) | [English](./README.en.md) | [日本語](./README.ja.md) | [한국어](./README.ko.md) | [Español](./README.es.md) | [Português](./README.pt.md) | [हिन्दी](./README.hi.md) | [Русский](./README.ru.md) | [Français](./README.fr.md) | [Deutsch](./README.de.md) | [العربية](./README.ar.md)

TelunKey es un lanzador de atajos nativo de macOS que permite activar apps y elegir ventanas en una sola secuencia de teclas.

- Desarrollado en Swift nativo: respuesta rápida, bajo consumo y mínima interferencia
- Admite Command izquierdo/derecho (retardo 0 o personalizado), Option izquierdo/derecho (retardo 0 o personalizado) y activación con Space (retardo mínimo de 0,2 s para no afectar la escritura diaria)
- Optimizado para flujos de trabajo de alta frecuencia y un cambio de ventanas más fluido
- Enfoque local-first: sin dependencia predeterminada de análisis de comportamiento en la nube

## Sitio web

- Página de inicio de Zeabur: https://telunkey.zeabur.app

> [!IMPORTANT]
> Si no puede acceder a Zeabur de forma continuada, es probable que no tenga un escenario real de uso para TelunKey. No obstante, si cuenta con la capacidad y la paciencia para resolver las dificultades de red, le recomendamos probar TelunKey; estoy convencido de que aumentará notablemente su productividad.

## Vista previa de la interfaz de usuario

https://github.com/user-attachments/assets/bf6afeee-3813-410c-87db-9696f364cea7

<img alt="Sugerencia de activación" src="./images/datishi.png?v=20260329" width="100%" />
<img alt="Escenario de Chrome" src="./images/chrome.png?v=20260329" width="100%" />
<img alt="Pantalla de ajustes" src="./images/shezhi.png?v=20260329" width="100%" />

## Requisitos del sistema

- macOS 14.0 o posterior

## Instalación

Los usuarios que tengan instalado [Homebrew](https://brew.sh/) pueden ejecutar:

```bash
brew update
brew install --cask telungit/tap/telunkey
```

Tras la instalación, abra TelunKey desde «Aplicaciones».

## Actualización

```bash
brew update
brew upgrade --cask --greedy telungit/tap/telunkey
```

También puede comprobar las actualizaciones directamente desde la aplicación.

## Permisos

TelunKey requiere los siguientes permisos para una funcionalidad completa:

- Accesibilidad: escuchar eventos globales de teclado
- Grabación de pantalla: generar miniaturas de ventanas

## Privacidad

TelunKey sigue una estrategia que da prioridad a lo local. Los datos básicos permanecen en su máquina.

## Comentarios

- Telegram: https://t.me/telungram
