# ArtPros Viewer Mini Demo

This folder is a static GitHub Pages demo for ArtPros Viewer.

It includes one speaker (`PGU-CD`) and four demo sweeps:

- `0028`
- `0029`
- `0030`
- `0032`

The file `PGU-CD/pos/0001.txt` is included only to estimate the clenched-teeth jaw baseline.

Run locally from this directory with:

```bash
python3 -m http.server 8000
```

Then open:

```text
http://localhost:8000/
```

For GitHub Pages, publish this directory and use `index.html` as the entry point.
