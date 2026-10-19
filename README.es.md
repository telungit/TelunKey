<div align="center">

<img src="./images/icon.png" width="112" alt="Icono de TelunKey" />

# TelunKey

**Llega a cualquier ventana con el teclado. Colócala con un gesto.**

Mantén pulsada una tecla y escribe una o dos letras para ir directo a cualquier ventana de cualquier app. Desliza en el trackpad y la ventana queda en su sitio.

[![Última versión](https://img.shields.io/github/v/release/telungit/TelunKey?label=release)](https://github.com/telungit/TelunKey/releases/latest)
![macOS 14+](https://img.shields.io/badge/macOS-14%2B-black?logo=apple)

[Sitio web](https://www.telunkey.shop) · [Instalar](#install) · [Comentarios](#feedback)

[简体中文](./README.md) | [繁體中文](./README.zh-Hant.md) | [English](./README.en.md) | [日本語](./README.ja.md) | [한국어](./README.ko.md) | Español | [Português](./README.pt.md) | [हिन्दी](./README.hi.md) | [Русский](./README.ru.md) | [Français](./README.fr.md) | [Deutsch](./README.de.md) | [العربية](./README.ar.md)

</div>

## Dos o tres teclas hasta cualquier app

Mantén pulsada una tecla de activación (Command izquierda / derecha, Option izquierda / derecha o Espacio) y escribe de una a tres letras. Si la app no está abierta, se abre; si tiene una ventana, pasa al frente; si tiene varias, aparece un selector. Mientras mantienes la tecla se muestran todas las asignaciones, así que no hay nada que memorizar.

<img src="./images/en/hint.png" width="100%" alt="Menú de ayuda con todas las asignaciones al mantener la tecla de activación" />

## Elige la ventana de un vistazo

El selector muestra todas las ventanas de la app en miniatura. Pulsa un número o una letra para elegir una, o Espacio para la usada más recientemente. Si las ventanas están repartidas en varios escritorios, cada tarjeta indica en cuál está.

<img src="./images/en/picker.png" width="100%" alt="Selector de ventanas con miniaturas" />

## Desliza y la ventana queda en su sitio

- **Gestos de activación**: mantén la tecla de activación y desliza en el trackpad para llevar la ventana bajo el puntero a media pantalla, un cuarto o pantalla completa.
- **Gestos globales**: asigna deslizamientos, toques o clics con tres dedos a acciones de ventana, atajos de teclado o teclas sueltas.
- **Entre pantallas**: lleva un gesto global más allá del borde para mover la ventana a otra pantalla, manteniendo sus proporciones.
- Cada gesto se puede reasignar, y un modo de práctica muestra las acciones sin ejecutarlas.

## Nativo y ligero

Escrito íntegramente en Swift, sin dependencias de terceros, y vive en la barra de menús. La configuración se guarda en tu Mac y se puede importar y exportar; la interfaz está disponible en 12 idiomas.

https://github.com/user-attachments/assets/bf6afeee-3813-410c-87db-9696f364cea7

<a id="install"></a>

## Primeros pasos

Requiere macOS 14 o posterior y [Homebrew](https://brew.sh/):

```bash
brew install --cask telungit/tap/telunkey
```

Al abrirla por primera vez, un asistente te guía por los permisos, las teclas de activación, los atajos y los gestos. Actualiza desde la propia app o ejecuta:

```bash
brew upgrade --cask --greedy telungit/tap/telunkey
```

## Permisos y privacidad

| Permiso | Para qué |
| --- | --- |
| Accesibilidad (obligatorio) | Detectar teclas de activación y gestos; cambiar y colocar ventanas |
| Grabación de pantalla (opcional) | Miniaturas de ventanas; sin él se muestran los iconos de las apps y el cambio sigue funcionando |

La configuración se guarda en tu Mac y la credencial de licencia, en el llavero. TelunKey solo se conecta a internet para verificar la licencia y buscar actualizaciones, y no recopila datos de uso.

## Gratis y con licencia

La versión gratuita permite asignar hasta 5 apps, con todas las demás funciones incluidas. Una licencia permanente del [sitio web](https://www.telunkey.shop) elimina el límite.

<a id="feedback"></a>

## Comentarios

- [GitHub Issues](https://github.com/telungit/TelunKey/issues)
- [Telegram](https://t.me/telungram)
