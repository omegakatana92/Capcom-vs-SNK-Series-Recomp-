# Capcom vs. SNK Collection Recompilation Project

## Project Overview

The Capcom vs. SNK Collection Recompilation Project is a multi-game development initiative focused on bringing four classic fighting games from Capcom and SNK to modern Windows and Linux gaming environments.

The project combines platform-specific game implementations with a unified, modern launcher designed to preserve the original gameplay experience while introducing convenient quality-of-life features, customizable presentation, modern controller support, and improved accessibility.

The goal is to create a polished fighting game collection that respects the original arcade and handheld experiences while making the games easier to configure, launch, and enjoy on contemporary hardware, including the Steam Deck.

## Supported Games

The collection features four titles across three original gaming platforms.

### Sega NAOMI

- Capcom vs. SNK 2000 Pro
- Capcom vs. SNK 2

### SNK Neo Geo

- SNK vs. Capcom: SVC Chaos

### SNK Neo Geo Pocket Color

- SNK vs. Capcom: The Match of the Millennium

Each game receives its own platform-appropriate implementation, configuration, and compatibility testing.

## Project Features

### Unified Game Launcher

A centralized launcher provides access to all four games through a consistent interface.

Main menu options include:

- Start Game
- Continue / Load
- ROM Selection
- Display Settings
- Audio Settings
- Controller Settings
- Gameplay Settings
- Extras
- About
- Exit

Additional launcher functionality includes individual game profiles, recently played games, persistent settings, game availability indicators, and customizable themes.

### User-Supplied ROM and Game Files

Players must provide their own legally obtained ROMs and required game files.

The application does not distribute copyrighted game ROMs, BIOS files, firmware, or proprietary game assets.

Each game has an independent ROM selection and validation system.

Features include:

- Individual ROM selectors.
- Native file browsing on Windows and Linux.
- Game directory selection where supported.
- Remembered file locations.
- Game-file validation.
- Missing-file detection.
- Compatibility checks.
- External storage support.
- Game-specific setup instructions.

The launcher clearly indicates whether each game is ready to play or requires additional files.

### Original Gameplay Preservation

Preserving the original gameplay experience is a primary development objective.

Development priorities include:

- Accurate fighting mechanics.
- Responsive character movement.
- Correct attack registration.
- Special moves and combinations.
- Character animations.
- Original game timing.
- Character selection.
- Platform-specific gameplay systems.
- Stable frame pacing.

Game-specific mechanics, including the Groove System in Capcom vs. SNK 2 and the original handheld gameplay systems in The Match of the Millennium, must be preserved.

### Graphics and Display Customization

The collection provides configurable display options where supported.

Features include:

- Original aspect ratios.
- Original screen orientation.
- Horizontal and vertical arcade presentation.
- Optional screen rotation.
- Integer scaling.
- Pixel-perfect presentation.
- Windowed and fullscreen modes.
- Nearest-neighbor and bilinear filtering.
- VSync.
- Supported frame-pacing controls.
- Optional CRT shaders.
- Scanlines and shadow masks.
- Screen curvature.
- Brightness and gamma adjustments.
- Custom borders and wallpapers.
- Compatible widescreen options.

Original presentation is preserved by default.

### Audio System

Audio quality and synchronization are important development priorities.

The implementation aims to support:

- Background music.
- Character voices.
- Announcer audio.
- Fighting sound effects.
- Menu sounds.
- Music transitions.
- Stereo output where supported.
- Configurable master volume.
- Independent music and sound-effect volume.
- Audio synchronization.
- Adjustable audio latency where supported.

### Controller and Arcade Input Support

The collection is designed for multiple control configurations.

Supported input targets include:

- Keyboard and mouse.
- Xbox controllers.
- PlayStation controllers.
- Steam Deck integrated controls.
- Compatible arcade sticks.

Additional functionality includes:

- Configurable button mapping.
- Controller presets.
- Controller hotplugging.
- Multiple-player support where available.
- Coin and Start inputs.
- Game-specific arcade buttons.
- Service and test inputs where safely supported.
- Restore-default controls.
- Separate configurations for individual games.

### Save States and Quality-of-Life Features

Modern convenience features are included wherever the underlying runtime supports them.

Planned features include:

- Multiple save-state slots.
- Quick save and quick load.
- Continue from the previous session.
- Save-state management.
- Automatic save-state backups.
- Persistent settings.
- Screenshots.
- Optional rewind functionality where technically feasible.

Save-state functionality must use genuine runtime-state serialization. Where complete save states are unavailable, the application will clearly identify the limitation and use conventional game-save functionality where supported.

### In-Game Quick Menu

An accessible quick menu provides convenient controls without requiring players to exit their current game.

Options include:

- Resume.
- Restart Game.
- Save State.
- Load State.
- Display Settings.
- Audio Settings.
- Controller Configuration.
- Gadgets.
- Return to Main Menu.
- Exit.

Escape is the default keyboard shortcut, with a configurable controller shortcut.

Menu navigation must not accidentally trigger gameplay inputs.

### Gadgets and Extras

An expandable Gadgets section provides additional tools, including:

- Screenshot capture.
- FPS counter.
- Frame-time information.
- Input display.
- Game information.
- Save-state manager.
- Optional visual filters.
- Additional supported runtime utilities.

### Steam Deck Optimization

Steam Deck compatibility is a major development target.

The interface is designed around the Steam Deck's 1280×800 display, with support for 16:10 and 16:9 layouts.

Development priorities include:

- Integrated controller support.
- Game Mode compatibility.
- Readable frontend typography.
- Appropriate display scaling.
- Stable gameplay performance.
- Reliable audio.
- Persistent settings.
- External storage support.
- Convenient application launching.

The Linux release is intended to use a standalone, double-clickable AppImage.

## Supported Operating Systems

### Windows

- Native Windows executable (.exe).
- Bundled or reliably resolved dependencies.
- Game launcher and configuration system.
- Persistent settings.
- Native file selection.
- Controller support.

### Linux / Steam Deck

- Linux application distribution.
- AppImage packaging.
- SteamOS compatibility.
- Steam Deck Game Mode support.
- Integrated controller support.
- Persistent configuration and save storage.
- Internal and external game-file locations.

Both platforms will receive independent testing.

## Development Philosophy

The project prioritizes functional game implementations over superficial presentation.

A game is not considered complete simply because it launches.

Testing must cover:

- Graphics rendering.
- Audio playback.
- Gameplay functionality.
- Character animations.
- Input responsiveness.
- Game timing.
- Frame pacing.
- Stability.
- Save-state functionality where supported.
- Frontend integration.
- Windows compatibility.
- Steam Deck compatibility.

Platform-specific limitations will be documented rather than hidden or represented as completed features.

## Repository and Distribution Policy

This repository is intended for source code, development documentation, and original project materials.

It will not distribute:

- Commercial game ROMs.
- Copyrighted game assets.
- Proprietary firmware.
- BIOS dumps.
- Unauthorized game data.
- Extracted commercial game content.

Players must provide their own legally obtained game files and any required platform firmware.

## Development and Contributions

Development focuses on maintaining a clean, modular architecture that supports the four games independently while sharing frontend components and common application services.

The project aims to provide:

- Organized source code.
- Reproducible builds.
- Documented dependencies.
- Windows build instructions.
- Linux build instructions.
- Steam Deck setup instructions.
- Compatibility documentation.
- Testing reports.
- Release notes.

## Final Goal

The ultimate objective is to deliver a unified Capcom vs. SNK and SNK vs. Capcom fighting game collection that combines the authenticity of the original arcade and handheld experiences with the convenience of a modern gaming application.

Four classic fighting games. Three original platforms. One unified collection.

**Preserve the originals. Improve the experience. Bring the battles to modern hardware.**
