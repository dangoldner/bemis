# Formatting Instructions for Chapter Dialogs

When preparing dialogs for future chapters, apply these transformations:

1. **Dollar signs in LaTeX**: Replace `\$` (backslash-dollar) with `&#36;` — the escape doesn't render correctly, possibly due to KaTeX interference.

2. **Figure paths**: Replace local paths like `fig/1.1.png` with the GitHub raw URL:
   ```
   https://raw.githubusercontent.com/dangoldner/bemis/main/fig/1.1.png
   ```
   The local path isn't accessible in the published version of the dialog.
