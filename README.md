<!--
  PORTADA DEL REPOSITORIO PÚBLICO DE DESCARGAS.

  No se edita allí: el trabajo `publicar` de .github/workflows/instaladores.yml copia este archivo
  como README.md del repositorio público en cada release. Se edita aquí.
-->

<div align="center">

<img src="Assets/Icons/judo-256.png" alt="JudoInstalador" width="128">

# Instalador de Judo

**Todas las aplicaciones de la competición, en un solo paso.**

[![Descargar](https://img.shields.io/badge/Descargar-última%20versión-brightgreen?logo=github)](../../releases/latest)
[![Windows · macOS · Linux](https://img.shields.io/badge/Windows%20·%20macOS%20·%20Linux-multiplataforma-informational)](#cómo-se-usa)

</div>

---

## Qué es

Un programa que se abre una vez en cada equipo de la competición y deja instaladas las aplicaciones
que elijas: [JudoAdministración](https://github.com/JuSaFe/JudoAdministracion-Releases),
[JudoCrono](https://github.com/JuSaFe/JudoCrono-Releases),
[JudoCombates](https://github.com/JuSaFe/JudoCombates-Releases),
[JudoClasificación](https://github.com/JuSaFe/JudoClasificacion-Releases)… y las que se publiquen en
adelante, que aparecen solas.

Baja de cada una la última versión **para el sistema del equipo** y las instala una detrás de otra.
En un equipo que ya las tiene, marca las que tienen versión nueva: sirve también para ponerlas al día.

## Cómo se usa

Descarga el archivo de tu sistema desde la [**última versión**](../../releases/latest) y ábrelo. **Se
instala solo** y desde entonces lo tienes como cualquier otra aplicación: en el menú Inicio y el
escritorio en Windows, en Aplicaciones en macOS y en el menú de aplicaciones en Linux. El archivo
descargado ya no hace falta.

| Sistema | Archivo | Permisos |
|---|---|---|
| Windows 10/11 (x64) | `.exe` | Se instala como cualquier programa. Pide administrador **una vez** al abrirse; los instaladores de las aplicaciones ya no vuelven a preguntar. |
| macOS (Apple Silicon) | `.dmg` | Ábrelo y abre el programa desde dentro: se copia solo a Aplicaciones. Solo pide la contraseña si tu usuario no puede escribir allí. |
| Linux (x64) | `.AppImage` | Dale permiso de ejecución y ábrelo: se copia a `~/Applications` y al menú, sin pedir nada. Las aplicaciones también van ahí. |

Hace falta **conexión a internet**: la red de un pabellón de competición normalmente no la tiene, así
que se hace antes de montar los equipos.

En español, inglés, francés, alemán, ruso, chino y japonés: sale en el idioma del sistema y se cambia
arriba a la derecha.

Se **actualiza solo**: al abrirse comprueba si hay una versión más nueva de sí mismo y, si la hay, la
descarga y se abre ya actualizado. Quien tenga el programa de las primeras versiones, que no se
instalaba, no tiene que hacer nada: al abrirlo se actualiza y queda instalado (en Windows, además, el
`.exe` suelto desaparece).

> **macOS.** Como no está firmado con certificado de Apple, la primera vez macOS dirá que no puede
> comprobar el desarrollador: clic derecho sobre el programa ▸ **Abrir** ▸ **Abrir**.
>
> **Windows.** SmartScreen puede avisar de «editor desconocido»: **Más información ▸ Ejecutar de
> todas formas**.

## Soporte

¿Un fallo, una duda o una propuesta? Abre una [**incidencia**](../../issues/new) describiendo qué
ocurre, en qué sistema y con qué versión.

## Licencia

Software **de código propietario y uso gratuito**. Texto completo en **[LICENSE](LICENSE)**. La
**propiedad intelectual del programa es de Juan Cotolí San Félix**.

Las bibliotecas de terceros que incorpora se rigen por sus propias licencias, detalladas en
[TERCEROS.md](TERCEROS.md).

---

<div align="center">
<sub>Hecho para el tatami. 🥋</sub>
</div>
