# DysCoder Reading Profile

The DysCoder theme changes Visual Studio Code colors. This optional profile complements the theme with reading-comfort settings: more spacious code, visible indentation guides, and a project tree that is easier to scan.

The profile never replaces your preferences automatically. You can copy every setting or only the ones that work for you.

## Included settings

- Font size set to `16` px, with a `28` px line height.
- Slight character spacing (`0.4`).
- Visible active line and disabled minimap.
- Stronger indentation and bracket-pair guides.
- Explorer folders shown individually, without compacting them.
- Folders displayed before files.
- Explorer indentation set to `30`.
- Breadcrumbs enabled, so the current file path remains visible.

## Installation

1. Install and activate the **DysCoder Universal** theme.
2. Open [`DysCoder-Reading.settings.json`](DysCoder-Reading.settings.json).
3. In VS Code, open the Command Palette with `Ctrl+Shift+P`.
4. Run `Preferences: Open User Settings (JSON)`.
5. Copy the settings you want from the profile file.
6. Save the file. VS Code applies the changes immediately.

## Font

The profile does not force a font. You can try [OpenDyslexic](https://opendyslexic.org/), Atkinson Hyperlegible Mono, or any monospace font that feels comfortable to read.

After installing a font, you can add it to your settings:

```json
{
  "editor.fontFamily": "OpenDyslexic, Consolas, monospace"
}
```

## Adapt the profile to your reading needs

These values are a starting point, not a rule. Feel free to adjust:

- `editor.fontSize` if text is too small or too large;
- `editor.lineHeight` if lines are too close together or too far apart;
- `editor.letterSpacing` if characters feel too tight;
- `workbench.tree.indent` if the Explorer needs more or less spacing.

If a setting does not suit the way you work, simply remove it from your preferences.
