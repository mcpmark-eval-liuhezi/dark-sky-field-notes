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

One night-sky image search per park (4 searches × 10 results = **40 raw images**). Sixteen representative candidates were carried into a semantic near-duplicate filter (16 → 5 distinct themes), and the best 5 covering all four parks were kept — one per park plus a second Great Basin pick. URLs in Section 4.

---

## 2. Paper Shortlist (12 papers)

Ordered by relevance to the guide's brief. "Angle" marks which search angle(s) each paper entered the pool under. All links are to the arXiv abstract pages.

| # | arXiv id | Title | Authors | Why it's in the guide | Angle |
|---|---|---|---|---|---|
| 1 | [2610.09028](https://arxiv.org/abs/2610.09028) | Assessment of sky brightness in central Portugal: the Dark Sky destination "Aldeias do Xisto" case study | Domingos Barbosa et al. | The closest thing to our own brief: a certified dark-sky destination characterized by combining night-time satellite imagery (VIIRS DNB) with ground-based Sky Quality Meter field testing — a 2012-2017 monitoring methodology for sky brightness and light pollution, with the darkest site in the region at 21.4 mag/arcsec². | 1, 2, 3 |
| 2 | [1908.05234](https://arxiv.org/abs/1908.05234) | Sky Brightness Measurements and Ways to Mitigate Light Pollution in Kirksville, Missouri | Vayujeet Gokhale et al. | Hands-on methods with Unihedron Sky Quality Meters, comparing a light-polluted college town with Anderson Mesa near Flagstaff — the world's first International Dark Sky City — plus concrete mitigation strategies. | 1 |
| 3 | [2503.04937](https://arxiv.org/abs/2503.04937) | A First Quantitative Characterization of Colombian Night Sky Through All-Sky Photometry | J. P. Uchima-Tamayo et al. | Modern all-sky imaging methods: Sky Quality Camera data across four sites, measuring surface brightness and correlated colour temperature — a template for how a club could survey a candidate dark site. | 1 |
| 4 | [1807.10593](https://arxiv.org/abs/1807.10593) | Using all-sky differential photometry to investigate how nocturnal clouds darken the night sky in rural areas | Andreas Jechow et al. | Shows how clouds and weather change what "dark" means on a given night — crucial for planning whether a trip is worth the drive, and for interpreting sky-quality readings under overcast skies. | 1, 2 |
| 5 | [1703.08484](https://arxiv.org/abs/1703.08484) | Measuring Light Pollution with Fisheye Lens Imagery from a Moving Boat, A Proof of Concept | Andreas Jechow et al. | Proof of concept for cheap, portable fisheye-lens sky-brightness mapping in remote/hard-to-reach terrain — applicable to shoreline and backcountry sites like ours. | 1 |
| 6 | [2310.19753](https://arxiv.org/abs/2310.19753) | Severity of light pollution and its multifaceted impact: A mini review on the dark side of light | Pranjal Choudhary, Sudhish Kumar | Mini review of the adverse effects of light pollution on human well-being and the wider environment — including disoriented migrating birds colliding with buildings. | 2 |
| 7 | [2311.02098](https://arxiv.org/abs/2311.02098) | Artificial light at night: a global disruptor of the night-time environment | Salvador Bará, Fabio Falchi | The big-picture framing paper from two leading light-pollution researchers: ALAN as a global environmental stressor, and why protecting remote dark refuges matters. | 2 |
| 8 | [1803.09811](https://arxiv.org/abs/1803.09811) | Systematic measurements of the night sky brightness at 26 locations in Eastern Austria | Johannes Puschnig et al. | Long-term SQM monitoring network study, including correlations between light pollution and air pollution and a slight (~2%) decrease in mean zenithal sky brightness at one observatory over 2012-17. | 1 |
| 9 | [2108.07050](https://arxiv.org/abs/2108.07050) | Colour remote sensing of the impact of artificial light at night (II): Calibration of DSLR-based images from the International Space Station | Alejandro Sánchez de Miguel et al. | Satellite/ISS-based colour imaging of ALAN — the dataset behind many of the light-colour maps our members will see, and a bridge between remote sensing and ecological impact. | 3 |
| 10 | [2508.00590](https://arxiv.org/abs/2508.00590) | An Extended VIIRS-like Artificial Nighttime Light Data Reconstruction (1986-2024) | Yihe Tian et al. | Extends the VIIRS nighttime-lights record back to 1986 — the state of the art in long-term ALAN remote sensing, and the basis for trend claims about artificial light at night. | 3 |
| 11 | [2510.05105](https://arxiv.org/abs/2510.05105) | Land use and anisotropy of artificial light observed by night time satellite | S. Otomo et al. | Uses the wide VIIRS-DNB swath to observe city light at multiple angles, linking land use to how light is emitted — explains why parks near urban areas still lose darkness from light scattered sideways and upward. | 3 |
| 12 | [2510.02977](https://arxiv.org/abs/2510.02977) | Multi-faceted light pollution modelling and its application to the decline of artificial illuminance in France | Rolf Buhler et al. | The Otus 3 light-pollution modelling package applied to France, finding a 23% decrease in artificial ground illuminance 2019-2024 — rare good news, and a model for national-scale dark-sky policy evaluation. | 3 |

**Notable cut:** [1401.1200](https://arxiv.org/abs/1401.1200) — the Hong Kong Night Sky Brightness Monitoring Network (urban night sky 15× brighter than rural) — was the 13th-ranked paper and only narrowly missed the 12-paper cap.

---

## 3. The Four Parks — Visitor Centers and Current Alerts

All content in this section is **exactly what the National Park Service API returned on 2026-10-19**.

### 3.1 Acadia National Park (ME) — `acad`

https://www.nps.gov/acad/index.htm | (207) 288-3338 | acadia_information@nps.gov
"Astronomy" and "Stargazing" are both listed NPS activities. Entrance: $35/private vehicle (7 days), plus a $6 timed-entry vehicle reservation for Cadillac Summit Road (road closes to vehicles at 9 pm). Non-US residents 16+ also pay a $100 nonresident fee.

**Visitor centers (6 returned):**

1. **Hulls Cove Visitor Center** — 25 Visitor Center Road, Bar Harbor, ME 04609. Acadia's main visitor contact station and transportation hub from May into October; adjacent to an entrance for the 27-mile Park Loop Road and a key stop for the fare-free Island Explorer bus system. 52 steps to the main entrance (separate accessible entrance). Open daily 8:30 am - 4:30 pm (summer season from the first week of May to end of October; winter information hosted at the Bar Harbor Chamber of Commerce).  
2. **Sieur de Monts Nature Center** — 47 Sweet Water Circle, Bar Harbor, ME 04609. Visitor services, hiking information and interactive exhibits; trailhead for many trails; rangers present spring-summer-fall. Open 9 am - 5 pm June 14 - Oct 12, 2026.  
3. **Acadia Gateway Center** — Route 3, Trenton, ME 04605. Intermodal transit and welcome center 3 miles north of Mount Desert Island; Island Explorer bus stop, day-use parking, 11,000 sq ft welcome center with tourism information, store, waiting area, restrooms. Open 8 am - 6 pm, May 20 - Oct 12, 2026.  
4. **Islesford Historical Museum** — Little Cranberry Island, Islesford, ME 04646 (accessible only by boat). Historical exhibits on life on and around the Cranberry Isles from the 1700s to present. Closes for the season Sep 19, 2026.  
5. **Schoodic Institute Welcome Center at Rockefeller Hall** — 9 Atterbury Circle, Winter Harbor, ME 04693. On Schoodic Peninsula off the one-way loop road; exhibits about the old Navy base plus park information. Open seven days per week, May 1 - Oct 26.  
6. **Winter Information: Bar Harbor Chamber of Commerce** — 2 Cottage Street, Bar Harbor, ME 04609. During winter and spring (typically Nov 1 into early May) information and some pass sales are hosted here. Open 8 am - 4 pm daily.  

**Current alerts (3 returned) — all relevant to night-visit planning:**

- **Eastern Section of Beech Mountain Loop Trail Closed for Repairs** *(Park Closure, area inaccessible; updated 9/30/2026)* — Starting Sept 21, the eastern section of the Beech Mountain Loop Trail is closed from a junction just beyond the parking lot to just below the summit at the fire tower. Three alternate routes to the summit are available: the outer loop of the Beech Mountain Loop Trail, Beech South Ridge Trail and Beech West Ridge Trail.
- **Schoodic Mountain Road Closed for Repairs** *(Park Closure, area inaccessible; updated 9/30/2026)* — Starting Aug 31, Schoodic Mountain Road is closed from Schoodic Loop Road to the summit of Schoodic Head. Workers operating heavy equipment for resurfacing, regrading and ditching.
- **Southern Section of Ocean Path Closed for Repairs** *(Park Closure, area inaccessible; updated 9/16/2026)* — Starting Aug 31, a section of Ocean Path is closed from a trailhead across from the Otter Point parking lot to the trail's southern terminus.

### 3.2 Big Bend National Park (TX) — `bibe`

https://www.nps.gov/bibe/index.htm | (432) 477-2251 | bibe_info@nps.gov
"There is a place in Far West Texas where night skies are dark as coal…" The park is always open — entrances are open 24 hours daily, all year. No EV charging stations in the park (nearest is 130 miles away in Fort Stockton); plan fuel, food and water carefully. Entrance: $30/private vehicle (7 days).

**Visitor centers (5 returned):**

1. **Panther Junction Visitor Center** — park headquarters, center of the park (68 miles south of Marathon; 29 miles east of Study Butte). "The best place to begin your visit" — backcountry and river use permits issued here, entrance fees, exhibits on geology and natural/cultural history, theater with park movie on request, Big Bend Natural History Association bookstore, U.S. Post Office, restrooms, water faucet. Open all year 8:30 am - 5:00 pm.  
2. **Chisos Basin Visitor Center** — Basin developed area, 10 miles southwest of Panther Junction. Interactive exhibits on plants, animals and birds of the Chisos Mountains; backcountry and river permits; bookstore; water faucet on the east side of the building. Open all year 8:30 am - 4:00 pm (closed for lunch 12:00-1:00 pm).  
3. **Persimmon Gap Visitor Center** — northern entrance, on Hwy 385, 42 miles south of Marathon and 26 miles north of Panther Junction. Park orientation and information, exhibits, bookstore, restrooms; entrance fees can be paid here. Busy season (Nov 1 - Apr 30): daily 10:00 am - 12:30 pm and 1:30 - 4:00 pm, closed for lunch 12:30-1:30.  
4. **Castolon Visitor Center** — in the Castolon Historic District along Ross Maxwell Scenic Drive, approx. 8 miles from the Santa Elena Canyon trailhead, inside the historic Garlick House. River use permits, entrance fees, bookstore, nearby restrooms. Open seasonally November through April, daily 10:00 am - 4:00 pm (closed for lunch).  
5. **Rio Grande Village Visitor Center** — 0.25 miles north of the Rio Grande Village developed area, 20 miles east of Panther Junction. New exhibits on the Rio Grande; outdoor ramada with large raised-relief map; life-sized bronze wildlife sculptures; river use permits. Open seasonally Nov 1 - Apr 30, 9:00 am - 4:30 pm (closed for lunch).  

**Current alerts (3 returned):**

- **Boquillas Port of Entry Station Closed Due to Unsafe Conditions** *(Park Closure, area inaccessible; updated 10/19/2026)* — The Boquillas Port of Entry and river crossing is temporarily closed due to excessive rain and unsafe conditions.
- **Big Bend is a NO DRONE Zone** *(Information, non-emergency; updated 12/13/2022)* — The use of drones is prohibited in Big Bend National Park. "Thank you for preserving the peace and tranquility of Big Bend."
- **Bringing a Pet to Big Bend?** *(Information, non-emergency; updated 5/4/2022)* — Pets are not allowed on park trails, in the backcountry, or on the river; pets are allowed only where vehicles can go and may not be left unattended.

### 3.3 Death Valley National Park (CA/NV) — `deva`

https://www.nps.gov/deva/index.htm | 760-786-3200 | deva_information@nps.gov
A certified Gold Tier International Dark Sky Park. The park is open daily, all year. Entrance: $30/private vehicle (7 days). Autumn arrives in late October with warm days, generally clear skies and chilly nights — prime stargazing season.

**Visitor centers (2 returned):**

1. **Furnace Creek Visitor Center** — Furnace Creek, CA 92328. "The central hub for all things Death Valley": pay entrance fee, speak with a ranger about trip plans or questions, Junior Ranger program, 20-minute park film, museum displays, bookstore. Open every day of the year, including holidays, 8:00 am - 5:00 pm.  
2. **Stovepipe Wells Ranger Station** — Stovepipe Wells. "Note: This is a contact station, not a full visitor center. Hours vary — not open every day. Please call (760) 786-3200 for today's hours."

**Current alerts (1 returned):**

- **Gas Pumps at Panamint Springs Resort are Closed at Night** *(Information, non-emergency; updated 1/27/2025)* — Gasoline is available at Panamint Springs Resort from 7 am - 9:30 pm daily. Gas is available at Furnace Creek and Stovepipe Wells 24 hrs.

### 3.4 Great Basin National Park (NV) — `grba`

https://www.nps.gov/grba/index.htm | (775) 234-7331 | grba_interpretation@nps.gov
"Bask in the darkest of night skies" is in the park's own description; the park's listed topics are Animals, Birds, Caves/Caverns/Karst, Night Sky, Astronomy. Entrance fees: none returned by the API. No public transportation is available to, or in, the park.

**Visitor centers (2 returned):**

1. **Lehman Caves Visitor Center** — 5.5 miles up from Baker, NV (end of NV 488). Plan your visit, purchase cave tour tickets, watch the park movie, and "explore exhibits about the caves and the darkness of Great Basin National Park." (775) 234-7510. Open daily year-round, 8:00 am - 5:00 pm.  
2. **Great Basin Visitor Center** — just north of Baker on the west side of NV Highway 487. Information desk staffed by park rangers, exhibits on park ecology and history, theater with park film, brochures. (775) 234-7520. In summer, open daily, 8:00 am - 5:00 pm.  

**Current alerts (4 returned) — the most operationally significant set for a fall/winter night trip:**

- **Wheeler Peak Scenic Drive Seasonal Closure** *(Park Closure, area inaccessible; updated 10/17/2026)* — Wheeler Peak Scenic Drive is closed to vehicle traffic at the Summit Trailhead due to impacts from winter weather.
- **Wheeler Peak Campground Seasonal Closure** *(Park Closure, area inaccessible; updated 10/8/2026)* — The Wheeler Peak Campground closed for the season on Saturday, October 10, 2026. Availability in the other park campgrounds can be found on recreation.gov.
- **Dump Station Seasonal Closure** *(Park Closure, area inaccessible; updated 10/8/2026)* — Due to incoming winter weather, the park's dump station closed for the season at 12:00 pm on Friday, October 9, 2026. After that time, there is no potable water available inside the National Park.
- **No Potable Water in Park Campgrounds** *(Caution, potential hazard; updated 6/2/2026)* — There currently is no water available in any campground in Great Basin National Park. Water is available at the RV Fill and Dump Station, the Great Basin and Lehman Caves Visitor Centers, as well as some local businesses.

### 3.5 At-a-glance

| Park | Code | Visitor centers returned | Current alerts | Night-visit headline |
|---|---|---|---|---|
| Acadia | acad | 6 | 3 | Cadillac Summit Road closes to vehicles at 9 pm (timed-entry reservation required); three trail/road closures on Mount Desert Island and Schoodic |
| Big Bend | bibe | 5 | 3 | Boquillas crossing closed after heavy rain; no drones; pets restricted to vehicle areas |
| Death Valley | deva | 2 | 1 | Gas up before dark — Panamint Springs pumps close 9:30 pm (Furnace Creek and Stovepipe Wells are 24 hrs) |
| Great Basin | grba | 2 | 4 | Wheeler Peak Scenic Drive closed at Summit Trailhead; Wheeler Peak Campground closed; no potable water in campgrounds |

---

## 4. Image Picks (5)

Representative night-sky photographs for the four parks, after semantic near-duplicate removal (40 raw search results → 16 candidates → 5 kept, covering all four parks). URLs point to the source image files; credits per the hosting page.

| # | Park | Image URL | Source / credit |
|---|---|---|---|
| 1 | Acadia | https://www.nps.gov/acad/getinvolved/images/Schoodic-Cove-Imma-Barrera.jpg?maxwidth=1300&autorotate=false | NPS — Stargazing at Acadia (Schoodic Cove, photo by Imma Barrera) |
| 2 | Big Bend | https://www.nps.gov/common/uploads/cropped_image/primary/F5FD831D-EA0D-2A23-2B28A71097DC9A5E.jpg?width=1300&quality=90&mode=crop | NPS — View the Night Sky, Big Bend |
| 3 | Death Valley | https://www.nps.gov/deva/learn/nature/images/DeathValley_B-W_MilkyWay_Duriscoe.jpg | NPS — Lightscape / Night Sky, Death Valley (Milky Way by Dan Duriscoe) |
| 4 | Great Basin | https://travelnevada.com/wp-content/uploads/2024/06/Stargazing-Great-Basin-National-Park-Feat.jpg | Travel Nevada — "Star Sanctuary: Stargazing at Great Basin National Park" |
| 5 | Great Basin | https://www.nps.gov/common/uploads/structured_data/AED0DAB8-0FB7-5710-46732DF80111AC64.jpg | NPS — Comet NEOWISE over ancient bristlecone pine, Great Basin (Charlie Reed) |

Alternates considered but dropped as near-duplicates or weaker: NPS Acadia "Night Skies" gallery photo; Friends of Acadia Schoodic stars; Jason Weingart's Big Bend Milky Way; the Oasis at Death Valley and Sidetracked Death Valley shots; the NPS Great Basin Doso-Doyabi moonlight and Milky-Way-over-Lehman-Caves-VC images; Travel Nevada's second Great Basin image.

---

## 5. Computed Counts (script-tallied)

All numbers below were computed by running code over the recorded tool outputs — not by hand.

| Quantity | Value |
|---|---|
| arXiv queries run (3 angles) | 16 |
| Raw results per angle: measurement methods / wildlife & ecosystems / satellite remote sensing | 33 / 32 / 19 |
| **Raw results pooled (3 angles)** | **84** |
| Duplicate instances dropped while pooling | 17 |
| **Unique papers after near-duplicate removal** | **67** |
| Papers shortlisted for the guide | 12 (5 measurement / 3 wildlife / 4 remote sensing) |
| Parks covered | 4 (Acadia, Big Bend, Death Valley, Great Basin) |
| Visitor centers returned per park (acad / bibe / deva / grba) | 6 / 5 / 2 / 2 |
| **Total visitor centers returned** | **15** |
| Current alerts returned per park (acad / bibe / deva / grba) | 3 / 3 / 1 / 4 |
| Total alerts returned | 11 |
| Raw image search results (4 searches × 10) | 40 |
| Candidates passed to near-duplicate removal | 16 |
| **Images kept** | **5** (covering all 4 parks) |

### Reproduction notes

- Paper pool: 84 raw entries were pooled across the 16 arXiv queries; identity = arXiv id; the semantic near-duplicate filter collapsed these to 67 unique papers, then reranking + manual screening produced the 12-paper shortlist.
- Park data: retrieved from the NPS API on 2026-10-19 via the visitor-centers and alerts endpoints for park codes acad, bibe, deva, grba. Where the API paginated results (Acadia, Big Bend), all pages were fetched so the full returned set is reported.
- Images: four image searches (one per park, 10 results each = 40 raw); 16 representative candidates were deduplicated semantically to 5 distinct picks, chosen to cover all four parks.

*End of field_notes.md*
