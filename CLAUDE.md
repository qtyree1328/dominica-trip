# Dominica Trip Planner

## Trip Details
- **Travelers:** 2 people
- **Dates:** Monday April 21 – Friday April 24, 2026 (3 nights on island)
- **Flight to Miami:** Sunday April 20, evening (MEX → MIA)
- **Flight to Dominica:** Monday April 21, AA4304, 10:16 AM → 1:49 PM, MIA → DOM, 3h 33m nonstop, ~$384/person
- **Return leg 1:** Friday April 24, LF 3203 (Contour Airlines public charter), 9:00 AM → 10:25 AM, DOM → SJU, 1h 25m, Embraer ERJ145
- **Return leg 2:** Friday April 24, UA 1173, 1:25 PM → 5:39 PM, SJU → EWR, 4h 14m
- **Planning from:** Mexico City

## Date Rules — DO NOT GET THESE WRONG
- MEX → MIA: **Sunday April 20** (night before)
- MIA → DOM: **Monday April 21** (arrival day, Day 1)
- Day 2: **Tuesday April 22**
- Day 3 (last full day): **Wednesday April 23**
- Day 4 / Departure: **Friday April 24** (early AM flight at 9:00 AM, need to leave hotel ~6:30 AM)
- The trip is **Apr 21–24**, 3 nights on island

## Current State of the Page
- `index.html` is a single-file trip planning page (HTML/CSS/JS, no build step)
- Sections: Hero → Flights → Activities Directory → Day-by-Day Itinerary → Map → Hotels → Budget → Notes on Dominica → Practical Info
- **No "Overview" section** — it was removed. Do not add it back.
- **No "Other Options" / alternatives section** — it was removed. Do not add it back.
- Activities Directory uses accordion dropdowns stacked **vertically in a single column** (7 categories: Hikes, Waterfalls, Snorkel/Scuba, Whale Watching, Beaches, Restaurants, Shopping/Culture)
- Map uses Esri satellite basemap with labels overlay (NOT OpenStreetMap)
- Budget tab tracks costs for 2 people, $384/pp for MIA→DOM flight ($768 total locked in)
- 4 days in itinerary (not 5): Day 1 arrival, Day 2 whales, Day 3 last full day, Day 4 early departure

## Approach
- User is in **active trip planning mode** — no speculative content, no "maybe consider this other destination" stuff
- Itinerary days have selectable options (option cards) — user will lock each day in over time
- All prices should be shown per person where applicable
- When adding activities, include booking links where available
- Keep the page practical and decision-oriented

## Style
- No emojis in text content (they were removed from headings/labels)
- Use HTML entities for special characters (e.g. `&mdash;` `&ndash;` `&rarr;`)
- Clean, professional tone — not a blog post
