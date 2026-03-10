---
description: Where to get exoplanet tables, light curves, and analysis-ready data.
---

# Catalogs & data

### In this wiki

These pages help you interpret catalog fields and measurement provenance.

* [Key terms & definitions](basics/key-terms-and-definitions.md)
* [Naming & designations](basics/naming-and-designations.md)
* [Measuring exoplanet properties](basics/measuring-exoplanet-properties.md)
* [Detection methods (overview)](detection-and-confirmation/detection-methods-overview.md)

### Exoplanet catalogs

* [NASA Exoplanet Archive](https://exoplanetarchive.ipac.caltech.edu/)
* [Exoplanets.org](https://exoplanets.org/)
* [exoplanet.eu](https://exoplanet.eu/)

### Light curves and time-series

* [MAST (Mikulski Archive for Space Telescopes)](https://mast.stsci.edu/) — Kepler, K2, TESS, HST, JWST, more.
* [Lightkurve docs](https://docs.lightkurve.org/) — Python toolkit for Kepler/TESS light curves.

### High-level analysis tools

* [Astroquery](https://astroquery.readthedocs.io/en/latest/) — scripted access to common archives.
* [Astropy](https://www.astropy.org/) — the base layer for most Python astronomy workflows.

### Practical workflow

1. Pull target metadata from NASA Exoplanet Archive.
2. Fetch photometry from MAST.
3. Reproduce the transit fit.
4. Compare with the discovery paper on ADS.

<details>

<summary>Notes on “confirmed” vs “candidate”</summary>

A catalog entry might be a \*\*planet candidate\*\* (signal consistent with a planet) or a \*\*confirmed planet\*\* (validated or mass-confirmed).

Missions and catalogs use different labels. Always read the linked reference.

</details>
