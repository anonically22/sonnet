# Change Log

All notable changes to the **Sonnet** extension will be documented in this file.

## [0.1.0] — 2026-06-29

### Added
- **Two dark theme variants** shipping in a single extension:
  - **Sonnet Crimson** — pure black base (`#000000`), near-white foreground (`#f5f5f5`), blood-red cursor (`#e8112e`), crimson keywords (`#a30f29`). Sharp, high-contrast, severe.
  - **Sonnet Tsar** — deep blue-black base (`#0a0e14`), icy-white foreground (`#e8f0f7`), frost-white cursor (`#cdeefc`), ice-blue keywords (`#4ec3e0`). Crystalline, frozen, regal.
- Full `colors` section for each variant: editor, sidebar, activity bar, tabs, status bar, title bar, buttons, inputs, lists, scrollbars, badges, diff/git decorations, and terminal ANSI colors.
- Full `tokenColors` section for each variant: comments (italic), keywords, storage types, functions, variables, constants, strings, numbers, language constants (bold), HTML/JSX tags, attribute names, punctuation, support classes/namespaces, markup (bold/italic/heading), and invalid tokens.
- Both variants registered in `contributes.themes` under labels `Sonnet Crimson` and `Sonnet Tsar`.
