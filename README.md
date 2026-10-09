# TicoLoft v1.0

Frontend comunitario para explorar fuentes que configura cada usuario y descargar contenido a las carpetas que utiliza Tico en Nintendo Switch con Atmosphère.

## Descarga e instalación

Descarga `TicoLoft v1.0.zip` desde los archivos del repositorio o la sección **Releases** y extrae su contenido en la raíz de la microSD. El ZIP ya contiene la ruta `switch/TicoLoft/`. Al terminar, la tarjeta tendrá esta estructura:

```text
sdmc:/switch/TicoLoft/TicoLoft.nro
sdmc:/switch/TicoLoft/archive_sources.json
sdmc:/switch/TicoLoft/settings.json
```

Abre Homebrew Menu en modo aplicación para disponer de memoria suficiente: mantén **R** mientras inicias un juego legítimo instalado y selecciona Homebrew Menu. Después ejecuta TicoLoft. Tico debe instalarse por separado.

En **Fuentes**, añade las colecciones que quieras usar o importa tu propio JSON. El paquete no configura fuentes automáticamente. En **Ajustes**, puedes añadir tu propia API key de SteamGridDB para las carátulas; sin clave o sin una coincidencia disponible, se muestra el indicador de carátula ausente.

Las descargas se guardan en `sdmc:/tico/roms/<sistema>/`, donde Tico busca las ROMs.

## Controles

- Cruceta o palanca: navegar; A: aceptar; B: volver.
- L/R: saltar 6 juegos; ZL/ZR: saltar 10.
- X: buscar; Y: favorito; −: cambiar pestaña; +: salir y guardar la cola.
- Pantalla táctil: controles, pestañas y deslizamiento por listas.

## Configuración y privacidad

`archive_sources.json` empieza con una lista vacía. `settings.json` no incluye API keys ni credenciales. Cada persona añade sus fuentes y, si lo desea, su clave de SteamGridDB en su propia consola. No compartas tus archivos de configuración después de guardar credenciales.

El ZIP solo contiene el ejecutable y estos dos archivos de configuración vacíos; no incluye juegos, BIOS, firmware, claves, carátulas, colecciones ni fuentes activas.

## Aviso de uso responsable

TicoLoft es una herramienta para gestionar fuentes configuradas por el usuario. **Úsala únicamente para descargar archivos que estés legalmente autorizado a obtener y utilizar.** Tener una copia de un juego no implica necesariamente que esté permitido descargar otra desde cualquier fuente. Cada persona es responsable de comprobar la legislación aplicable, los derechos sobre los archivos y las condiciones del servicio que utilice. No promovemos ni respaldamos la piratería, la infracción de derechos de autor ni el acceso no autorizado a contenido.

Archive.org, SteamGridDB, Nintendo, Atmosphère, Tico y Ticobro son proyectos o servicios independientes. TicoLoft no está afiliado ni respaldado por ellos. Este aviso es informativo y no constituye asesoría legal.
