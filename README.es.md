<div align="center">

<img src="./images/icon.png" width="112" alt="Icono de TelunKey" />

# TelunKey

**Cambio de ventanas para macOS · Teclado y trackpad**

Mantén una tecla de activación y pulsa de una a tres teclas para llegar a cualquier app o ventana. Desliza en el trackpad para colocarla.

[![Última versión](https://img.shields.io/github/v/release/telungit/TelunKey?label=release)](https://github.com/telungit/TelunKey/releases/latest)
![macOS 14+](https://img.shields.io/badge/macOS-14%2B-black?logo=apple)

[Sitio web](https://www.telunkey.shop) · [Instalar](#install) · [Comentarios](#feedback)

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

Mantén pulsada la tecla de activación y desliza dos dedos en el trackpad para colocar la ventana bajo el puntero en media pantalla, un cuarto o maximizada.

- Arriba, abajo, izquierda, derecha: mitades. Cuatro diagonales: cuartos
- Arriba y luego abajo sin levantar: maximizar, conservando la barra de menús y el Dock
- Entra en la zona de cancelación para cancelar; vuelve para elegir otra vez

### Gestos de tres dedos

Al activarlos, ocho direcciones, idas y vueltas, toque, doble toque, toque largo y clic pueden enviar un atajo, una sola tecla, un clic central o una acción de ventana.

- Desactivados por defecto. Si chocan con un gesto de tres dedos del sistema, Ajustes lo indica y enlaza a la solución
- Entre pantallas: continúa un gesto de tres dedos hacia fuera, más allá de la zona de cancelación, para mover la ventana a otra pantalla conservando sus proporciones.
- Cada gesto se puede reasignar, y un modo de práctica muestra las acciones sin ejecutarlas.

<p align="center"><img src="./images/en/gestures.png" width="380" alt="Ajustes de gestos de activación" /></p>

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

## Permisos y privacidad

| Permiso | Para qué |
| --- | --- |
| Accesibilidad (obligatorio) | Detectar teclas de activación y gestos; cambiar y colocar ventanas |
| Grabación de pantalla (opcional) | Miniaturas de ventanas; sin él se muestran los iconos de las apps y el cambio sigue funcionando |

TelunKey es local primero y no recopila contenido de pulsaciones de teclas ni telemetría del comportamiento de las ventanas.

Dodo Payments gestiona pagos, correos de compra, claves y activaciones. Al activar se envían la clave y el nombre del dispositivo para gestionar el límite de dos equipos. La clave y el registro local se guardan en el Llavero del sistema. No guardamos tarjetas ni creamos cuentas web.

## Versión gratuita y Actualizaciones de por vida

La versión gratuita permite asignar hasta 5 apps, con todas las funciones, sin límite de tiempo ni cuenta. El plan Actualizaciones de por vida cuesta US$3.99 en un pago único e incluye asignaciones ilimitadas y futuras actualizaciones.

Una vez completado el pago, busca el correo de Dodo Payments con tu clave de licencia e introdúcela en la página Licencia de los ajustes de TelunKey. No hace falta cuenta. Puedes usarlo en 2 Mac; desactiva el antiguo antes de cambiar.

[Planes y condiciones](https://www.telunkey.shop/es/terms)

<a id="feedback"></a>

## Comentarios

- [GitHub Issues](https://github.com/telungit/TelunKey/issues)
- [Telegram](https://t.me/telungram)
