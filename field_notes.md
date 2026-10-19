# Dark-Sky Field Notes

**A field guide for astronomy-club members planning stargazing trips in US national parks**

Compiled: 2026-10-19 (UTC) | Sources: arXiv search, National Park Service API, web image search
Maintained for the club's dark-sky bulletin

This issue covers three things: the science of night-sky brightness and light pollution; the practical side of visiting four of the darkest national parks in the United States; and a curated set of night-sky photographs to illustrate the bulletin. Every count quoted below was computed by running a script over the actual tool outputs — not estimated by hand.

---

## 1. How We Searched

### 1.1 Science side: arXiv survey

We attacked night-sky brightness and light pollution from three angles, each with its own arXiv queries ("past year" filter unless noted). arXiv skews heavily toward physics, astronomy and CS, so several ecology-phrased queries returned little or nothing; where a query returned no usable results we re-phrased it and searched again until each angle had a usable hit list.

**Angle 1 — Sky-brightness measurement methods** (5 queries, **33 raw results**)

| Query | Results |
|---|---|
| night sky brightness measurement methods | 10 |
| all-sky brightness monitoring sky quality meter skyglow | 2 |
| night sky brightness photometry measurements dark sky sites | 10 |
| sky brightness atlas light pollution modelling skyglow | 1 |
| satellite constellation brightness astronomy observations impact *(supplementary)* | 10 |

**Angle 2 — Effects on wildlife and ecosystems** (7 queries, **32 raw results**)

| Query | Results |
|---|---|
| light pollution effects on wildlife and ecosystems | 10 |
| artificial light at night ecological impacts insects birds | 8 |
| ecological light pollution nocturnal animals ecology ALAN | 2 |
| urban night lighting ecology moth bat bird migration | 0 |
| artificial light at night biodiversity insect decline | 1 |
| light pollution effects on ecosystems animals plants | 10 |
| light pollution human health circadian exposure *(supplementary)* | 1 |

**Angle 3 — Satellite remote sensing of artificial light at night (ALAN)** (4 queries, **19 raw results**)

| Query | Results |
|---|---|
| satellite remote sensing artificial light at night | 10 |
| VIIRS nighttime lights light pollution monitoring urban | 1 |
| artificial light at night environmental remote sensing data | 8 |
| skyglow diffuse urban light measurements cities | 0 |

**Total raw results pooled across the three angles: 84** (33 + 32 + 19).

### 1.2 Pooling, deduplication and selection

1. All results were pooled into one list of 84 entries (paper identity = arXiv id).
2. Near-duplicate removal: the pooled set was passed to a semantic near-duplicate filter and collapsed to **67 unique papers** (17 duplicate instances dropped — e.g. the Portugal "Aldeias do Xisto" dark-sky case study surfaced under all three angles, and satellite-megaconstellation papers appeared under two).
3. The 67 unique papers were ranked against the brief ("night-sky brightness and artificial light at night: how sky brightness and skyglow are measured, the effects of ALAN on wildlife and ecosystems, and satellite remote sensing of ALAN") with a reranker, then the top matches were screened by hand for topical fit.
4. Final shortlist: **12 papers** (within the 8-12 target), balanced across the three angles — 5 on measurement methods, 3 on wildlife/ecosystem effects, 4 on satellite remote sensing.

> Note on "recent": the "past year" filter was applied to the fresh 2025-2026 preprints, but to keep the ecology angle (where arXiv coverage is thin) and the measurement-methods canon usable, a few classic works from 2014-2023 were admitted from angle-specific searches without the time filter. Each entry below is tagged with the angle(s) it entered under.

### 1.3 Parks side

Four national parks renowned for dark skies were selected, with **Acadia as one of them**: **Acadia** (ME), **Big Bend** (TX), **Death Valley** (CA/NV) and **Great Basin** (NV). All four are International Dark Sky Parks / hold dark-sky credentials and list both "Astronomy" and "Stargazing" among their NPS activities; Acadia additionally hosts the Acadia Night Sky Festival each autumn.

For each park we queried the National Park Service API for (a) **visitor centers** — where members pick up maps and ask rangers about astronomy programs — and (b) **current alerts** relevant to a night visit. Everything reported in Section 3 is exactly what the park service returned on 2026-10-19; nothing has been assumed or filled in from general knowledge. Two parks (Big Bend and Death Valley) returned fewer visitor centers than might be expected for their size — that is what the API returned, and we report it as such.

### 1.4 Image side

One night-sky image search per park (4 searches × 10 results = **40 raw images**). Sixteen representative candidates were carried into a semantic near-duplicate filter (16 → 5 distinct themes), and the best 5 covering all four parks were kept — one per park plus a second Acadia pick. URLs in Section 4.

---

## 2. Paper Shortlist (12 papers)

Ordered by relevance to the guide's brief. "Angle" marks which search angle(s) each paper entered the pool under. All links are to the arXiv abstract pages.

| # | arXiv id | Title | Authors | Why it's in the guide | Angle |
|---|---|---|---|---|---|
| 1 | [2610.09028](https://arxiv.org/abs/2610.09028) | Assessment of sky brightness in central Portugal: the Dark Sky destination "Aldeias do Xisto" case study | Domingos Barbosa et al. | The closest thing to our own brief: a certified dark-sky destination characterized by combining night-time satellite imagery (VIIRS DNB) with ground-based Sky Quality Meter field testing — 2012-2017 monitoring methodology for sky brightness and light pollution, plus the darkest site in the region at 21.4 mag/arcsec². | 1, 2, 3 |
| 2 | [1908.05234](https://arxiv.org/abs/1908.05234) | Sky Brightness Measurements and Ways to Mitigate Light Pollution in Kirksville, Missouri | Vayujeet Gokhale et al. | Hands-on methods with Unihedron Sky Quality Meters, comparing a light-polluted college town with Anderson Mesa near Flagstaff — the world's first International Dark Sky City — plus concrete mitigation strategies. | 1 |
| 3 | [2503.04937](https://arxiv-on-more
