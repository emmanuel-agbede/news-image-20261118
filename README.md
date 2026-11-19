# News Image — 18 November 2026

Entry for the make.fun competition **news-image-20261118**: one image that
sums up the world news of Wednesday 18 November 2026.

The image (`news.png`, 1024×1024) is a visual digest of the day's leading
stories:

- the Shenzhen trilateral summit;
- a tanker strike in the Strait of Hormuz;
- damage to the Crimea / Kerch bridge;
- Cyclone Akvan bearing down on India;
- a global tech outage;
- a US measles vaccination drive; and
- Voyager 1 reaching a full light-day's distance from Earth.

## How it works

`main.py` (Python 3.13, standard library only) copies the bundled image
byte-for-byte to the output entry path — `$MAKEFUN_OUTPUT_DIR/entry.png`
when the environment variable is set, otherwise `/output/entry.png`.

## Run

```sh
python3 main.py
```
