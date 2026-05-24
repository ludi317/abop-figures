# abop-figures

Interactive recreations of figures from *The Algorithmic Beauty of
Plants* (Prusinkiewicz & Lindenmayer, 1990). Each file is a single
self-contained HTML page using p5.js. No build, no dependencies
beyond a browser.

## Running

Open any `Figure-*.html` directly in a browser, or serve the
directory with anything that handles static files:

```
python3 -m http.server
```

Then visit `http://localhost:8000/`.

## Files

### Chapter 1 — Graphical modeling using L-systems

- **Figure-1.24-bracketed-OL-systems.html** — the classic bracketed
  OL-systems (a–f).
- **Figure-1.25-3D-bush.html** — 3D bush model.
- **Figure-1.31-Hogeweg-Hesper-plants.html** — context-sensitive
  2L-systems (a–e) over `{0,1}`.

### Chapter 2 — Modeling of trees

- **Figure-2.6-monopodial-tree.html** — Honda's monopodial tree
  L-system (Table 2.1, a–d). 3D, orbit + zoom.
- **Figure-2.7-sympodial-tree.html** — Aono–Kunii sympodial tree
  L-system (Table 2.2, a–d). 3D.
- **Figure-2.8-3D-tree.html** — ternary-branching tree with tropism
  (Table 2.3, a–d). 3D.

### Chapter 4 — Phyllotaxis

- **Figure-4.2-phyllotaxis.html** — Vogel's phyllotaxis disc model.
- **Figure-4.15-pineapple.html** — cylindrical phyllotaxis on a
  pineapple.

### Chapter 5 — Models of plant organs

- **Figure-5.5-cordate-leaf.html** — cordate leaf as a polygon. Grid
  of derivation stages with adaptive cell widths.
- **Figure-5.6-simple-leaves.html** — simple leaves family
  (Table 5.1, a–f).
- **Figure-5.8-rose-leaf.html** — rose leaf.
- **Figure-5.11-compound-leaves.html** — compound leaves
  (Table 5.2, a–e).

### Chapter 8 — Fractal properties of plants

- **Figure-8.2-Barnsley-fern.html** — Barnsley fern via IFS.


## Source

The PDF used as reference is *The Algorithmic Beauty of Plants*,
available online at <http://algorithmicbotany.org/papers/abop/abop.pdf>.
