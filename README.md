# SVG Tool

A browser-based SVG editor that runs entirely client-side — no build step, no dependencies, just open `index.html`.

## Features

- **Draw shapes** — rectangle, ellipse, line, polygon, polyline, text, and freehand paths
- **Edit paths** — click any path to see its nodes; drag nodes and control handles; add line/curve/quadratic/arc segments from the start or end
- **Select & transform** — resize any element with corner/edge handles; rotate by dragging near the selection boundary
- **Inspect & style** — edit fill, stroke, font, and raw attributes in the side panel
- **Canvas control** — set canvas dimensions, toggle the grid, pick a background color
- **Export** — download as SVG, PNG, or JPG; copy raw markup to clipboard
- **Import** — drag-and-drop an SVG file, use the file picker, or paste from clipboard if it contains SVG markup
- **Undo / redo** — full history via Ctrl/Cmd+Z and Ctrl/Cmd+Shift+Z

## Usage

Open `index.html` in any modern browser. No server required.

### Keyboard shortcuts

| Key | Tool |
|-----|------|
| `V` | Select / Move |
| `P` | Path (pen) |
| `R` | Rectangle |
| `O` | Ellipse |
| `L` | Line |
| `G` | Polygon |
| `Y` | Polyline |
| `T` | Text |
| `Del` | Delete selected node or element |
| `Esc` | Finish drawing |
| `Ctrl/Cmd+Z` | Undo |
| `Ctrl/Cmd+Shift+Z` | Redo |

### Path editing

Select any path with the Select tool, then click a node to activate it. Blue node = selected. Gray dots with connecting lines are control handles for curves.

Use the add-segment buttons that appear below the start/end nodes to extend the path with a line, cubic curve, quadratic curve, or arc. For arcs, drag the diagonal control handle to adjust the rx/ry radii.

### Resize & rotate

With any element selected, drag a corner or edge handle to resize. To rotate, click and drag anywhere along the selection boundary between the handles — the cursor changes to a grab cursor in that zone.
