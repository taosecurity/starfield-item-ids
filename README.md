# Starfield Item IDs

This page is a searchable list of the Form IDs of every item you can spawn with the Starfield console. It was read from the official game files (game version 1.16.244.0): the base game, Shattered Space, Terran Armada, Free Lanes, Trackers Alliance and Watchtower.

**View it here:** https://taosecurity.github.io/starfield-item-ids/

## Example

1. Open the page and type `7.77` in the search box.
2. The Ammo group shows **7.77mm Caseless**, with the Form ID `0004AD3E` and the Editor ID `Ammo777mm`.
3. Type `100` in the Count box, then click the command `player.additem 0004AD3E 100` to copy it.
4. In the game, press ~ (PC only), paste the command and press Enter.

You get 100 rounds of 7.77mm Caseless ammo.

## Using the console

On PC, press the **~** key (the key under Esc) to open the console, type or paste the command, and press Enter. Xbox and PlayStation have no console. Using the console turns off achievements for that save unless you use a mod that keeps them on.

## What's on the page

- The page lists 6,019 items in 14 groups: weapons, spacesuits, helmets, boost packs, apparel, ammo, aid, food and drink, resources, misc items and valuables, books and slates, keys, weapon mods and armor mods. Each group lists the main game first, then each add-on.
- You can click an ID or a ready-made command (`player.additem <ID>`, or `amod <ID>` for mods) to copy it. A Count box adds a quantity to every command.
- Add-on IDs depend on load order. The page starts from the game's built-in order, and you can set each add-on's prefix to match your own game; the page explains how.
- You can search by name, Form ID or Editor ID, and filter by where an item comes from.

What's new: see the top of the [live page](https://taosecurity.github.io/starfield-item-ids/).

## Words used here

- **Console:** the PC command line inside the game, opened with ~.
- **Plugin:** a mod's data file (`.esm`, `.esp` or `.esl`). It adds or changes records in the game. Each add-on is a plugin too.
- **Record:** one thing in a plugin, such as a weapon, a quest, a location or a setting.
- **Form ID:** a record's number, such as `0004AD3E`. The first two digits depend on the load order.
- **Editor ID:** a record's readable name, such as `Ammo777mm`, used by the Creation Kit and xEdit.
- **Load order:** the order the game loads plugins in. When two plugins change the same record, the one loaded later wins.
- **Load order prefix:** the first digits of a Form ID, which say which plugin the item comes from. Base game items start with `00`. A full add-on gets two digits, such as `01`, and a medium one such as Trackers Alliance gets `FD` plus two digits. The number depends on where the add-on loads in your game.

## How it was made

- The items were read from the official game files, game version 1.16.244.0.
- The list leaves out records the game marks as not playable, ship weapons and ammo, creature attacks and skins, test and cut records, and companion- or enemy-only weapon copies.
- The IDs were not tried in the game one by one. Base game and Shattered Space IDs were spot-checked against other published lists.
- The list is regenerated after game updates.

## Found a mistake?

Open an issue: https://github.com/taosecurity/starfield-item-ids/issues

## Credits and license

Richard Bejtlich of [Richard Presents Starfield Essentials](https://www.youtube.com/@RichardBejtlich) made this page. More Starfield tools and references are on the [Richard Presents Development Hub](https://taosecurity.github.io/).

This is an unofficial list, not made or endorsed by Bethesda. Starfield is a trademark of ZeniMax Media. Item names are the game's own.

The page is a single self-contained `index.html` with no external dependencies. Its code (layout, search, copy and load-order features) is under the MIT license; see [LICENSE](LICENSE).
