# Changelog

All notable changes to this theme are documented here.
The format follows [Keep a Changelog](https://keepachangelog.com/en/1.1.0/),
and the theme uses [Semantic Versioning](https://semver.org/).

## [Unreleased]

## [1.1.0] - 2026-11-11

### Added

- Thin white outline on the setting groups and text fields of the Luna settings page (`--theme-luna-box-border`)
- Outline in the sunset gradient on context menus and their submenus (`--theme-popup-border`); submenu and context menu lines lie on top of each other, whether the submenu opens to the left or to the right
- Midnight-blue hover for context menu entries, rows in the Feed, track rows on playlist pages (all columns) and the three-dot button on album covers; the selected entry in the sidebar menu uses it too and fills the whole menu width
- White play and heart buttons on album and personal radio covers; a liked heart shows the sunset gradient
- Music notes animation in the colours of the sunset: amber at the bottom, rose in the middle, indigo at the top
- The name of the playlist that is playing is shown in amber in the sidebar
- Layout for the Local Files plugin page (`.lf-page`)

### Changed

- The search field becomes as wide as the results panel while the results are open (`--theme-search-open-width`)
- The compact header that appears when scrolling an album or credits page has a solid black background, and its cover, title, artist and buttons sit lower so the top bar no longer covers them
- The "Next up" box (plugin up-next) in the player has no background, starts further right and is limited in width so it stays clear of the heart, the menu and the playback buttons
- Luna settings page starts closer to the top bar

### Fixed

- The Local Files page no longer runs off the right edge of the window

## [1.0.0] - 2026-11-07

### Added

- Pure black design for AMOLED screens with square corners throughout
- Fullscreen view with a sunset background
- Progress bar animations: `tide`, `stardust`, `moon`, `aurora`, `notes`, `bubbles`, `none`
- Seek line along the top of the player that grows on hover
- Search field at the top of the sidebar with a dimmed spotlight while results are open
- Player docked to the bottom across the full window width
- Black backgrounds on album, playlist, track and Luna settings pages

[Unreleased]: https://github.com/mathisschaefer2000/Tidal-Nightfall/compare/v1.1.0...HEAD
[1.1.0]: https://github.com/mathisschaefer2000/Tidal-Nightfall/compare/v1.0.0...v1.1.0
[1.0.0]: https://github.com/mathisschaefer2000/Tidal-Nightfall/releases/tag/v1.0.0
