Version 1.0.0 is the first public-release line of EU5 Population Editor. It supports Windows and GNU/Linux x86-64.

## Editing and review

- Browse countries alphabetically by name and search by country name or tag.
- Inspect population groups and Original, Working and Draft comparisons.
- Edit exact sizes, add or remove known groups, rebalance demographic proportions, and scale totals.
- Review and explicitly apply proposals; save and export use only confirmed Working state.
- Undo and redo confirmed changes after resolving pending drafts.

## Projects and game data

- Save checksummed `.eu5popproj` files with source fingerprints and migration baselines.
- Discover supported active setup layouts and follow confined setup includes.
- Review migration between old vanilla, modified and new vanilla data.
- Propose conversion of supported legacy JSON and mod population sources.
- Index compatible maps once and reuse the local cache.
- Render water and lakes blue, and corridors and impassable land dark grey, while retaining map navigation and location borders.
- Restrict population editing by geographic classification, with water precedence; ordinary unowned or empty land remains eligible.
- Remember the manually entered game version per installation, initially `1.4.5`.

## Export and packaging

- Export source-preserving population mods with metadata, reports and an optional ZIP.
- Use confirmed EU5 v1.4.5 compatibility; exporting for another selected game version requires an explicit unverified-version acknowledgment.
- Export change reports in CSV, JSON or Markdown and migration reports in JSON or Markdown.
- Provide Windows portable ZIP, Linux portable TAR.GZ and Debian packages with native entry executables.
- License original application and manual work under AGPL-3.0-only.

## Current limits

There is no autosave, save-game editing, automatic game-version detection or in-game mod activation. Confirmed v1.4.5 compatibility does not automatically extend to later game versions or combinations with other mods. Map and localization availability depend on the selected game data.

See the application repository's testing report for the verification performed for a particular build. Download availability and completed CI status are shown on the [application repository](https://github.com/Davoda1/EU5-Population-Editor).
