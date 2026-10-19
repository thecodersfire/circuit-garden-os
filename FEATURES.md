# Built-in features for circuit-garden-os

Purpose: electronics design

1. **prepare a creative project** — run circuit-garden-os-workspace. It creates ~/Documents/circuit-garden-os-workspace/ with Briefs, Working Files, Exports folders.
2. **plan a production session** — run circuit-garden-os-plan to open a purpose-specific Markdown plan, saved under ~/Documents/circuit-garden-os-session-plans/.
3. **check project and export readiness** — run circuit-garden-os-check for an interactive checklist. Answers are not saved or transmitted.

These local tools create folders, open a local note, or display prompts. They do not install packages, change system settings, or send data.

Install them from this repository:

    mkdir -p "$HOME/.local/bin"
    install -m 0755 features/circuit-garden-os-workspace features/circuit-garden-os-plan features/circuit-garden-os-check "$HOME/.local/bin/"

## Preinstalled purpose software

The installer adds these three Flathub applications for electronics design:

1. **GNOME Builder** — org.gnome.Builder
2. **Wireshark** — org.wireshark.Wireshark
3. **Arduino IDE 2** — cc.arduino.IDE2

They are installed from Flathub during setup. The repository contains application IDs and documentation, not third-party binaries; each publisher’s terms and licenses apply.

## Ten more purpose-specific preinstalled applications

The setup installs these ten Flathub apps selected for electronics design:

1. **FreeCAD** — design mechanical parts (org.freecadweb.FreeCAD)
2. **OpenSCAD** — model parametric 3D parts in code (org.openscad.OpenSCAD)
3. **Blender** — create 3D assets and animations (org.blender.Blender)
4. **PrusaSlicer** — prepare models for 3D printing (com.prusa3d.PrusaSlicer)
5. **DB Browser for SQLite** — inspect SQLite databases (org.sqlitebrowser.sqlitebrowser)
6. **GNOME Boxes** — test workflows in virtual machines (org.gnome.Boxes)
7. **GNOME Calculator** — perform scientific and financial calculations (org.gnome.Calculator)
8. **GNOME Text Editor** — edit plain-text notes and configuration files (org.gnome.TextEditor)
9. **GNOME Logs** — inspect logs during troubleshooting (org.gnome.Logs)
10. **Disk Usage Analyzer** — find large files and manage storage (org.gnome.baobab)

Flathub distributes the app packages. Check each publisher license and terms. This repository contains app IDs and documentation, not third-party binaries.
