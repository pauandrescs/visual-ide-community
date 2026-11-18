# Visual IDE community starter kit

Templates and themes for [Visual IDE](https://github.com/pauandrescs/visual-ide), the visual builder for
native Android apps by ARK PLATFORMS. This repository is also an example of how to share your own.

## Use it

1. In Visual IDE, open **Tools > Community**.
2. Type `pauandrescs/visual-ide-community` and press **Load catalogue**.
3. Press **Install** next to what you want.

Templates appear in **File > New Project**. Themes appear among the ready-made themes of a project.

## What is here

| Kind | Name | Description |
| --- | --- | --- |
| Template | Coffee Shop | Three screens with navigation, a validated sign-in form and a saved order counter. |
| Template | Component Gallery | Two screens showing every ready-to-use component. |
| Theme | Ocean Blue | Blue primary colour, cool backgrounds. |
| Theme | Sunset | Warm orange primary colour. |
| Theme | Forest | Green primary colour. |

## Share your own

1. Export a project with **Tools > Export Project as Template** (`.vidtemplate`), or a theme from a project's
   Theme panel (`.vidtheme`). Plugins are zip files with `plugin.json` at their root.
2. Put the files in a folder — `templates/`, `themes/` and `plugins/` keep it tidy.
3. In **Tools > Community** press **Build catalogue file** and choose the folder. Visual IDE writes
   `visual-ide.json` with the size and SHA-256 fingerprint of every package.
4. Push the folder to a GitHub repository. Make it public for everyone, or private and give access to the
   people who should use it (they add an access token in the Community window).

Run **Build catalogue file** again whenever a package changes: Visual IDE refuses downloads that do not match
the fingerprint in the catalogue.

## Safety

Templates and themes are data only; nothing in them is executed. Plugins stay switched off until the person
installing them approves them.
