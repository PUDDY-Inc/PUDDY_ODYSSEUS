# PUDDY Odysseus

The official typeface of PUDDY, by PUDDY Inc. Free for anyone, for anything, under the SIL Open Font License 1.1.

Copyright (c) 2026, PUDDY Inc. (https://puddystudios.com), with Reserved Font Name "PUDDY". Licensed under the SIL Open Font License, Version 1.1 (OFL.txt).

PUDDY Odysseus is a geometric sans drawn new: every outline is computed from the square, the circle and the triangle, and among its glyphs is Caput Mortuum 🝎 (U+1F74E), the alchemical sign, drawn in the same geometry. This repository is the font's public record: the released font files, the licence, the font log, the release note and the security contact. The construction that computes the outlines is PUDDY Inc.'s own engine and is not part of this repository; only the built files are published.

## The release

PUDDY Odysseus 1.100, released 2026-10-10: four weights, Regular 400, Medium 500, Bold 700 and Black 900, each with the capitals A to Z, the lowercase a to z, the lining figures 0 to 9, basic punctuation and the alchemical sign Caput Mortuum 🝎 (U+1F74E), 88 glyphs with .notdef and space, kerned by rule; each weight in OTF, TTF, WOFF 1.0 and WOFF2, and one variable font across the four. RELEASE.md lists each file with its size and SHA-256, the metrics, the names and the licence line. SHA256SUMS.txt carries the same hashes for `shasum -a 256 -c` on macOS or `sha256sum -c` on Linux. The download page is https://odysseus.puddystudios.com.

Released at the topocentric New Moon in Libra, 2026-10-10 06:59:39 PDT, computed using Puddy Studios' upcoming celestial tracking tool, PUDDY STARMAP.

| file | format |
|---|---|
| `fonts/PUDDYOdysseus-<Weight>.otf` | OpenType, CFF outlines, for each of Regular, Medium, Bold and Black. Desktop: macOS, Windows and Linux |
| `fonts/PUDDYOdysseus-<Weight>.ttf` | OpenType, TrueType outlines, for each weight. Desktop: macOS, Windows and Linux |
| `fonts/PUDDYOdysseus-<Weight>.woff2` | WOFF2, for each weight. The web |
| `fonts/PUDDYOdysseus-<Weight>.woff` | WOFF 1.0, for each weight. The web, for older browsers |
| `fonts/PUDDYOdysseus[wght].ttf` | the variable font, one axis, wght, 400 to 900 |
| `OFL.txt`, `LICENSE` | the licence, the SIL Open Font License 1.1; LICENSE is the same file |
| `FONTLOG.txt` | the font log: what each version carries, version by version |
| `RELEASE.md` | the release note: the weights, the files, their sizes and SHA-256, the font's metrics and names, the licence line |
| `SHA256SUMS.txt` | every released file's SHA-256 |
| `SECURITY.md` | the security contact |

## Install

Install one desktop format, OTF or TTF, not both; install the weights you want, or the variable font alone.

- macOS: double-click each `.otf` file and click Install, or copy the files into `~/Library/Fonts` for you alone or `/Library/Fonts` for every user.
- Windows: select the `.otf` files, right-click and choose Install, or drag them onto Settings > Personalization > Fonts.
- Linux: copy the files into `~/.local/share/fonts` for you alone or `/usr/local/share/fonts` for every user, then run `fc-cache -f`.
- The web: serve the WOFF2 and the WOFF from your own site and declare one face per weight (400, 500, 700, 900), as for the Bold:

```css
@font-face {
  font-family: 'PUDDY Odysseus';
  src: url('/fonts/PUDDYOdysseus-Bold.woff2') format('woff2'),
       url('/fonts/PUDDYOdysseus-Bold.woff') format('woff');
  font-weight: 700;
  font-style: normal;
  font-display: swap;
}
```

The font carries the capitals, the lowercase, the figures, basic punctuation and the sign 🝎; any other character falls to the next font in your stack.

## The licence

    PUDDY Odysseus 1.100 - Copyright (c) 2026, PUDDY Inc. (https://puddystudios.com), with Reserved Font Name "PUDDY". Licensed under the SIL Open Font License, Version 1.1: https://openfontlicense.org

In plain words: anyone may use PUDDY Odysseus for anything, at no cost: a website, an app, a book, a brand, a product you sell. You may change it and share it. Two conditions hold. OFL.txt travels with the font files wherever they go, and the font is not sold by itself. Modified versions stay under the OFL, and a modified version may not use the Reserved Font Name "PUDDY" in its primary font name. PUDDY Inc. grants, under condition 3 of the OFL, that a format conversion or a subset that leaves the design unchanged may keep the name.

## Provenance

Every outline is computed from the square, the circle and the triangle by PUDDY Inc.'s own construction; no other typeface was traced or measured, and no image of any typeface was used. The build is reproducible: the same construction gives byte-identical files, and the release's test rebuilds every file in a fresh folder and compares it byte for byte with the files published here.

## Credits

THE MASTER CUBE (the-master-cube[bot]), PUDDY✵ODYSSEUS (puddy-odysseus[bot]), Colton Dempsey 𓅇, Founder and CEO of PUDDY Inc. (https://github.com/cubedivisiondev).

Designed and built by THE MASTER CUBE for PUDDY Inc.; the glyph U+1F74E, the release of 1.100 and its publication with PUDDY✵ODYSSEUS. Licensed under the SIL Open Font License 1.1.
