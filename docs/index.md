---
icon: lucide/book-open-text
---

# Introduction

**Reflex Modding** — The ultimate modding guide and documentation for `MX vs ATV Reflex`.

Find out here how to change textures, game parameters, localization strings, sounds, create tracks, and edit the UI logic.

!!! warning "Important: Backup your files"
    Before making any changes, always create backup copies of the original `.package` archives (along with the corresponding `.database`), `.bxml`, and `.fpack` files, or the entire game folder. If a file is damaged, it can be easily restored.

## Modding Tools

All modding workflows are based on these utilities:

* **Reflex Package Tool** — A tool for extracting resources from `.package` archives. It allows you to extract textures, localization resources, sounds, and configurations.
[:octicons-mark-github-16: Download](https://github.com/daniilkorochansky/reflex-package-tool/releases){ .md-button .md-button--small target="_blank" }
* **Reflex BXML Editor** — A specialized editor for reading and modifying game parameters encrypted in the binary `BXML` format. It is used to tweak vehicle physics and game settings.
[:octicons-mark-github-16: Download](https://github.com/daniilkorochansky/reflex-bxml-editor/releases){ .md-button .md-button--small target="_blank" }
* **Reflex Font Package Viewer** — A tool for viewing, extracting, and replacing jersey font characters in the `data.fpack` file.
[:octicons-mark-github-16: Download](https://github.com/daniilkorochansky/reflex-font-package-viewer/releases){ .md-button .md-button--small target="_blank" }
* **Digital Earthworks** — The track editor used to create custom tracks and place 3D environment objects.  
<!-- [:octicons-link-external-16: Learn more](tracks/intro.md){ .md-button .md-button--small } -->
<!--
## Quick Start

Follow these steps to create your very first mod:

1. Navigate to **Tools → Reflex Package Tool** and learn how to work with `.package` files.
2. Locate the configuration files you want to edit within the extracted folder.
3. Open them using **Reflex BXML Editor** and make your tweaks (e.g., modifying bike suspension parameters).
4. Pack the files back into the archive and launch the game to test your changes.
-->
---

## How to Edit This Documentation

This documentation is fully open-source. If you found a typo, want to update outdated info, or want to share a completely new game modding guide, you can do it in just a few minutes:

### Quick Fixes (Typos, broken links)
* If you spot an error, click the **Pencil icon** in the top right corner of any page.
* You will be taken directly to the GitHub web editor. Make your changes in the browser and hit **Commit changes** to submit a **Pull Request**.

*Or create an `Issue` in the repository.*
[:octicons-mark-github-16: Create Issue](https://github.com/daniilkorochansky/reflex-modding/issues){ .md-button .md-button--small target="_blank" }

### New Guides or Major Content Updates
* **Fork** documentation repository.
* Create a new `.md` file inside the appropriate folder (`tools/`, `game-files/`, etc.).
* Don't forget to open the `zensical.toml` file in the root and register your new page under the `nav` list.
* Submit a **Pull Request** to our `main` branch.

Once your Pull Request is approved, a **GitHub Actions** workflow will automatically rebuild the site.