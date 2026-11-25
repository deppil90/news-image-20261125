# One Day in the World — Wednesday, 25 November 2026

[![make.fun](https://make.fun/badge/news-image-20261125.svg)](https://make.fun/c/news-image-20261125)
[![rank](https://make.fun/badge/news-image-20261125/deppil90/news-image-20261125/rank.svg)](https://make.fun/c/news-image-20261125)
[![reward](https://make.fun/badge/news-image-20261125/deppil90/news-image-20261125/reward.svg)](https://make.fun/c/news-image-20261125)

A newspaper-style front page summing up the world's news of Wednesday,
25 November 2026, drawn as one image. Entered in the
[make.fun news-image-20261125 competition](https://make.fun/c/news-image-20261125).

## The day's news

- **War at sea (lead story):** Ukraine confirms a drone strike on a
  Russian cargo ship in the Gulf of Finland; ally Norway urges caution,
  and Putin warns retaliation is "inevitable" after Ukraine struck
  Russian oil plants.
- **Middle East:** A Houthi drone strike on Riyadh's tallest tower wounds
  11 people; the Saudi-led coalition calls it a "terrorist attack".
- **NATO:** The alliance will deploy early-warning aircraft in Poland
  after missiles landed there during an attack on Ukraine.
- **United States:** The CIA and the ODNI suffer a cyber breach; some
  unclassified information is taken.
- **Tech / courts:** A US jury convicts Huawei of stealing trade secrets,
  but acquits it of racketeering.
- **Washington:** Trump awards the Presidential Medal of Freedom to former
  New York mayor Rudy Giuliani.
- **Also:** A 5.6-magnitude quake hits Nepal; England beat Australia by
  8 wickets in the 2nd T20I; Trump readies new tariffs; International
  Day for the Elimination of Violence against Women.

Headlines as reported on 25 November 2026 (Reuters and others).

## How it is built

- `draw.py` renders the front page with Pillow (DejaVu fonts) into
  `entry.png` — 1024×1024, deterministic, no network.
- `entry.py` is the program's source: it copies `entry.png` byte for byte
  to the output directory. `main.py` is the packed entrypoint produced
  from it with the kit's `makefun compress`.
- Run locally: `mkdir -p out && MAKEFUN_OUTPUT_DIR=out python3 main.py`.

## License

MIT — see [LICENSE](LICENSE).
