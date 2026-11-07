# Componentes de terceros

Bibliotecas que JudoInstalador incorpora y bajo qué licencia. Todas son permisivas y compatibles con
la distribución de este proyecto en los términos de su [licencia](LICENSE): ninguna obliga a publicar
el programa como código abierto ni a permitir obras derivadas, y ninguna impone condiciones de uso.

---

## 1. Paquetes NuGet (`JudoInstalador.csproj`)

| Paquete | Versión | Licencia | Notas |
|---|---|---|---|
| Avalonia, Avalonia.Desktop, Avalonia.Themes.Fluent, Avalonia.Diagnostics | 11.3.6 | MIT | `Avalonia.Diagnostics` se excluye en Release |
| Avalonia.Fonts.Inter | 11.3.6 | MIT (paquete) · **SIL OFL 1.1** (tipografía Inter) | Redistribución libre; hay que conservar el aviso de copyright de la fuente |
| CommunityToolkit.Mvvm | 8.4.0 | MIT | |

## 2. Plataforma y herramientas

| Componente | Licencia | Cómo se usa |
|---|---|---|
| .NET 9 | MIT | Runtime incluido en los ejecutables autocontenidos |

## 3. Iconos

Los iconos de `Assets/Icons` son obra del titular del proyecto (el judogi y la caja salen de la
tipografía Apple Color Emoji al generarlos, ver `Empaquetado/iconos/`) y se rigen por la
[licencia](LICENSE) general.

## 4. Lo que descarga

JudoInstalador no incluye ninguna de las aplicaciones que instala: las descarga en el momento de sus
repositorios públicos de descargas, y cada una se rige por su propia licencia.
