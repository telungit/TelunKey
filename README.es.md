# TelunKey
[简体中文](./README.md) | [繁體中文](./README.zh-Hant.md) | [English](./README.en.md) | [日本語](./README.ja.md) | [한국어](./README.ko.md) | [Español](./README.es.md) | [Português](./README.pt.md) | [हिन्दी](./README.hi.md) | [Русский](./README.ru.md) | [Français](./README.fr.md) | [Deutsch](./README.de.md) | [العربية](./README.ar.md)

TelunKey es un lanzador de atajos nativo de macOS que permite activar apps y elegir ventanas en una sola secuencia de teclas.

- Desarrollado en Swift nativo: respuesta rápida, bajo consumo y mínima interferencia
- Admite Command izquierdo/derecho (retardo 0 o personalizado), Option izquierdo/derecho (retardo 0 o personalizado) y activación con Space (retardo mínimo de 0,2 s para no afectar la escritura diaria)
- Optimizado para flujos de trabajo de alta frecuencia y un cambio de ventanas más fluido
- Enfoque local-first: sin dependencia predeterminada de análisis de comportamiento en la nube

## Sitio web

- Página de inicio de Zeabur: https://telunkey.zeabur.app

> [!IMPORTANTE]
> Si no puede acceder a Zeabur en absoluto, es posible que TelunKey no se ajuste a su entorno actual. Si puede resolver los problemas de red por su parte, vale la pena probar TelunKey y puede mejorar su eficiencia.

## Vista previa de la interfaz de usuario

https://github.com/user-attachments/assets/bf6afeee-3813-410c-87db-9696f364cea7

![Trigger hint](./images/datishi.png?v=20260329)
![Chrome scenario](./images/chrome.png?v=20260329)
![Settings](./images/shezhi.png?v=20260329)

## Requisitos del sistema

- macOS 14.0 o posterior

## Descargar

- Última versión (DMG): https://github.com/telungit/TelunKey/releases/latest/download/TelunKey.dmg
- Todos los lanzamientos: https://github.com/telungit/TelunKey/releases

## Instalación

1. Descargue y abra `TelunKey.dmg`
2. Arrastre `TelunKey.app` a Aplicaciones
3. No abra la app todavía. Primero haga doble clic en `一键修复.command` dentro del DMG
4. Abra TelunKey cuando termine la reparación
5. Solo si el script falla, ejecute manualmente el siguiente comando en la Terminal

```bash
xattr -dr com.apple.quarantine /Applications/TelunKey.app
```

## Permisos

TelunKey requiere los siguientes permisos para una funcionalidad completa:

- Accesibilidad: escuchar eventos globales de teclado
- Grabación de pantalla: genera miniaturas de ventanas

## Privacidad

TelunKey sigue una estrategia que da prioridad a lo local. Los datos básicos permanecen en su máquina.

## Comentario

- Telegrama: https://t.me/telungram
