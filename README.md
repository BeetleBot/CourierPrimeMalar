# Courier Prime Malar

Courier Prime Malar is a unified, single-font solution for high-fidelity Tamil screenplay writing. By merging Courier Prime with Mukta Malar, this project provides a specialized typeface that eliminates the rendering bottlenecks found in professional screenwriting software.

## The Technical Objective
Most professional screenplay software (Fade In, Final Draft, Highland) utilizes custom text-rendering engines designed for the precise metrics of 12pt Courier. Introducing a second font for Tamil often results in:

  - Metric Mismatch: The cursor jumps or overlaps because the Latin and Tamil fonts have different widths/heights.
  - Rendering Lag: The software struggles to switch between different font files mid-sentence.
  - Broken Ligatures: System fallback often fails to apply the complex shaping rules required for the Tamil script.
  - Courier Prime Malar bypasses these issues by housing all Latin and Tamil glyphs in a single unified file. This ensures the software treats the entire script as a native set, resulting in stable cursor behavior and perfect character shaping.

### Download the .ttf files from the fonts/ directory.

## Install them on your system:
```
Linux: Place in ~/.local/share/fonts and run fc-cache -fv.
```
```
macOS/Windows: Double-click and install.
```
```
In your screenwriting software, set your global font or element styles to Courier Prime Malar.
```

License

This project is licensed under the SIL Open Font License 1.1.

This is a derivative work based on:
- Courier Prime (Quote-Unquote Apps)
- Mukta Malar (Ek Type)
