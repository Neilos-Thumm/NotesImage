# Notes Image

Makes images copied from a browser pasteable in Apple Notes.

Browsers copy an image together with an HTML link to it. Notes uses the link and shows a blue `?` instead of the picture. `img` keeps only the picture on the clipboard.

## Use

1. Copy an image in the browser.
2. Run `img` in the terminal.
3. Paste into Notes (⌘V).

## Install

```bash
cp img ~/.local/bin/img
chmod +x ~/.local/bin/img
```

`~/.local/bin` must be on your `PATH`.
