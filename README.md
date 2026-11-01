# Wands & Wizards for Foundry VTT

A [Foundry VTT](https://foundryvtt.com) module that brings **Wands & Wizards**, the Harry Potter adaptation for D&D 5e (2014 rules) by u/Murphen44 and its community ([r/WandsAndWizards](https://www.reddit.com/r/WandsAndWizards/)), to the **dnd5e** system. It is made with the author's permission.

What you get: the 10 houses, the 3 Casting Styles and the 6 Schools of Magic with dnd5e's own advancement from level 1 to 20, backgrounds, feats, starting equipment, pets and the Diagon Alley assistant; the 144 spells with their automation, lethality, Dedication, wands and corruption; the 69 potions with their qualities, ingredients and brewing; a wizard sheet, chat cards and an interface theme of its own; English and Spanish.

*En español más abajo.*

## Install

In Foundry, go to **Add-on Modules → Install Module**, paste this **Manifest URL** and click **Install**:

```
https://github.com/ShailAlis/wands-and-wizards/releases/latest/download/module.json
```

Then enable **Wands & Wizards** in your world. On first load it offers to switch dnd5e to the 2014 rules if your world is not on them yet.

## Requirements

| Package | Version |
|---|---|
| Foundry VTT | 14.369 or later (v14) |
| dnd5e | 6.0.6 or later (6.x), with the 2014 (legacy) rules |
| Midi-QOL | 14.6.4 or later, **`dnd6` branch** |
| DAE | 14.6.3 or later, **`dnd6` branch** |
| socketlib, lib-wrapper | from Foundry's package listing |
| Babele | 2.9.1 or later (only for Spanish) |

> Foundry's package listing installs the `v14` branch of Midi-QOL and DAE, which only works with dnd5e 5.x. For dnd5e 6, install them from these manifest URLs, **DAE first**:
> - DAE: `https://gitlab.com/tposney/dae/raw/dnd6/package/module.json`
> - Midi-QOL: `https://gitlab.com/tposney/midi-qol/raw/dnd6/package/module.json`

## Updating

Foundry tells you when a new version is out (**Add-on Modules → Check for Updates**). Each release lists what changed.

- Changes to your world's data are migrated automatically when the GM opens the world.
- **Items already on character sheets are not updated.** dnd5e copies each item onto the character, so a fix to a spell, potion or feature in the compendiums only reaches what you drag in again. If a release fixes something your table already has, delete it from the sheet and drag it again from the compendium.

## Reporting a bug

Open an issue in [this repository](https://github.com/ShailAlis/wands-and-wizards/issues/new/choose) with the module, Foundry, dnd5e and Midi-QOL versions, and what you expected to happen.

## Credits and legal

- Wands & Wizards is the work of u/Murphen44 and its community, used here with the author's permission.
- The module's code is under the MIT License; the game content is not (see [LICENSE](LICENSE)).
- Icons from [game-icons.net](https://game-icons.net) (CC BY 3.0) and fonts under the SIL Open Font License 1.1; full credits in the module's `CREDITS.md`.

This is unofficial Fan Content permitted under the Fan Content Policy. Not approved/endorsed by Wizards. Portions of the materials used are property of Wizards of the Coast. ©Wizards of the Coast LLC. Not approved or endorsed by J.K. Rowling or Warner Bros. Entertainment.

---

## En español

Módulo de Foundry VTT que adapta **Wands & Wizards**, la adaptación de Harry Potter para D&D 5e (reglas de 2014) de u/Murphen44 y su comunidad, al sistema **dnd5e**. Está hecho con permiso del autor y trae la interfaz y el contenido en inglés y en español (para el español hace falta Babele).

- **Instalación:** en Foundry, *Módulos → Instalar módulo*, pega la URL de manifiesto de arriba y pulsa *Instalar*. Al abrir el mundo, el módulo ofrece pasar dnd5e a las reglas de 2014 si aún no lo están.
- **Requisitos:** los de la tabla de arriba. Midi-QOL y DAE tienen que ser de la rama `dnd6`: instálalos con los dos manifiestos de arriba, DAE primero.
- **Actualizar:** Foundry avisa de cada versión nueva. Los cambios en los datos del mundo se migran solos al entrar el GM, pero los objetos que ya están en las fichas no cambian: para recoger una corrección, bórralo de la ficha y vuelve a arrastrarlo desde el compendio.
- **Fallos:** abre una issue en este repositorio con las versiones del módulo, de Foundry, de dnd5e y de Midi-QOL.
