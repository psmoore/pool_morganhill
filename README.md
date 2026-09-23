# Morgan Hill Aquatics — Pool Relay embed preview

A seven-page replica of the City of Morgan Hill
[aquatics pages](https://www.morganhill.ca.gov/209/Aquatics): the hub, the outdoor Aquatics Center, the
indoor Centennial Recreation Center (CRC) pool, and the Aqua Fitness, Swim Lessons, Lap Swim and Splash
Swim Team pages, each with a live [Pool Relay](https://www.poolrelay.com) calendar scoped to exactly
what that page is about.

Not an official City of Morgan Hill page. It says so in a ribbon across the top.

Built with `python3 build.py` (the chrome lives there; edit it, not the HTML) and served by GitHub Pages.

## The seven pages

| Page | Calendar | Scoped to |
|---|---|---|
| `index.html` — Aquatics hub | [`qmQGUpyn…`](https://www.poolrelay.com/v/qmQGUpyn9LZQmdKwjAeWF6) | both centers, every program except CRC open play, **Facilities** menu on All |
| `aquatics-center.html` | [`tQF06YWo…`](https://www.poolrelay.com/v/tQF06YWoAo4HDLxztRYow1) | the Aquatics Center, **Pools** menu |
| `aqua-fitness.html` | [`vEXgsnQB…`](https://www.poolrelay.com/v/vEXgsnQBRAFvNxupDVVR7T) | Shallow Tone, Deep H2O Dynamics, CRC Aqua Fitness |
| `crc.html` | [`CfjPFKFb…`](https://www.poolrelay.com/v/CfjPFKFbY9mY804eLoftpT) | the CRC indoor pool, including the play area |
| `swim-lessons.html` | [`ZA813GWy…`](https://www.poolrelay.com/v/ZA813GWyAMBTXFnXtI76zF) | Swim Lessons |
| `lap-swim.html` | [`c5dJvh9W…`](https://www.poolrelay.com/v/c5dJvh9WnUdSPDCdjh15a2) | Lap Swim at both centers, **Pools** menu on All |
| `splash.html` | [`4nOtuEgJ…`](https://www.poolrelay.com/v/4nOtuEgJabUEssEWCxcGbe) | the Competition Pool, where Splash trains |

## Sources

Both schedules are effective September 8, 2026, with no end date:
[Aquatics Center](https://www.morganhill.ca.gov/DocumentCenter/View/786) (a page per pool) and
[CRC Indoor Pool](https://www.morganhill.ca.gov/DocumentCenter/View/40340). Page copy is from the city's
aquatics, Aquatics Center, CRC Aquatics, Lap Swim, Swim Lessons and Splash Swim Team pages, read the same day.

## What is ours

- **Lane ranges.** "9–17 lanes" is entered as lanes 1–9 and Saturday's "10–17" as lanes 1–10.
- **Instructional Pool** bookings hold the whole pool (6 lanes), as the schedule gives them.
- **CRC lanes.** Lessons take lanes 2–3 while one lap lane (lane 1) stays open, per the schedule's
  "(1 Lap Lane Open)".
- **Aqua Zumba** is noted on the Saturday 8am Shallow Tone class, not entered separately.
- **October 24:** Competition Pool lap swim narrowed to 5–7am for the swim meet; nothing else changed.

## Open questions (also on the hub and Aquatics Center pages)

| | |
|---|---|
| **Conflict** | Deep H2O Dynamics (weekdays 11:00–11:55) sits inside the 5am–1:30pm lap swim block; which lanes does it take? Left flagged on the calendar. |
| **Conflict** | The aquatics page says the Competition Pool has up to 18 lanes; the schedule tops out at 17. Built with 17. |
| **Gap** | October 24 make-up Sunday has no date; does water polo or the Instructional Pool run during the meet? |
| **Gap** | Splash Youth Swim, Monday–Thursday "between 4:15 and 7:55pm" in the Competition Pool, is on neither schedule. Lap swim has 5 of 17 lanes then, so presumably 12 are Splash's. |
