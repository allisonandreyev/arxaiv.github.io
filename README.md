# AI-Generated Scientific Paper Dataset

This repository hosts a small, fully AI-generated scientific dataset. All assets were produced synthetically and are provided as zipped PNG bundles for easy download and inspection.

## Files in this repo
- `Set 1.zip` — first half of the AI-generated paper set; 59 PNGs (`1.png`–`59.png`) plus macOS resource sidecars.
- `Set 2.zip` — second half of the AI-generated paper set; 41 PNGs (`60.png`–`100.png`) plus macOS resource sidecars.
- `figures.zip` — 156 standalone AI-generated figures stored under `figures/` (314 entries when counting `__MACOSX` resource files).

## Getting started
1) Download or clone this repo.
2) Extract the archives:
   - `unzip "Set 1.zip" -d papers`
   - `unzip "Set 2.zip" -d papers`
   - `unzip figures.zip -d figures`
3) You can merge the paper halves by extracting both `Set 1` and `Set 2` into the same `papers/` directory; filenames already run from `1.png` to `100.png`.

## Dataset notes
- The zips were created on macOS, so `__MACOSX` files may appear on extraction; they can be safely deleted.
- All content is AI-generated. Please review for fitness before downstream use and observe any institutional policies governing synthetic data.
- No license or citation text is included yet; add one here if you intend to share publicly.

## Suggested citation (fill in)
If you use this dataset, please cite the repository. Example placeholder:

```
@misc{arxaiv2026,
  title = {arxAIv: An AI-Generated Scientific Research Universe},
  author = {Andreyev, Allison},
  howpublished = {\url{https://github.com/allisonandreyev/arxaiv.github.io}},
  note = {Version 1.0, accessed YYYY-MM-DD}
}
```
