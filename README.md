# Crochet Palette

An open-source stitch colour planning tool for crochet and fibre artists.

Crochet Palette is a browser-based space for exploring motif colours and planning stitch-by-stitch grids without an account or cloud service.

## Why Crochet Palette

Generic pixel and grid tools do not always reflect the way crochet makers plan colours row by row and stitch by stitch. Crochet Palette is designed around a crochet-oriented visual workflow.

## Motif Templates

The application currently includes three selectable crochet motif templates:

- 花朵方形花片
- 经典祖母格 / Classic Granny Square
- 花瓣扇贝方片 / Petal Shell Square

Motifs can define different numbers of independently editable colour roles. Petal Shell Square currently provides five roles: Framework, Inner Petals, Shell Ring, Square Transition, and Border. It is a structural visual motif for colour planning, not an exact crochet pattern generator.

## Features

- Three selectable crochet motif templates with template-specific colour roles.
- Per-role colour editing, locking, Shuffle, Reset, and Undo.
- A reusable yarn palette with an add-colour control.
- Saved palette Collection and motif Gallery.
- Chinese and English interface support.
- Copy HEX values and export motif or grid plans as PNG.
- Grid Planner with row and stitch labels, drawing, clear cell, right-click clear, colour picking, fill row, fill column, clear row, clear canvas, and Undo.
- Responsive controls for desktop and mobile browsers.
- Installable Web App metadata and local browser storage.

## Privacy & Data

- Browser-only: no account is required.
- No analytics, tracking, or external API is used.
- User state is stored locally in the browser with `localStorage`.
- PNG exports are generated locally.
- Data is not synchronized between devices or browsers.
- Clearing browser or site data may remove saved state.

## Run Locally

This is a static project. Serve this directory with any simple static HTTP server, then open the local URL in a browser. No package installation is required.

The page can also open directly from `file://` for normal development use. Browser storage is origin-specific, so data saved under `file://` is separate from data saved through a local HTTP server or an HTTPS deployment.

## Browser Support

Designed for modern desktop and mobile browsers. PNG export and rendering can vary slightly by browser and operating system.

## Project Status

Early open-source release / active development.

See [CHANGELOG.md](CHANGELOG.md) for release history.

## Contributing

Bug reports, accessibility improvements, browser-compatibility feedback, crochet-workflow feedback, and carefully scoped feature proposals are welcome.

Please keep changes small, verify existing functionality before and after a change, and avoid rewriting the project without a clear reason. Do not add analytics, tracking, or external APIs unless a maintainer explicitly accepts the change. Do not submit assets whose copyright or source is unclear.

## License

Software code is available under the [MIT License](LICENSE).

MadeByLala brand assets are subject to the branding terms in [BRANDING.md](BRANDING.md).