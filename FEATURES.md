# Built-in features for wildframe-os

Purpose: wildlife and nature photography, RAW image development, and photo editing

1. **prepare a creative project** — run wildframe-os-workspace. It creates ~/Documents/wildframe-os-workspace/ with Briefs, Working Files, Exports folders.
2. **plan a production session** — run wildframe-os-plan to open a purpose-specific Markdown plan, saved under ~/Documents/wildframe-os-session-plans/.
3. **check project and export readiness** — run wildframe-os-check for an interactive checklist. Answers are not saved or transmitted.

These local tools create folders, open a local note, or display prompts. They do not install packages, change system settings, or send data.

Install them from this repository:

    mkdir -p "$HOME/.local/bin"
    install -m 0755 features/wildframe-os-workspace features/wildframe-os-plan features/wildframe-os-check "$HOME/.local/bin/"

## Preinstalled purpose software

The installer adds these three Flathub applications for wildlife and nature photography, RAW image development, and photo editing:

1. **QGIS** — org.qgis.qgis
2. **GNOME Maps** — org.gnome.Maps
3. **LibreOffice** — org.libreoffice.LibreOffice

They are installed from Flathub during setup. The repository contains application IDs and documentation, not third-party binaries; each publisher’s terms and licenses apply.

## Ten more purpose-specific preinstalled applications

The setup installs these ten Flathub apps selected for wildlife and nature photography, RAW image development, and photo editing:

1. **GNOME Weather** — check local weather conditions (org.gnome.Weather)
2. **Zotero** — manage research sources and citations (org.zotero.Zotero)
3. **GNOME Calendar** — schedule sessions, deadlines, and events (org.gnome.Calendar)
4. **GNOME Clocks** — time work sessions and events (org.gnome.clocks)
5. **GNOME Contacts** — organize partner and team contacts (org.gnome.Contacts)
6. **Document Scanner** — digitize paper notes and forms (org.gnome.SimpleScan)
7. **GNOME Papers** — read project and reference PDFs (org.gnome.Papers)
8. **GNOME Boxes** — test workflows in virtual machines (org.gnome.Boxes)
9. **GNOME Text Editor** — edit plain-text notes and configuration files (org.gnome.TextEditor)
10. **GNOME Calculator** — perform scientific and financial calculations (org.gnome.Calculator)

Flathub distributes the app packages. Check each publisher license and terms. This repository contains app IDs and documentation, not third-party binaries.

## Fifteen more purpose-specific preinstalled applications

These applications add tools suited to this setup focus. They are installed from Flathub by the setup scripts.

1. **RawTherapee** (com.rawtherapee.RawTherapee) — develop RAW photo files with tone and color controls.
2. **digiKam** (org.kde.digikam) — catalog, tag, and batch-process large photo collections.
3. **Shotwell** (org.gnome.Shotwell) — import, sort, and make quick edits to photo libraries.
4. **Pixelorama** (com.orama_interactive.Pixelorama) — draw pixel-art sprites and frame-based animations.
5. **Synfig Studio** (org.synfig.SynfigStudio) — create vector-based 2D animations.
6. **OpenToonz** (io.github.OpenToonz) — produce hand-drawn and cutout 2D animation.
7. **LibreCAD** (org.librecad.librecad) — draft precise 2D technical drawings.
8. **QElectroTech** (org.qelectrotech.QElectroTech) — draw electrical schematics and wiring diagrams.
9. **Thunderbird** (org.mozilla.Thunderbird) — manage email and communication accounts.
10. **Inkscape** (org.inkscape.Inkscape) — create vector illustrations and diagrams.
11. **Blender** (org.blender.Blender) — create 3D assets and animations.
12. **Disk Usage Analyzer** (org.gnome.baobab) — find large files and manage storage.
13. **GNOME Logs** (org.gnome.Logs) — inspect logs during troubleshooting.
14. **Flatseal** (com.github.tchx84.Flatseal) — review Flatpak app permissions.
15. **Kdenlive** (org.kde.kdenlive) — edit video timelines.

Emulator frontends do not include game ROMs or copyrighted game files; supply only files you are legally allowed to use.

## Fifteen further purpose-specific preinstalled applications

This second batch adds another set of apps selected for this setup’s purpose. They are installed from Flathub by the setup scripts.

1. **Gwenview** (org.kde.gwenview) — review image sets and make quick crop, resize, and annotation edits.
2. **KGeoTag** (org.kde.kgeotag) — add GPS coordinates to photos from a GPX track or map.
3. **Kamoso** (org.kde.kamoso) — capture webcam photos and short video clips.
4. **KolourPaint** (org.kde.kolourpaint) — make quick raster sketches, labels, and simple image edits.
5. **Rnote** (com.github.flxzt.rnote) — sketch diagrams, write by hand, and annotate pictures or documents.
6. **Okular** (org.kde.okular) — read, bookmark, and annotate technical drawings, reading lists, and reference PDFs.
7. **Dolphin** (org.kde.dolphin) — organize project assets and inspect folders.
8. **Ark** (org.kde.ark) — open and create common project archive files.
9. **Filelight** (org.kde.filelight) — find large folders and reclaim disk space.
10. **Warehouse** (io.github.flattool.Warehouse) — review installed Flatpaks, manage versions, and clean app data.
11. **KCalc** (org.kde.kcalc) — run scientific and unit calculations for coursework or technical work.
12. **Meld** (org.gnome.meld) — compare and merge source files, folders, and Git changes.
13. **Marble** (org.kde.marble) — explore maps and a virtual globe for geographic context.
14. **KStars** (org.kde.kstars) — plan sky observations and explore astronomy simulations.
15. **Konsole** (org.kde.konsole) — run shell commands and inspect development or system tasks.

Game frontends do not include proprietary game data; add only games or files you are allowed to use.
