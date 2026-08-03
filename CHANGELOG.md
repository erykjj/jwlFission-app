# jwlFission App Changelog

## Unreleased

### Added

- Add button to allow launching from video links copied to clipboard

### Changed

- Handle position sync on mode/language change
- Various other improvements

### Fixed

### Removed

____
## [v2.1.0] - 2026-07-10
### Fixed

- Fixed italic markers in copy/export
  - in subtitle copy/export: italic tags <i> are included
  - in transcript copy/export: italic tags are stripped away (plain text only)

## [v2.0.2] - 2026-07-09
### Added

- Added subtitle (timestamp) and transcript (restructured text) mode toggle
  - selections and searching work in both modes
  - both modes are synchronized

## [v1.14.0] - 2026-06-25
### Changed

- Updated libs

## [v1.12.0] - 2026-06-24
### Changed

- Updated libs
- Edge-to-edge fixes

## [v1.10.0] - 2026-06-08
### Fixed

- Fixed whole-line italics in some languages (like French)

## [v1.8.0] - 2026-06-05
### Added

- Allow copying whole transcript to clipboard

### Changed

- Restore timestamp toggle state between sessions
- Use _ for italics (instead of \<em> tags)
- Share will send *text* instead of *file*
  - Allow to share only selected range (similar to copy)
- Keep transcript title sticky at top

### Fixed

- Fixed splashscreen color

## [v1.6.0] - 2026-03-03
### Changed

- Updated libs
- Edge-to-edge fixes

## [v1.5.0] - 2026-01-06
### Added

- Added title and release date to top of subtitle display
  - also to shared/saved file and link copied to clipboard

### Changed

- Updated libs

## [v1.4.0] - 2025-12-19
### Added

- Added toast when link OK but no subs available

### Changed

- Improved website link handling
- Updated to latest framework/libs

## [v1.3.0] - 2025-11-28
### Changed

- Fine-tuned timegap-based merging

### Fixed

- Fixed italics handling

## [v1.2.0] - 2025-11-23
### Added

- Improved sharing from website
  - Handle videos from search results
  - Handle "Featured" and "Latest" videos

### Changed

- Spinning logo while loading

### Fixed

- Added "S" (Spanish) to top languages

## [v1.1.0] - 2025-11-23
### Added

- Handle URLs with locale instead of wtlocale (shared from browser)

## [v1.0.0] - 2025-11-20

- Initial production release

____
[v2.1.0]:https://github.com/erykjj/jwlFission-app/releases/tag/v2.1.0
[v2.0.2]:https://github.com/erykjj/jwlFission-app/releases/tag/v2.0.2
[v1.14.0]:https://github.com/erykjj/jwlFission-app/releases/tag/v1.14.0
[v1.12.0]:https://github.com/erykjj/jwlFission-app/releases/tag/v1.12.0
[v1.10.0]:https://github.com/erykjj/jwlFission-app/releases/tag/v1.10.0
[v1.8.0]:https://github.com/erykjj/jwlFission-app/releases/tag/v1.8.0
[v1.6.0]:https://github.com/erykjj/jwlFission-app/releases/tag/v1.6.0
[v1.5.0]:https://github.com/erykjj/jwlFission-app/releases/tag/v1.5.0
[v1.4.0]:https://github.com/erykjj/jwlFission-app/releases/tag/v1.4.0
[v1.3.0]:https://github.com/erykjj/jwlFission-app/releases/tag/v1.3.0
[v1.2.0]:https://github.com/erykjj/jwlFission-app/releases/tag/v1.2.0
[v1.1.0]:https://github.com/erykjj/jwlFission-app/releases/tag/v1.1.0
[v1.0.0]:https://github.com/erykjj/jwlFission-app/releases/tag/v1.0.0
