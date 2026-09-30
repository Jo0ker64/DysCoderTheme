# DysCoder Universal Theme

[Version française](README.md)

DysCoder Universal is a Visual Studio Code theme designed to make code easier to scan, locate, and read over long sessions.

It is intended in particular for dyslexic developers, developers with ADHD, and anyone who prefers a structured, high-contrast, less visually noisy interface.

![DysCoder Universal dark preview](images/preview-dark.png)

## What DysCoder provides

- A comfortable anthracite dark palette (`#383838`).
- A consistent color for each code role: keywords, functions, types, strings, numbers, variables, and comments.
- Clear visual hierarchy: keywords, functions, classes, HTML tags, and CSS properties are emphasized in bold.
- Orange comments that are easy to find without blending into the code.
- Progressive indentation guides to follow nested blocks more easily.
- Universal support based on generic VS Code syntax rules, with additional HTML, CSS, and common-language rules.

## Installation

### From the Visual Studio Code Marketplace

1. Open Visual Studio Code.
2. Open the Extensions view with `Ctrl+Shift+X`.
3. Search for `DysCoder Universal Theme`.
4. Install the extension.
5. Open the Command Palette with `Ctrl+Shift+P`.
6. Run `Preferences: Color Theme`.
7. Select **DysCoder Universal**.

## Recommended font: OpenDyslexic

The theme works with any monospace font. For a reading experience designed with dyslexia in mind, we recommend trying [OpenDyslexic](https://opendyslexic.org/).

1. Download and install OpenDyslexic from its official website.
2. In VS Code, open `Ctrl+Shift+P` and run `Preferences: Open User Settings (JSON)`.
3. Add the font to your settings:

```json
{
  "editor.fontFamily": "OpenDyslexic, Consolas, monospace"
}
```

If this font does not work for you, use whichever font feels most comfortable to read. DysCoder does not force a font choice.

## DysCoder Reading Profile

The theme changes colors. The reading profile adds optional settings to make the editor more spacious and large projects easier to navigate:

- font size `16`;
- line height `28`;
- slight character spacing;
- disabled minimap;
- visible active line and indentation guides;
- non-compacted Explorer folders;
- increased Explorer indentation;
- enabled breadcrumbs.

The [`profiles/DysCoder-Reading.settings.json`](profiles/DysCoder-Reading.settings.json) file contains these settings. You can copy all or part of them into your VS Code settings. They remain optional: everyone should be able to keep the workflow that suits them.

## Compatibility

DysCoder is designed to work across as many languages as possible through VS Code's common syntax categories. It is tested throughout development with:

- TypeScript and JavaScript;
- Python;
- HTML and CSS;
- PHP;
- SQL;
- JSON;
- Java.

## Feedback and improvements

The theme is built from real code-reading situations. If a color lacks contrast, a language is hard to distinguish, or an element blends into the rest, please open an issue in the [GitHub repository](https://github.com/Jo0ker64/DysCoderTheme/issues).

## License

Distributed under the **Joeker Labs Community License (JLCL) v1.0**.

Copyright © 2026 Joeker Labs. All rights reserved. See [LICENSE](LICENSE) for the full terms.
