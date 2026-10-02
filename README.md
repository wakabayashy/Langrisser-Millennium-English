# Langrisser Millennium — English Translation

An English translation project for **Langrisser Millennium** on the **Sega Dreamcast**.

> **Current status: Beta 1 — Build 62**

This is an **AI-assisted translation project**.

The project has reached public beta testing. A large amount of the game has been translated and integrated, but the entire game has not yet been completed from beginning to end with the English build.

The goal of the Beta is to find remaining untranslated content, translation problems, graphical issues and technical bugs through real gameplay testing.

---

## Current Status

**Beta 1 / Build 62**

Basic testing has been completed for:

- Game boot
- Modified English opening
- Hero selection and confirmation
- Character creation
- Beginning of the game
- Strategic map
- Character information
- Menus
- Dialogue
- Battles
- Sword Art / formation interfaces

A complete English playthrough has **not yet been performed**.

For that reason, Beta 1 should not be considered a final or 100% complete translation.

---

## What's Translated?

Work has been done on:

- Story and event dialogue
- System text
- Menus
- Character creation
- Character information
- Tutorials and help pages
- Battle text
- Units and bases
- Recruitment
- Character and location names
- Items and equipment
- Sword Arts
- Formation descriptions
- Status effects
- System messages
- PVR interface graphics
- Parts of the opening movie

The game contains thousands of dialogue and text commands, as well as Japanese text stored directly inside graphical resources.

---

## Technical Work

This project required more than simple text replacement.

### String relocation

Some English translations are much longer than their original Japanese strings.

For example:

**浮遊城 → FLOATING CASTLE**

When a translation cannot safely fit in its original space, longer strings can be relocated and their references redirected where possible.

### Dreamcast PVR graphics

Some Japanese interface text is stored directly inside **PVR textures** rather than as normal text.

Several graphical resources have been decoded, edited and reinserted into the game.

### CRI Sofdec opening

The game uses a **CRI Sofdec SFD** opening movie containing MPEG video and ADX audio.

The modified opening required preserving important properties of the original Sofdec stream and MPEG structure to work correctly in-game.

---

## Beta Testing

Beta testers are very welcome.

Ideally, the game needs to be played from beginning to end while exploring as many menus, events, characters and gameplay systems as possible.

Please report:

- Japanese text still visible
- Japanese graphics
- Untranslated menus
- Incorrect translations
- Awkward English
- Incorrect names
- Text overflow or alignment problems
- Missing or broken text
- Graphical corruption
- Broken events
- Crashes or freezes
- Opening/video problems
- Anything else that looks wrong

### When reporting a bug

Please include, if possible:

1. A screenshot
2. The chapter, location, menu or battle
3. What you were doing when the problem occurred
4. Emulator or hardware used
5. Any other information that may help reproduce the problem

Screenshots are especially useful for tracing untranslated graphical resources.

---

## Known Limitations

Beta 1 may still contain:

- Untranslated Japanese text
- Untranslated graphical elements
- Translation/context mistakes
- Awkward English
- Text alignment or overflow problems
- Rare event issues
- Emulator-specific problems
- Other bugs not yet discovered

Static analysis cannot reliably identify every player-facing element in the game.

Some Japanese data inside the executable also belongs to debugging, development or internal structures and should not be modified blindly.

The goal is not simply to remove every Japanese byte from the game.

The goal is to produce a **stable, readable and enjoyable English version**.

---

## Download

The latest public version can be found in the **Releases** section of this repository.

**Current release: Beta 1 / Build 62**

**Beta 1 Hotfix / Build 62 fixes a critical loading freeze present in Build 61.**

The download contains the **translation patch only**.

**No Dreamcast game image, ROM, GDI, CDI or other copyrighted game data is distributed by this project.**

You must provide your own copy of the original Japanese game.

---

## Discord

For beta testing, bug reports, screenshots and project discussion:

**https://discord.gg/qf33SZmpn**

Discord is currently the easiest place to report problems found during gameplay.

---

## Translation Quality

The English script is still undergoing review and should be considered a **Beta translation**.

It has received technical and terminology consistency checks, but has not received a complete professional editing pass by a fluent Japanese translator.

Context can reveal translation problems that are difficult to identify from extracted text alone.

If something sounds wrong during gameplay, please report it.

---

## Future Plans

Feedback from Beta 1 will be used to prepare future builds.

The current development phase is focused on:

- Full-game beta testing
- Remaining Japanese content
- Translation corrections
- UI and graphical corrections
- Bug fixing
- Stability testing
- English polishing

Once enough full-playthrough testing has been completed, the project can move toward a final release.

---

## Project Goal

The goal is simple:

**A complete, stable and enjoyable English version of Langrisser Millennium for the Sega Dreamcast.**

If Japanese appears, it will be investigated.

If a translation is wrong, it can be improved.

If a graphical element was missed, it can be identified and corrected.

If something breaks, it can be investigated through beta testing.

---

## Disclaimer

This is an unofficial fan translation project.

**Langrisser Millennium**, Sega Dreamcast and all related trademarks and copyrighted material belong to their respective owners.

This repository does not distribute the original game or pre-patched game images.
