# tidepool-assets

Generated art for [Tidepool](https://github.com/marcusohx/tidepool), a Twitch chat
fishing game. Served over jsDelivr:

    https://cdn.jsdelivr.net/gh/marcusohx/tidepool-assets@main/<variant>/<slug>.png

**This repository is generated. Do not edit it by hand.** Sprites are built from
64x64 masters in the source repo by `tools/build_catalog.py` and staged here by
`tools/stage_assets.py`. Anything changed here is overwritten on the next publish.

Variants are **directories**, never filename prefixes. The prefix scheme is what
caused 8 of the 10 live 404s found in a teardown of a competing product, and the
directory layout is what makes that class of typo impossible.

`index.json` lists every sprite with its URL and a pixel hash. The source repo's
zero-404 gate checks each URL returns 200 on every push.

## Provenance

Original art. Generated with PixelLab, quantized to a hand-authored palette derived
from this project's own probe census, and hand-finished. No competitor asset, sprite
or palette is used. See `docs/AI-DISCLOSURE.md` and `docs/PROVENANCE.md` in the
source repo.
