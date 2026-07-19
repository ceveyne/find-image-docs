# Changelog

Notable changes to this project will be documented in this file.

## Distribution

- **Source Code:** [LM Studio Hub](https://lmstudio.ai/ceveyne/find-image)
- **Documentation:** [GitHub Repository](https://github.com/ceveyne/find-image-docs)

---

## [0.1.4] - 2026-07-19 Revision 4

### Added

- Added an option to allow for byte-identical duplicates in search resutls.

### Changed

- Updated README.md.
- Structured search criteria no longer affect semantic result ranking.
- Metadata searches now return only images matching every requested constraint.

### Fixed

- Search results no longer re-enter image indexing.

---

## [0.1.3] - 2026-07-18 Revision 3

### Changed

- Added some more screenshots to README.md.
- Improved tool-descriptions.
- Diagnostic logs now consistently use local time.

### Fixed

- Draw Things project updates are detected reliably, including recent changes.

---

## [0.1.2] - 2026-07-18 Revision 2

### Fixed

- Draw Things projects are no longer modified during indexing.

---

## [0.1.1] - 2026-07-17 Revision 1

### Added

- Initial release
- **find-image** is an advanced LM Studio plugin for searching local image stores and generation history. It helps finding images, prompts, source files, and project entries even if you remember only part of what you are looking for.
- The plugin combines metadata search with optional multimodal embedding search. Exact text matches still matter, but visual embeddings allow results to be found by image content instead of only by prompt or filename text.
- When used together with draw-things-chat or user-docs, search results can be shown with visual previews and can be referenced in follow-up analysis, detection, generation, edit, image-to-image, image-to-video, or post-processing requests.
