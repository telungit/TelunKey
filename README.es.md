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

Sin tecla de activación. Asigna deslizamientos y recorridos de ida y vuelta con tres dedos, además de toques, dobles toques y clics físicos con tres o cuatro dedos a atajos, teclas individuales, clics centrales u operaciones de ventana; la pulsación prolongada se reserva para cambiar de pantalla. Todas las acciones actúan sobre la ventana fijada bajo el puntero e incluyen un modo de práctica que previsualiza sin ejecutar.

Si hay conflicto con el deslizamiento, el arrastre o la consulta del sistema con tres dedos, TelunKey muestra solo las opciones activas y abre directamente la página correspondiente de Ajustes del Sistema, volviendo a comprobar al regresar sin modificar nada por su cuenta. Mientras persista el conflicto, los deslizamientos y la pulsación prolongada con tres dedos quedan inactivos, pero los toques y clics siguen disponibles.

## Mantén pulsado para cambiar de pantalla

¿A la izquierda, derecha o arriba? Mantén pulsado para abrir un mapa fiel a la disposición de pantallas de macOS, desliza hacia la pantalla deseada y levanta los dedos para mover la ventana conservando su proporción.

- Mantén pulsados cuatro dedos para elegir pantalla (los deslizamientos normales de cuatro dedos siguen en macOS); también funcionan tres dedos una vez configurados, o la tecla de activación mantenida con uno a tres dedos habilitados
- Mueve la ventana al escritorio visible en la pantalla de destino; se excluyen las ventanas a pantalla completa y las pantallas con una app a pantalla completa
- Puedes volver atrás antes de confirmar; levanta los dedos en la pantalla de origen o en un espacio vacío, suelta antes la tecla de activación o pulsa Esc para cancelar

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
