# ArtPros Viewer Mini Demo

This folder is a static GitHub Pages demo for ArtPros Viewer.

It includes one speaker (`PGU-CD`) and six clean demo sweeps:

- `0030` - A5, focus on MATT
- `0032` - A6, focus on MATT
- `0034` - A1, broad focus
- `0037` - A4, focus on SAT
- `0039` - A3, focus on CAT
- `0048` - A2, focus on FAT

The file `PGU-CD/pos/0001.txt` is included only to estimate the clenched-teeth jaw baseline.

This stripped-down demo does not require WAV audio files. If `PGU-CD/wav/*.wav` is absent, the viewer still loads the TextGrid annotations, EMA tracks, velocity tracks, syllable triangles, and articulatory boundary calculations. Waveform display and click-to-play audio are simply disabled.

Run locally from this directory with:

```bash
python3 -m http.server 8000
```

Then open:

```text
http://localhost:8000/
```

For GitHub Pages, publish this directory and use `index.html` as the entry point.
