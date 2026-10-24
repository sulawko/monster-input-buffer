<p align="center">
  <img src="apple-touch-icon.png" width="96" alt="Monster Input Buffer">
</p>

<h1 align="center">Monster Input Buffer</h1>

<p align="center">
  Mod de <b>Geode</b> para Geometry Dash 2.208 que corrige tus clicks "por las dudas".<br>
  Hecho por <b>SuLawko</b>.
</p>

<p align="center">
  <a href="https://github.com/sulawko/monster-input-buffer/releases/latest"><b>⬇ Descargar</b></a> ·
  <a href="https://sulawko.github.io/monster-input-buffer/">Web</a> ·
  <a href="https://discord.gg/dsYchZdGvf">Discord</a>
</p>

---

## ¿Qué hace?

Simula tu click unos ticks hacia adelante con dos jugadores "fantasma" invisibles. Si clickear ahora te mata, pero un click apenas más tarde sobrevive, tu input se retrasa y se entrega en el tick correcto. Es una ayuda potente pero no exagerada (1 tick = 0.25 frames a 60 fps).

- Cubo, bola, ufo, spider, robot, swing y wave (clicks y soltadas). La nave no se toca.
- Orbes, pads, portales de gravedad y de velocidad también se simulan.
- El spam rápido de wave se deja intacto.

## Instalación

1. Instalá [Geode](https://geode-sdk.org) (versión 5.11.2 o más nueva) en Geometry Dash 2.2081, Windows.
2. Descargá `sulawko.monster-input-buffer.geode` desde la [última release](https://github.com/sulawko/monster-input-buffer/releases/latest).
3. Copialo a la carpeta `geode/mods` del juego (o arrastralo sobre el juego) y reiniciá.

## Uso

| Tecla | Acción |
| --- | --- |
| **F6** | Cambia la intensidad: 0.5f → 1f → 2f → 4f → 6f → 8f → custom → apagado |
| **K** | Muestra / oculta el panel de log en el nivel |

Al abrir el juego también se abre una consola con el mismo log. Cada vez que el mod te salva un click, lo anota (por ejemplo `SAVED press +3t`). Los ajustes (delay custom, tiempo de predicción, etc.) están en la configuración del mod dentro de Geode.

## Importante

Este mod cambia el timing de tus inputs: las completaciones hechas con él pueden no valer como legítimas en listas o rankings. Usalo bajo tu propia responsabilidad.

Mod no oficial, no afiliado a RobTop Games ni al equipo de Geode.

---

<sub>Este repositorio contiene la página web del mod y sus descargas (Releases). Para actualizar la descarga, editar el bloque `CONFIG` de `index.html` (`DOWNLOAD_URL`, `SHA256`, `YOUTUBE_ID`).</sub>
