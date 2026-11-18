# The World Today — 17 November 2026

A newspaper front page summing up the world news of **Tuesday, 17 November 2026**,
built for the make.fun competition `news-image-20261117`.

## The image

`entry.png` (1024×1024) is a front page titled **THE WORLD TODAY**, rendered
programmatically with Python and PIL (sharp text, no generated imagery), with
simple shape-drawn illustrations for each story:

- **Lead story — Kerch Bridge badly damaged:** a span of the bridge linking
  Russia to Crimea collapsed after a Ukrainian attack.
- **Trump in Manila, then on to China:** arrives for the ASEAN summit, signs a
  joint trade statement with Thailand, then heads to a trilateral meeting with
  Xi and Putin.
- **Mines hit tankers in the Strait of Hormuz:** two tankers struck by mines,
  blamed on the IRGC; a third US aircraft carrier arrives in the region.
- **JPMorgan: outage was a software bug:** Monday's banking outage was caused
  by a software bug, the bank says — not a cyberattack.
- **Vulcan rocket fails; 40 satellites lost:** ULA's Vulcan rocket fails in
  flight and 40 Amazon Leo internet satellites are lost with it.
- **Nvidia reports earnings:** its first earnings since Jensen Huang stepped
  down as chief executive.
- **Also today:** COP31 climate talks continue; Russian strikes hit
  Zaporizhzhia; in Indonesia, police general Irjen Eko Hadi Santoso is
  dismissed dishonourably (PTDH) in the wiretapping ethics case.

No casualty figures appear anywhere: none were verified well enough to print.
No speculation is presented as fact.

## How to run

```sh
mkdir -p out && MAKEFUN_OUTPUT_DIR=out python3 main.py
```

This copies `entry.png` to `$MAKEFUN_OUTPUT_DIR/entry.png`. Standard library
only, no network, deterministic — every run writes the same bytes.

## License

MIT — see `LICENSE`.
