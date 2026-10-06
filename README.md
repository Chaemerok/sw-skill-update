# sw-skill-update

**Español** · [English](#english)

Datos de habilidades de Summoners War revisados a mano para **SW RTA Optimizer**, una aplicación de escritorio que
ayuda a elegir y runar monstruos para el PvP. La app los descarga de aquí para tenerlos al día sin esperar a una
versión nueva.

## Qué hay

| Archivo | Contenido |
| --- | --- |
| `manifest.json` | Versión y fecha de los datos, cuántas fichas y correcciones hay, la huella SHA-256 de cada archivo y los cambios de la última versión |
| `passives.json` | Fichas de habilidades pasivas: cuándo se activa cada efecto, con qué condición y qué hace |
| `skill-fixes.json` | Correcciones de efectos que los datos de origen tienen mal etiquetados (una cantidad guardada como probabilidad, un nombre o un destinatario equivocados) |
| `CHANGELOG.md` | Qué ha cambiado en cada versión de los datos |

## De dónde salen

Los textos y efectos de partida son los de [SWARFARM](https://swarfarm.com). Cada ficha y cada corrección se revisa a
mano antes de publicarse. Cada entrada guarda la huella de la habilidad tal como estaba al revisarla: si un parche del
juego la cambia, la app deja de usar esa entrada hasta que se revise otra vez.

Este repositorio **no contiene datos de ninguna cuenta** de jugador.

## Licencia

[CC BY 4.0](LICENSE): puedes usar y adaptar estos datos citando la fuente. Summoners War es una marca de Com2uS; este
proyecto no está relacionado con Com2uS ni con SWARFARM.

---

## English

Hand-reviewed Summoners War skill data for **SW RTA Optimizer**, a desktop app that helps pick and rune monsters for
PvP. The app downloads it from here to stay up to date without waiting for a new release.

### Contents

| File | What it holds |
| --- | --- |
| `manifest.json` | Data version and date, how many sheets and fixes there are, the SHA-256 of each file and the changes in the latest version |
| `passives.json` | Passive-skill sheets: when each effect triggers, under which condition and what it does |
| `skill-fixes.json` | Fixes for effects the source data labels wrongly (an amount stored as a chance, a wrong name or target) |
| `CHANGELOG.md` | What changed in each data version |

### Where it comes from

The starting texts and effects come from [SWARFARM](https://swarfarm.com). Every sheet and fix is reviewed by hand
before it's published. Each entry stores a fingerprint of the skill as it was when reviewed: if a game patch changes
the skill, the app stops using that entry until it's reviewed again.

This repository holds **no player account data**.

### License

[CC BY 4.0](LICENSE): you may use and adapt this data with attribution. Summoners War is a trademark of Com2uS; this
project isn't affiliated with Com2uS or SWARFARM.
