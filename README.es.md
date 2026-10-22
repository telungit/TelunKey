<div align="center">

<img src="./images/icon.png" width="112" alt="Icono de TelunKey" />

# TelunKey

**Cambio de ventanas para macOS · Teclado y trackpad**

Mantén una tecla de activación y pulsa de una a tres teclas para llegar a cualquier app o ventana. Desliza en el trackpad para colocarla.

[![Última versión](https://img.shields.io/github/v/release/telungit/TelunKey?label=release)](https://github.com/telungit/TelunKey/releases/latest)
![macOS 14+](https://img.shields.io/badge/macOS-14%2B-black?logo=apple)

[telunkey.shop](https://www.telunkey.shop)

[Instalar](#install) · [Comentarios](#feedback)

[简体中文](./README.md) | [繁體中文](./README.zh-Hant.md) | [English](./README.en.md) | [日本語](./README.ja.md) | [한국어](./README.ko.md) | Español | [Português](./README.pt.md) | [हिन्दी](./README.hi.md) | [Русский](./README.ru.md) | [Français](./README.fr.md) | [Deutsch](./README.de.md) | [العربية](./README.ar.md)

</div>

## Teclas directas

Mantén pulsada una tecla de activación (Command izquierda / derecha, Option izquierda / derecha o Espacio) e introduce de una a tres teclas asignadas a una app. Si no está abierta, se abre; si tiene una ventana, pasa al frente; si tiene varias, aparece el selector. Las asignaciones se muestran mientras mantienes la tecla de activación.

<img src="./images/en/hint.png" width="100%" alt="Menú de ayuda con todas las asignaciones al mantener la tecla de activación" />

## Selector de teclado

El selector ordena las miniaturas como el teclado: 1–0, Q–P, A–L, Z–M, con hasta 36 ventanas por página. Pulsa el número o la letra correspondiente para elegir una ventana.

- Espacio: vuelve a la última ventana usada
- Las ventanas de otros escritorios indican en cuál están
- [ y ] cambian de página, Esc cancela, o simplemente haz clic

<img src="./images/en/picker.png" width="100%" alt="Selector de ventanas" />

## Gestos de activación

Mantén la tecla de activación y desliza con uno, dos o tres dedos habilitados para colocar la ventana bajo el puntero en mitades, cuartos o maximizarla.

- Arriba, abajo, izquierda, derecha: mitades. Cuatro diagonales: cuartos
- Arriba y luego abajo sin levantar: maximizar, conservando la barra de menús y el Dock
- Entra en la zona de cancelación para cancelar; vuelve para elegir otra vez

<p align="center"><img src="./images/en/gestures.png" width="380" alt="Ajustes de gestos de activación" /></p>

## Gestos globales con tres y cuatro dedos

Sin tecla de activación. Asigna deslizamientos y recorridos de ida y vuelta con tres dedos, además de toques, dobles toques y clics físicos con tres o cuatro dedos a atajos, teclas individuales, clics centrales u operaciones de ventana. La pulsación prolongada se reserva para mover entre pantallas. Las acciones usan la ventana fijada bajo el puntero.

Activado en instalaciones nuevas; las actualizaciones conservan tus ajustes. El contacto prolongado se reserva para mover entre pantallas. Los demás gestos pueden reasignarse; la práctica muestra sin ejecutar.

Antes de usar deslizamientos con tres dedos o mantener el contacto para elegir una pantalla, desactiva el arrastre del sistema con tres dedos y cambia los deslizamientos horizontales y verticales a cuatro dedos, o desactívalos. TelunKey muestra solo los conflictos activos y abre Trackpad → Más gestos o Accesibilidad → Control del puntero → Opciones del trackpad. Comprueba de nuevo al volver; también puedes configurarlo más tarde. Mientras haya conflictos, los deslizamientos y el contacto prolongado con tres dedos quedan inactivos; los toques y clics siguen disponibles. Los conflictos con la consulta del sistema se indican por separado. TelunKey nunca modifica los ajustes del sistema automáticamente.

## Mantén pulsado para cambiar de pantalla

¿A la izquierda, derecha o arriba? Una pulsación prolongada abre un mapa que sigue la disposición de pantallas de macOS. Desliza hasta la pantalla deseada y levanta los dedos para mover la ventana.

- Mantén cuatro dedos quietos y desliza para elegir pantalla. También funcionan tres dedos tras la configuración, o la tecla de activación mantenida con uno a tres dedos habilitados
- Elige según la disposición de pantallas; la ventana conserva su posición proporcional en las áreas utilizables
- Puedes volver antes de confirmar; levanta los dedos en la pantalla de origen o en un espacio vacío para cancelar. También puedes cancelar con Esc.

Los deslizamientos normales con cuatro dedos siguen en macOS. Primero mantén cuatro dedos quietos. TelunKey solo toma el control temporal de ese gesto cuando se abre la selección de pantalla; al levantar los dedos, vuelve al sistema.

Al escritorio visible en otra pantalla. Una sola pantalla no ofrece destino. Se excluyen ventanas a pantalla completa y pantallas con apps a pantalla completa. Levantar los dedos en el origen, en un espacio vacío o en una pantalla no disponible cancela. En los gestos de activación, mantén la tecla hasta levantar los dedos; soltarla antes también cancela.

## Funcionamiento y configuración

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

## Permisos

| Permiso | Para qué |
| --- | --- |
| Accesibilidad (obligatorio) | Detectar teclas de activación y gestos; cambiar y colocar ventanas |
| Grabación de pantalla (opcional) | Miniaturas de ventanas; sin él se muestran los iconos de las apps y el cambio sigue funcionando |

<a id="feedback"></a>

## Comentarios

- [GitHub Issues](https://github.com/telungit/TelunKey/issues)
- [Telegram](https://t.me/telungram)
