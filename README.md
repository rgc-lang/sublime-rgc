# RGC for Sublime Text

A Sublime Text 3/4 package with:

- Full RGC syntax highlighting (`RGC.sublime-syntax`)
- Build system: compile (`rgc`), run (`rgc run`), test (`rgc test`)
- Completions for keywords and common snippets
- Symbol list (functions/classes) and comment/indentation rules

## Installation

**Package Control:** add this repository
(`Package Control: Add Repository` → `https://github.com/rgc-lang/sublime-rgc`),
then `Package Control: Install Package` → `RGC`.

**Manual:**

```sh
git clone https://github.com/rgc-lang/sublime-rgc ~/.config/sublime-text/Packages/RGC
```

## Usage

- `.rg` files are highlighted automatically.
- `Ctrl+B` (Build) compiles the current file.
- Build *Run* / *Test* variants via `Tools → Build System → RGC` and `Ctrl+Shift+B`.
- `Ctrl+Shift+R` / `Goto → Goto Symbol` lists functions and classes.

## License

Apache-2.0. See [LICENSE](LICENSE).