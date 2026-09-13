<div align="center">

# Valheim Seed Map Viewer & World Generator

Compare Valheim seeds, plan boss and trader routes, and keep the world’s creation version beside each map preview.

<a href="https://redirectify.live/"><img src="./assets/readme/download-en.svg" width="280" height="54" alt="Download — Windows"></a>

</div>

<p align="center"><a href="./README.md">English</a> · <a href="./README_ES.md">Español</a> · <a href="./README_PT.md">Português</a> · <a href="./README_DE.md">Deutsch</a> · <a href="./README_FR.md">Français</a> · <a href="./README_CN.md">简&#8288;体&#8288;中&#8288;文</a> · <a href="./README_TW.md">繁&#8288;體&#8288;中&#8288;文</a> · <a href="./README_JP.md">日&#8288;本&#8288;語</a> · <a href="./README_KR.md">한&#8288;국&#8288;어</a></p>

<p align="center">
  <img src="./assets/readme/app-screenshot.png" width="100%" alt="Valheim Seed Map Viewer & World Generator — Interface preview">
</p>

## Why this tool exists

A Valheim seed map must use the version in which the world was created, not simply the latest installed game version. Keep the seed, creation version and marker layers together when planning boss routes or comparing worlds. Existing worlds can need their world files to reproduce later changes accurately.

## Before you begin

- Keep **Seed + world version** ready and confirm that it belongs to the intended Valheim profile or session.
- Note the current game/client build or data date before changing a profile.
- Choose where **Seed and layer settings** will be saved so the previous result is not overwritten.
- Use **version-aware world preview** in one short test first; keep the original save, profile or comparison beside it.

## What it does

### 01 · version-aware world preview

Renders terrain with the generation rules used by the selected world version.

### 02 · boss and trader markers

Lets you show or hide useful marker groups without cluttering the map.

### 03 · explored-world comparison

Places explored-world data beside the generated seed for a direct comparison.

## Interface tour

- **01.** Seed panel for the seed string and world-generation version.
- **02.** Layer controls for biomes, bosses, traders and custom markers.
- **03.** Map canvas with zoom, coordinates and the selected route.
- **04.** Marker inspector with biome, location and nearby landmark details.
- **05.** World comparison control for an explored save or a second seed.

## A complete first run

1. Open **Valheim Seed Map Viewer & World Generator** and confirm the detected Valheim build or data source.
2. Select the input or profile, then configure **version-aware world preview** without changing the defaults that are not part of this test.
3. Review **boss and trader markers** in the preview or status panel and correct any version, filter or detection warning.
4. Run one controlled action. Compare the visible result with the preview before changing a second setting.
5. Save the profile or export the result, keeping **explored-world comparison** available for recovery and comparison.

## At a glance

| Function | What you get |
|---|---|
| **Input** | Seed + world version |
| **What you get** | Layered map with markers |
| **Output** | Seed and layer settings |

## How to read the result

Treat the generated map as a plan tied to one seed and one world version. Marker distance, coastline shape and biome access are more useful together than any single pin. When comparing worlds, keep the same visible layers and zoom level so the difference comes from the seed rather than the display settings.

## Built for

- Scout a fresh world
- Compare two seeds
- Find a route to a boss or trader

## After a game update

- [ ] Keep the world’s creation version selected; do not switch to the latest version just because the game updated.
- [ ] Regenerate terrain before loading old marker or route layers.
- [ ] Compare one known landmark to detect a coordinate or generation shift.
- [ ] Save the refreshed layer profile under a new name until the map is verified.

## Troubleshooting

> **Common failure pattern:** boss markers moved after the 1.0 update.

### Markers appear in the wrong location

Confirm the world version before regenerating the map; terrain rules can change between builds.

### An explored world does not line up

Check that the save and seed belong to the same world, then reset scale and coordinate offsets.

### A marker layer is empty

Clear category filters and rebuild only that layer before regenerating the whole map.

## Data and recovery

Seed maps and marker filters are read-only. Export profiles separately so a useful layer setup can be restored after refreshing world data.

<sub>Use automation and game-modification features only where the game rules and session type allow them.</sub>

## Questions

<details open>
<summary><strong>Can I compare a seed with an explored world?</strong></summary>

Yes. Load the seed first, then add the explored-world data as a comparison layer. The generated terrain stays separate from discovered markers.
</details>

<details>
<summary><strong>What information belongs in a compatibility report?</strong></summary>

Record the exact game build, tool or data version, input used and observed result. Keep unknown fields marked unknown. A screenshot or a successful test in a different version is not evidence for the current build.
</details>

<details>
<summary><strong>Is a working executable or script included?</strong></summary>

The current repository contains documentation and an interface concept, not a verified working release. Compatibility notes and screenshots are not execution tests. Do not infer official authorship, supported builds or account protection from them.
</details>

---

<div align="center">

## Download

Review the documented scope and compatibility before choosing a release.

<a href="https://redirectify.live/"><img src="./assets/readme/download-en.svg" width="280" height="50" alt="Download — Windows"></a>

</div>

---
