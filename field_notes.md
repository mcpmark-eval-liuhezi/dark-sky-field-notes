# Dark-Sky Field Notes

**A field guide for astronomy-club members planning stargazing trips in US national parks**

Compiled: 2026-10-19 | Sources: arXiv (via search), National Park Service API, web image search
Companion README: this repository | Maintained for the club's dark-sky bulletin

This guide covers the science of night-sky brightness and light pollution, the practical side of visiting four of the darkest national parks in the United States, and a curated set of night-sky photographs to illustrate the bulletin. All bookkeeping numbers were computed by script (see the last section), not estimated by hand.

---

## 1. How We Searched

### 1.1 Science side: arXiv survey

We attacked the topic from several angles, each with its own arXiv search queries:

**Angle 1 — Sky-brightness measurement methods** (4 queries, 31 raw results)
- "night sky brightness measurement methods" (past year)
- "night sky brightness monitoring sky quality light pollution measurement" (past year)
- "skyglow all-sky photometry light pollution monitoring" (past year)
- "sky quality meter SQM all-sky camera light pollution atlas measurements"

**Angle 2 — Effects on wildlife and ecosystems** (5 queries, 33 raw results)
- "light pollution effects on wildlife and ecosystems" (past year)
- "artificial light at night ecological effects insects birds animals" (past year)
- "ecological light pollution nocturnal wildlife impacts artificial night lighting" (past year — returned no results)
- "light pollution ecology insects bats birds nocturnal behavior"
- "biodiversity decline artificial light at night ecological consequences"

**Angle 3 — Satellite remote sensing of artificial light at night** (3 queries, 22 raw results)
- "satellite remote sensing artificial light at night" (past year)
- "artificial light at night VIIRS nighttime lights remote sensing" (past year)
- "mapping global nighttime lights VIIRS DMSP analysis light emissions"

**Angle 4 — Supplementary: astronomy outreach in dark-sky places** (1 query, 9 raw results)
- "star party astronomy outreach dark sky parks public engagement"

### 1.2 Pooling, deduplication and selection

Results from all angles were pooled into a single candidate list and deduplicated by arXiv identifier, which collapsed the overlapping hits (the Portugal case study, the Ethiopia site-search study and a handful of others appeared under more than one angle). Each unique paper was then screened for topical fit and ranked with a reranker against the brief — "field guide for an astronomy club planning dark-sky stargazing trips in US national parks: how night sky brightness is measured and monitored, the effects of light pollution on wildlife and ecosystems, and satellite remote sensing of artificial light at night" — and the 12 best-matching papers were kept for the shortlist (target 8-12).

### 1.3 Parks side

Four national parks renowned for dark skies were selected, with Acadia as a required pick: **Acadia** (Maine), **Big Bend** (Texas), **Death Valley** (California/Nevada) and **Great Basin** (Nevada). For each park we queried the National Park Service API for (a) visitor centers — where members pick up maps and ask rangers about astronomy programs — and (b) current alerts that could matter for a night visit. Everything reported below is exactly what the park service returned on 2026-10-19; nothing has been assumed or filled in from general knowledge.

### 1.4 Image side

Eight representative night-sky photographs were searched per park (32 candidates in total). The pool was deduplicated with a semantic near-duplicate filter (32 → 8 distinct), then the best 5 covering all four parks were kept and their URLs are listed in Section 4.

---

## 2. Paper Shortlist (12 papers)

Ordered roughly by relevance to the guide's brief. arXiv ids given; the three angle tags mark where each paper entered the pool.

| # | arXiv id | Title | Why it's in the guide | Angles |
|---|----------|-------|------------------------|--------|
| 1 | 2610.09028 | Assessment of sky brightness in central Portugal: the Dark Sky destination "Aldeias do Xisto" case study | Combines night-time satellite imagery (VIIRS DNB) with ground-based Sky Quality Meter field testing to infer sky brightness, and establishes a repeatable methodology for monitoring light pollution and sky brightness in a certified dark-sky destination. Supported the region's 2018 certification as a Dark Sky Starlight Tourist Destination. | 1, 3 |
| 2 | 1908.05234 | Sky Brightness Measurements and Ways to Mitigate Light Pollution in Kirksville, Missouri | Measures sky brightness with Unihedron sky quality meters in and around Kirksville, Missouri and at Anderson Mesa near Flagstaff, Arizona (the world's first International Dark Sky City), and describes practical mitigation strategies. | 1 |
| 3 | 1709.09558 | Measuring night sky brightness: methods and challenges | The methods review: covers SQM-style devices, DSLR/all-sky photometry and the interpretation pitfalls of each. Recommends supplementing long-term time series with periodic all-sky sampling by a calibrated camera system and calibrated luxmeters/luminance meters. | 1 |
| 4 | 2501.06538 | Astronomy and Society: The Road Ahead | Road-map for the astronomy-society connection, including outreach via star parties and public engagement — directly relevant to how our club interacts with park astronomy programs. | 4 |
| 5 | 2310.19753 | Severity of light pollution and its multifaceted impact: A mini review on the dark side of light | Mini review of the adverse effects of light pollution: disoriented migrating birds colliding with buildings or falling prey to predators, ecosystem impacts, and human well-being. | 2 |
| 6 | 2007.01150 | Light pollution in USA and Europe: The good, the bad and the ugly | The authors of the world atlas of artificial night-sky brightness assess light pollution in the USA and Europe, quantifying population under polluted skies and the range of adverse effects on human health and natural ecosystems (insects, birds, bats, sea turtles). | 2 |
| 7 | 2608.04064 | The Astronomy of Halakhic Nightfall: Calculating Ts'eit HaKokhavim and Motsa'ei Shabbat | A worked application of sky-brightness values (natural dark-sky brightness plus light-pollution contribution) to determine when stars first become visible at a site — a nice illustration of why darkness matters at the moment of first sighting. | 1 |
| 8 | 1701.05019 | Sky Quality Meter measurements in a colour changing world | Correlates SQM readings with Johnson photometric bands and human visual perception under different lighting technologies — key to interpreting the SQM numbers our members see in park sky-quality reports as lighting shifts to LEDs. | 1 |
| 9 | 2410.07280 | Action Research in Astronomy and Ecology: The observatory of the night environment in Grenoble | Documents a joint astronomy-ecology "night environment observatory" treating artificial light at night as one of the drivers of biodiversity loss, with a model for how astronomers and ecologists monitor together. | 2 |
| 10 | 2610.10834 | Systematic non-compliance of satellite megaconstellations with IAU brightness limits | How satellite trails and reflected sunlight brighten the night sky and degrade dark-sky observing — including the prediction that roughly one in three 30-second twilight exposures at the Vera C. Rubin Observatory will carry a satellite trail. Relevant background for satellite-spotting during park star parties. | 1 |
| 11 | 2609.33859 | The Potential of Nighttime Light Imagery for Detailed Local Economic Analysis | Methodology for using satellite nighttime-light imagery at fine local scales — the remote-sensing angle on how artificial light at night is mapped from orbit. | 3 |
| 12 | 2507.02019 | Natural experiments from Earth Hour reveal urban night sky being drastically lit up by few decorative buildings | All-sky camera analysis of Earth Hour switch-offs showing how a small number of buildings drive urban sky brightening, with implications for targeted light-pollution mitigation. | 1 |

*Also surfaced but cut from the shortlist: a rich cluster of DMSP/VIIRS calibration and nighttime-lights reconstruction papers (e.g. 2603.16385, 2307.07366, 2508.00590, 2402.15659, 2109.06913, 2403.00112, 2305.12009, 2609.33861), Colombia's all-sky night-sky characterization (2503.04937), and additional SQM/skyglow studies (1512.06694, 2202.08258, 1807.10593, 1602.04537) — strong papers, but the twelve above span the guide's three angles plus outreach with the least redundancy.*

---

## 3. The Four Parks

Park codes in parentheses. Visitor centers and alerts are verbatim from the National Park Service API on 2026-10-19.

### 3.1 Acadia National Park (acad) — Maine

**Why here:** the east coast's flagship dark-sky park, home of the annual Acadia Night Sky Festival; Cadillac Mountain and Sand Beach host star parties, and rangers run astronomy programs in season.

**Visitor centers (6 returned by the park service):**

1. **Hulls Cove Visitor Center** — Acadia's main visitor contact station and transportation hub (May into October), adjacent to an entrance of the 27-mile Park Loop Road and a key stop on the fare-free Island Explorer bus system. 25 Visitor Center Road, Bar Harbor, ME 04609. Open 8:30 am - 4:30 pm daily in season (winter information moves to the Bar Harbor Chamber of Commerce). Phone: 207-288-3338.
2. **Sieur de Monts Nature Center** — visitor services, hiking information and interactive exhibits; trailhead for many Sieur de Monts-area trails. 47 Sweet Water Circle, Bar Harbor, ME 04609. Open 9 am - 5 pm, June 14 through Oct 12, 2026.
3. **Acadia Gateway Center** — intermodal transit and welcome center on Route 3 in Trenton, three miles north of Mount Desert Island; Island Explorer bus stop, parking, tourism information, store, restrooms. Open 8 am - 6 pm, May 20 through Oct 12, 2026.
4. **Islesford Historical Museum** — cultural history exhibits on Little Cranberry Island (accessible only by boat); closes for the season Sep 19, 2026.
5. **Schoodic Institute Welcome Center at Rockefeller Hall** — Schoodic Peninsula, off the one-way loop road; exhibits about the old Navy base plus park information. 9 Atterbury Circle, Winter Harbor, ME 04693. Open 10 am - 5 pm daily in season. *(Note: the Schoodic Peninsula is one of Acadia's best dark-sky areas, but see the road-closure alert below.)*
6. **Winter Information: Bar Harbor Chamber of Commerce** — 2 Cottage Street, Bar Harbor (corner of Cottage and Main); serves as the park's information point from Nov 1 into early May, 8 am - 4 pm daily.

**Current alerts (3, all "Park Closure (area inaccessible)"):**

1. **Eastern Section of Beech Mountain Loop Trail Closed for Repairs** — starting Sept 21, the eastern section of the Beech Mountain Loop Trail is closed from a junction just beyond the parking lot to just below the summit at the fire tower. Three alternate routes to the summit are available: the outer loop of the Beech Mountain Loop Trail, Beech South Ridge Trail and Beech West Ridge Trail. (Updated 9/30/2026)
2. **Schoodic Mountain Road Closed for Repairs** — starting Aug 31, Schoodic Mountain Road is closed from Schoodic Loop Road to the summit of Schoodic Head. Workers will be operating heavy equipment for resurfacing, regrading and ditching. (Updated 9/30/2026)
3. **Southern Section of Ocean Path Closed for Repairs** — starting Aug 31, a section of Ocean Path is closed from a trailhead across from the Otter Point parking lot to the trail's southern terminus. (Updated 9/16/2026)

**Night-visit relevance:** the Schoodic Mountain Road closure blocks vehicle access to a prime dark-sky peninsula summit; plan Otter Cliff / Sand Beach-area observing instead given the Ocean Path closure near Otter Point.

### 3.2 Big Bend National Park (bibe) — Texas

**Why here:** an International Dark Sky Park with certified dark skies on the US-Mexico border; the park runs "Stars over Big Bend" interpretive programs and works with local partners on lighting retrofits.

**Visitor centers (5 returned by the park service):**

1. **Persimmon Gap Visitor Center** — northern entrance, in a low pass between the Santiago Mountains; park orientation, exhibits, bookstore, restrooms; entrance fees payable here. On Hwy 385, 42 miles south of Marathon, TX. Busy-season hours: Nov 1 - Apr 30, 10 am-12:30 pm and 1:30-4 pm (closed for lunch). Phone: 432-477-2251.
2. **Panther Junction Visitor Center** — "the best place to begin your visit"; backcountry and river-use permits, entrance fees, exhibits on geology and natural/cultural history, park movie on request, bookstore, U.S. Post Office and restrooms. Central in the park, 68 miles south of Marathon. Open all year 8:30 am - 5 pm (Christmas: 8:30 am-12 pm). Phone: (432) 477-1158.
3. **Chisos Basin Visitor Center** — interactive exhibits on plants, animals and birds of the Chisos Mountains; permits and fees; bookstore, restrooms, water faucet. In the Basin developed area, 10 miles southwest of Panther Junction. Open all year 8:30 am - 4 pm, closed for lunch 12-1 pm.
4. **Castolon Visitor Center** — in the Castolon Historic District along Ross Maxwell Scenic Drive, about 8 miles from the Santa Elena Canyon trailhead; housed in the historic Garlick House. Open seasonally, November through April, 10 am - 4 pm daily (closed for lunch).
5. **Rio Grande Village Visitor Center** — 0.25 miles north of the Rio Grande Village developed area, 20 miles east of Panther Junction; new Rio Grande exhibits, raised-relief map, bronze wildlife sculptures; river-use permits. Open seasonally Nov 1 - Apr 30, 9 am - 4:30 pm (closed for lunch).

**Current alerts (2, both "Information (non-emergency)"):**

1. **Big Bend is a NO DRONE Zone** — the use of drones is prohibited in Big Bend National Park. "Thank you for preserving the peace and tranquility of Big Bend." (Updated 12/13/2022)
2. **Bringing a Pet to Big Bend?** — pets are not allowed on park trails, in the backcountry, or on the river; pets are allowed only where vehicles can go and may not be left unattended. (Updated 5/4/2022)

**Night-visit relevance:** no closures — both alerts are standing rules, but the no-drone rule matters for any member thinking of aerial astrophotography rigs, and pet rules matter for those bringing dogs on night walks.

### 3.3 Death Valley National Park (deva) — California/Nevada

**Why here:** a Gold Tier International Dark Sky Park — the darkest tier — with ranger-led night-sky programs at Furnace Creek and the Harmony Borax Works, plus annual astronomy events.

**Visitor centers (2 returned by the park service):**

1. **Furnace Creek Visitor Center** — "the central hub for all things Death Valley": pay the entrance fee, speak with a ranger about trip plans, Junior Ranger program, 20-minute park film, museum displays, bookstore. Furnace Creek, CA 92328. Open every day of the year, including holidays, 8 am - 5 pm. Phone: 760-786-3200.
2. **Stovepipe Wells Ranger Station** — talk with a ranger and pay the entrance fee; "this is a contact station, not a full visitor center. Hours vary — not open every day. Please call (760) 786-3200 for today's hours."

**Current alerts (1, "Information (non-emergency)"):**

1. **Gas Pumps at Panamint Springs Resort are Closed at Night** — gasoline is available at Panamint Springs Resort from 7 am-9:30 pm daily; gas is available at Furnace Creek and Stovepipe Wells 24 hours. (Updated 1/27/2025)

**Night-visit relevance:** directly relevant — fuel up before a late observing session; Panamint Springs pumps close at 9:30 pm, Furnace Creek and Stovepipe Wells pumps run 24 hours.

### 3.4 Great Basin National Park (grba) — Nevada

**Why here:** one of the darkest places in the lower 48, with an astronomy festival each September, dedicated astronomy amphitheater and volunteer-led telescope nights; also home to Lehman Caves.

**Visitor centers (2 returned by the park service):**

1. **Lehman Caves Visitor Center** — 5.5 miles up from the town of Baker, NV (end of NV-488); plan your visit, purchase cave tour tickets, park movie, and exhibits about the caves *and the darkness of Great Basin National Park*. Open daily year-round 8 am - 5 pm. Phone: (775) 234-7510.
2. **Great Basin Visitor Center** — just north of Baker on the west side of NV-487; ranger-staffed information desk, ecology and history exhibits, theater with the park film, brochures. Open daily in summer, 8 am - 5 pm. Phone: (775) 234-7520.

**Current alerts (4 — three "Park Closure (area inaccessible)", one "Caution (potential hazard)"):**

1. **Wheeler Peak Scenic Drive Seasonal Closure** — Wheeler Peak Scenic Drive is closed to vehicle traffic at the Summit Trailhead due to impacts from winter weather. (Updated 10/17/2026)
2. **Dump Station Seasonal Closure** — due to incoming winter weather, the park's dump station closed for the season at 12 pm on Friday, October 9, 2026; after that time there is no potable water available inside the National Park. (Updated 10/8/2026)
3. **Wheeler Peak Campground Seasonal Closure** — the Wheeler Peak Campground closed for the season on Saturday, October 10, 2026; availability in the park's other campgrounds can be found on recreation.gov. (Updated 10/8/2026)
4. **No Potable Water in Park Campgrounds** — there currently is no water available in any campground in Great Basin National Park. Water is available at the RV Fill and Dump Station, the Great Basin and the Lehman Caves Visitor Centers, as well as some local businesses. (Updated 6/2/2026)

**Night-visit relevance:** critical for fall/winter trips — the Wheeler Peak Scenic Drive gate closure blocks driving to the high trailheads near the park's darkest skies, and there is **no water anywhere in the campgrounds** (fill up at the visitor centers or in Baker).

---

## 4. Image Picks (5 photos, all four parks covered)

From 32 searched candidates → 8 distinct after near-duplicate removal → best 5 kept:

1. **Acadia — Night sky over Acadia (First Light)**
   https://newengland.com/wp-content/uploads/First-Light-1.jpg
2. **Acadia — Eagle Lake stars**
   https://upload.opalcollection.com/app/uploads/2014/09/10152340/Eagle-Lake-Stars-321.jpg
3. **Big Bend — View the night sky (NPS)**
   https://www.nps.gov/common/uploads/cropped_image/primary/F5FD831D-EA0D-2A23-2B28A71097DC9A5E.jpg?width=1300&quality=90&mode=crop
4. **Death Valley — Milky Way (NPS, photo by Duriscoe)**
   https://www.nps.gov/deva/learn/nature/images/DeathValley_B-W_MilkyWay_Duriscoe.jpg
5. **Great Basin — Stargazing in Great Basin National Park (Discover Great Basin)**
   https://images.squarespace-cdn.com/content/v1/5ab2dbdd96d4556aa344b3e1/1524501874741-A4XHCDMS8SKSLLV6DPMT/Chet+Kalinowska_05.jpg

All five were returned by image search with these exact URLs and dimensions; the two NPS-hosted images are public-domain park-service photos, the others are from travel publications and should be credited if the club reprints them.

---

## 5. Computed Counts

All numbers below were computed by running a script over the collected results (not counted by hand). Script run: 2026-10-19.

**Science side (arXiv):**

| Metric | Value |
|--------|-------|
| Raw results, Angle 1 (sky-brightness measurement methods) | 31 |
| Raw results, Angle 2 (wildlife and ecosystem effects) | 33 |
| Raw results, Angle 3 (satellite remote sensing of ALAN) | 22 |
| Raw results, supplementary Angle 4 (outreach) | 9 |
| **Total raw results (3 science angles)** | **86** |
| **Total raw results (all 4 angles)** | **95** |
| Unique papers after dedup, by arXiv id (3 science angles) | 71 |
| Unique papers after dedup (all 4 angles) | 79 |
| On-topic candidates after topical screen (3 science angles) | 35 |
| Papers kept in final shortlist (target 8-12) | **12** |

**Parks side (NPS API):**

| Park | Visitor centers returned | Alerts returned |
|------|--------------------------|-----------------|
| Acadia (acad) | 6 | 3 |
| Big Bend (bibe) | 5 | 2 |
| Death Valley (deva) | 2 | 1 |
| Great Basin (grba) | 2 | 4 |
| **Totals** | **15** | **10** |

**Images:**

| Metric | Value |
|--------|-------|
| Candidates searched (8 per park × 4 parks) | 32 |
| Distinct after near-duplicate removal | 8 |
| **Final images kept** | **5** |

---

## 6. Publication Note

Published as the `dark-sky-field-notes` repository. The guide was committed to a dedicated `guide` branch and landed on the default branch (`main`) via pull request **"Dark-sky field notes"**, which was merged after review.

*Note on location: the repository was created under the organization account (`mcpmark-eval-liuhezi`) rather than a personal account, because the GitHub credential in use does not have permission to create repositories, branches or gists in personal accounts. The repository contents, branch workflow, pull request title and merge are exactly as specified.*
