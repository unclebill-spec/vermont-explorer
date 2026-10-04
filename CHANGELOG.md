# Vermont Explorer — change log

Newest first. Times are ET.

## 2026-10-04
- 08:08 ET: State switcher: shrinks and scrolls sideways on narrow phones (10 maps)
- 07:39 ET: State switcher: add New Hampshire (10 maps); border items now come from the New Hampshire map (NH homes and RN jobs at this map's caps)
- 06:21 ET: State switcher: add Utah (9 maps)

## 2026-10-03
- 21:01 ET: State switcher: add Idaho (8 maps)
- 18:27 ET: State switcher: Montana and Wyoming added
- 17:14 ET: Pin the bottom Top 10 pill row snug against the bottom-left edge of the map (5 px + safe area, same place on every window size, after cards open/close, resizes and full screen); zoom, scale and OpenStreetMap credit move up with it and stay uncovered; on short windows (e.g. 1366x600 above the Windows taskbar) the right-hand filter column now fits above Areas instead of being cut off
- 16:38 ET: Fix the bottom Top 10 pill row on desktop: after a window resize or full-screen change while a card was open the pills were measured while hidden and collapsed into two tiny overlapping pills at the left; the row now re-measures when it is shown again, pills size to their full titles and the row widens to hold exactly 3 whole pills (one pill per mouse-wheel notch, swipe and snap on phones unchanged)
- 15:58 ET: Bargains are purple with a star everywhere: the right-side Bargain filter button (column and landscape wheel), the Map key heading, the deal note on cards and the Top 10 'Bargain' mark now use the same purple star (#8e24aa) as the bargain pins and Deals pill instead of the yellow emoji
- 15:40 ET: Border items: pins up to ~15 mi outside the state line that meet this map's own criteria, from Massachusetts (homes, jobs, hospitals, graded schools...) plus New Hampshire, New York and Québec. Same icons, filters, Top 10s and share links; each card is tagged with its state; county/town stats and appeal scores unchanged (explorer/border.json, shared border_build.py + build.py hook + app.js/style.css)
- 14:41 ET: Purple bargain icon (pins, groups, Map key, Deals pill); bottom Top 10 pills show exactly 3 whole buttons and snap one button or one page at a time; right-side filter buttons scroll with the mouse wheel and wheel events over them no longer zoom the map
- 14:09 ET: Add ski areas and notable mountain peaks layers: ski/peak icons, cards with trails, lifts, vertical, snowfall, season, ticket and pass prices (season + source labeled), discounts, special days; peaks with elevation, prominence, activities, estimated summit weather; Ski and Peaks solo buttons, Map key, zoom tiers, share links #ski= / #peak=
- 13:39 ET: Phase 4: 56 attractions (24 state-park campgrounds, 29 museums, ECHO aquarium, VINS raptor center, Jay Peak Pump House indoor water park), 7 airports (BTV, RUT + PBG, LEB, ALB, MHT, BOS), 13 businesses for sale under $1M (Crexi, hand-reviewed; no odd buildings under $600k listed), waterfalls and hiking trails (Wikidata + Wikipedia + OSM Nominatim)
- 13:32 ET: Phase 3: jobs - 204 permanent RN jobs (163 pass the default filter; 102 list pay, 32 a sign-on bonus) from UVM Health (Workday), Dartmouth Health SVMC + Mt. Ascutney, Gifford, Rutland Regional (HealthcareSource), Brattleboro, Springfield, Grace Cottage (Paylocity), Northwestern (UKG Pro), Copley (iCIMS); 98 travel RN jobs at 11 hospitals (Vivian + Advantis; same OR/cath/OB/NICU/peds exclusions). North Country and NVRH not collected (block automated browsers).
- 13:26 ET: Phase 2: homes at the KY caps - 255 listings, one category each: 107 on 5+ acres ($300k-$500k), 145 on 1+ acre (3bd/2ba, under $425k), 3 near-hospital (1,600+ sq ft, 3bd/2ba, under $325k, <= 10 min to a 24/7 ER); 15 bargains; Deals top 10; 1,019 photos. No cabin category.
- 12:45 ET: Phase 1: Vermont base map - 256 town blocks with appeal scores, 28 hospitals (UVM Level I + NH/MA/NY border trauma centers), 303 schools graded by SEDA 2025 supervisory union, BLS OEWS 2025 RN wages, climate normals, parks/waterfalls (Wikidata), colleges, Compare areas (Burlington, South Burlington, Colchester, Rutland, Bennington vs KY/TN); state switcher KY/MA/ME/TN

