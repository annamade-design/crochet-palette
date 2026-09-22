# Changelog

This file records notable user-facing and technical changes to MadeByLala Crochet Palette.

## [0.2.0] - 2026-09-23

### Added

- Added the Petal Shell Square / 花瓣扇贝方片 structural crochet motif.
- Added five independently editable colour roles for Petal Shell Square: Framework, Inner Petals, Shell Ring, Square Transition and Border.
- Expanded structural motif support for motifs with variable role counts.

### Improved

- Structural motif architecture now accommodates different role counts instead of assuming one fixed role count.
- Updated public OSS documentation to describe the three available motifs.
- Integrated the new motif with the existing SVG template, colour-role and thumbnail rendering systems.

### Compatibility

- Existing motifs remain supported.
- Existing localStorage data and schema remain compatible.
- Existing colour, lock, shuffle, undo, reset and PNG export workflows support the new motif.
- The existing PWA manifest and branded icons remain compatible.

### Verification

- Role colour controls verified.
- Lock, shuffle, undo and reset behaviour verified.
- Chinese and English labels verified.
- Motif thumbnail rendering verified.
- PNG export verified.
- Mobile layout verified.
- localStorage persistence verified.
- Existing motif regression verified.
- PWA manifest and icon regression verified.

## [0.1.1] - 2026-08-18

### Improved

- Improved the visual distinction between locked and unlocked motif controls.
- Clarified the unlocked state while preserving the selected-role visual hierarchy.
- Improved lock-control accessibility labels.

Fixes #1

## [0.1.0] - 2026-08-18

### Added

- Initial public release with two Classic Granny motif templates.
- Editable yarn colour palette with lock, shuffle and undo workflows.
- Collection and Gallery workflows.
- Grid Planner with row and stitch labels and draw, clear, pick and fill tools.
- Chinese and English UI.
- Local PNG export.
- Responsive desktop and mobile layouts.
- Browser-local persistence.

### Privacy

- No account is required.
- Application state remains in the visitor's browser.
- No analytics, tracking or external API is required.