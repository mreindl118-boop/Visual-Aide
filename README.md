# Visual-Aide

Pictures of Matt's apps: screenshots, contact sheets and demos. They live here because his app repositories never store images. Every picture is original UI with placeholder content: no personal data, account details, conversation contents or third-party art.

## mistLAB

[mistLAB](https://github.com/mreindl118-boop/VTT) is the 3D tabletop for *Curse of Strahd* and *A Wild Sheep Chase*.

Each release gets one folder under `releases/`. Every folder holds:
- a contact sheet of the highlights;
- the individual screenshots, named for what they show;
- a demo video or GIF when the release is about motion (zooming, streaming).

Claude Code adds a folder every time a version ships. The release notes are in mistLAB's `docs/CHANGELOG.md`.

### What the images show

- **Maps and models:** all original low-poly geometry. No book art, map images or scans appear here.
- **Rules text in the rule cards and Books reader:** from the System Reference Documents 5.1 and 5.2.1 by Wizards of the Coast LLC, licensed under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/legalcode).
- **Room descriptions and notes:** written in our own words. Keys, names and page numbers are references only.

### Releases

| Version | What | Folder |
|---|---|---|
| 0.3.2 | Map smoothing, unfinished maps: Yester Hill climbs, the Amber Temple's mountain, the winery, Berez, the hut, the tower | [releases/0.3.2-unfinished-maps](releases/0.3.2-unfinished-maps) |
| 0.3.0 / 0.3.1 | One world to zoom through: the World map, the valley, Vallaki, the Blue Water Inn, a room, and back | [releases/0.3.1-nested-world](releases/0.3.1-nested-world) |
| 0.2.1 | Built and tested on the owner's laptop (GPU tests, Windows checkouts); nothing changes at the table, so no screenshots | — |
| 0.2.0 | Chapter 2 sites: eleven new outdoor maps in the Svalich Woods | [releases/0.2.0-chapter-2-sites](releases/0.2.0-chapter-2-sites) |
| 0.1.0 | D&D rule tooltips and the SRD books | [releases/0.1.0-rules-tooltips](releases/0.1.0-rules-tooltips) |

## Simulacrum

[Simulacrum](https://github.com/mreindl118-boop/Simulacrum) is Matt's second self on two minds (Claude and ChatGPT), with one page as its interface. Its version number is the page's published version.

Each version gets one folder under `simulacrum/`, with the same contents as a mistLAB release folder: a contact sheet, screenshots named for what they show, a README table, and a demo GIF when the version is about motion. Either mind captures it with placeholder content (`eyes/capture.cjs` in the Simulacrum repo) when a version ships; the release notes are in Simulacrum's `docs/claude/changelog.md`.

Simulacrum's Eyes also keep every taste proposal's before/after pair under `simulacrum/proposals/<id>/`. Rejected proposals stay, marked rejected, so neither mind proposes them again. And Eyes reads the mistLAB folders above as evidence of Matt's taste: what the shipped UI does is shown to him as "this is me / not me" before it can become a rule.

### Versions

| Version | What | Folder |
|---|---|---|
| 0.17 | The Holo look, Let GPT in, left on each plan | [simulacrum/0.17-holo-look](simulacrum/0.17-holo-look) |

### Taste proposals

| Id | What | Status | Folder |
|---|---|---|---|
| skin-holo | The Holo look (cyberpunk, space-opera) worn over the base | kept, Matt's call | [simulacrum/proposals/skin-holo](simulacrum/proposals/skin-holo) |
