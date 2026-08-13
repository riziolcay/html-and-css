# Web Technologies Project 1

## Description

A single XHTML 1.0 document (`index.html`) that presents two entirely different visual layouts depending on which stylesheet it links to — no JavaScript involved.

- **Style A** (`styleA.css`) — six boxes stacked vertically, centered horizontally, and equally spaced using Flexbox. The spacing between boxes adapts when the window is resized, but the boxes themselves never change size or overlap. The final box has a thick black border and centered text.
- **Style B** (`styleB.css`) — the first five boxes are arranged in a horizontal row in the top-left corner and never wrap, even on a narrow window. The sixth box is fixed to the bottom-right corner of the window at all times. Hovering over a box changes the cursor to a pointer and recolors the box (yellow background, goldenrod text).
- **Style C** (`styleC.css`, extra credit) — a third look for the same markup, using CSS gradients and transitions for a smoother, more dynamic appearance.

## Files

- `index.html` — the single shared markup (six `.box` divs inside a `#container`), valid XHTML 1.0 Strict.
- `styleA.css` — Style A layout.
- `styleB.css` — Style B layout.
- `styleC.css` — extra credit layout.

## How to run

Open `index.html` directly in Chrome. By default it links to `styleA.css`.

To preview the other looks, open `index.html` in a text editor and change the `href` in the `<link>` tag inside `<head>`:

```html
<link rel="stylesheet" type="text/css" href="styleA.css" />
```

to `styleB.css` or `styleC.css`, save, and refresh the page.

## Student

Rizwan — Government Post Graduate Science College, Quetta
