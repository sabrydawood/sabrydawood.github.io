# Fonts published with these pages

The two `.woff2` files here are **IBM Plex Sans Arabic**, Copyright 2019 IBM
Corp., licensed under the SIL Open Font License 1.1 — the full licence text is
in `LICENSE-ibm-plex-sans-arabic.txt` next to this file, and both travel with
the fonts into every published build because OFL clause 2 requires it.

**They are modified.** The Arabic Presentation Forms entries (U+FB50–FDFF,
U+FE70–FEFF) have been deleted from the `cmap` table. No outline, metric or
OpenType layout table is touched; shaping runs through GSUB and is unaffected.
The modification exists for the PDF press, where those cmap entries caused a
client's own company name to come out of the finished file unsearchable. These
pages reuse the same faces rather than carrying a second copy.

Because the version is modified and IBM Plex declares the Reserved Font Name
"Plex", the faces are named **Waraq Arabic Text** in their name tables and in
the CSS. OFL 1.1 clause 3 requires that; it is not branding.

Provenance, upstream version and the exact transformation are recorded in
`product/press/fonts/allowlist.json` and `product/press/fonts/LICENSES.md`.
