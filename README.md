# WMO · Win11 Media Overlay

Una isla dinámica para Windows 11: muestra lo que suena, la letra en sincronía y los controles del reproductor en una píldora discreta en el borde superior de la pantalla.

**Página y descarga:** <https://wmo.lbuccella.com>

## Qué hay en este repositorio

Las versiones publicadas de WMO y sus notas. El instalador de cada versión está en [Releases](../../releases), como archivo MSI.

El código fuente no se publica acá.

## Versiones

La última versión está siempre en [Releases](../../releases/latest), con sus notas. La página de descarga apunta sola a la más nueva.

A partir de la 1.3.0 la app se actualiza desde Ajustes › General: avisa cuando hay una versión nueva, muestra las notas y verifica la firma del instalador antes de instalarlo.

## Comprobar una descarga

Cada versión muestra la huella SHA-256 del instalador, en Releases y debajo del botón de descarga de la página. Para compararla con el archivo que bajaste, en PowerShell:

```powershell
Get-FileHash .\WMO_x.y.z_x64.msi -Algorithm SHA256
```

Si la huella no coincide, no lo instales.

## Requisitos

Windows 11 de 64 bits.

## Problemas y sugerencias

Abrí un [issue](../../issues) contando qué pasó, con qué reproductor y qué versión de WMO tenés.
