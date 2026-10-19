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
