# BetterTables

A plugin for Obsidian that makes native Markdown tables work like small Excel sheets: Excel-style A1
formulas, units, references between tables, number formats, dates, merged cells, row heights, a fill
handle and a table toolbar. Showing results never writes to your notes.

This repository holds the built plugin only: each [release](https://github.com/anyosag/bettertables/releases)
has its `main.js`, `manifest.json` and `styles.css`, and its notes say what changed.

## Install

1. Download `main.js`, `manifest.json` and `styles.css` from the
   [latest release](https://github.com/anyosag/bettertables/releases/latest).
2. In your vault, make the folder `.obsidian/plugins/bettertables` and put the three files in it.
3. Restart Obsidian, open Settings > Community plugins (turn Restricted mode off if it is on) and turn on
   BetterTables.

## Updates

From version 1.5.12, BetterTables updates itself: a few seconds after Obsidian starts it asks this
repository for its newest release, installs it if it is newer, restarts itself and says so. No other plugin
is needed. Settings > BetterTables > Update automatically turns this off, and Check for updates looks right
away. The version it replaces is kept in the plugin's `previous` folder.

## Network use

BetterTables connects to the internet only to look for and download its own updates, at api.github.com and
github.com for this repository. Nothing about you or your notes is sent.

## Licence

MIT, see [LICENSE](LICENSE). `main.js` bundles the libraries listed in
[THIRD-PARTY-NOTICES.md](THIRD-PARTY-NOTICES.md), each under its own licence.

Not the same plugin as "Better Tables" (`better-tables`) in Obsidian's plugin directory; the two are
unrelated.
