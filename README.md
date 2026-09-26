# Møntfod · Coinage Standards of the Kingdom of Denmark

A reference work on the coinage standards (*møntfødder*, *Müntzfüße*) of the
Danish-Norwegian realm, 1514–1914: which standard was in force when, what it
prescribed, and the coins struck under it.

**Live:** https://danskmoent.github.io/
**Languages:** Danish (default) · German · English · Ukrainian

## What the site contains

- A timeline of every standard on one common time scale.
- For each standard: its legal basis, its defining parameters (pieces per
  Cologne mark, fineness), its phases, and the coins struck under it,
  divided into full-value (*kurant*) and subsidiary (*skillemønt*) issues.
- Each coin row carries its catalogue numbers (Hede, Schou, Sieg, Krause and
  others), measured weights and fineness per source, and links to the
  museum records, catalogues and auction lots that document it.
- A bibliography for every factual claim in the text.

It is not a complete coin catalogue: a coin is included to document how a
standard worked, not to list every variant or die.

## This repository

This repository only **serves** the site. It contains no source data and no
build code.

| Branch | Content |
|---|---|
| `main` | This README and the licence. |
| `gh-pages` | The generated site. Rewritten on every publish — do not edit it by hand. |

The data (YAML), templates and build pipeline live in
[munzfuss/munzfuss.github.io](https://github.com/munzfuss/munzfuss.github.io),
which also publishes the sister site on the coinage standards of the North
German territories, [munzfuss.github.io](https://munzfuss.github.io/). On every
push to that repository's `main`, GitHub Actions builds the Danish site
(`scripts/build.py --site danskmoent`) and publishes it to the `gh-pages`
branch here.

Corrections and questions: please open an issue in
[munzfuss/munzfuss.github.io](https://github.com/munzfuss/munzfuss.github.io/issues).

## Licence

GPL-3.0 — see [LICENSE](LICENSE).
