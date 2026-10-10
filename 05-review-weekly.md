# Step 5: Review and update the calendar every week

**What starts this step:** Every Sunday evening, before the new week starts. Also any time the AI101 or ANIM223 instructor announces a change.

**What goes in:** `outputs/calendar.md`, `outputs/overlaps.md`, `input/syllabi/AI101.pdf`, `input/syllabi/ANIM223.pdf`, and any instructor announcements from the past week (course site, email).

**What this step does:** This is my human check. I confirm the coming two weeks are correct and decide what to do about any overlaps.

**Directions (done by me; the model only prepares):**

1. Model: list every event in the next 14 days from `outputs/calendar.md`, plus any overlaps in that window from `outputs/overlaps.md`. Then stop.
2. Me: check each listed date against that course's syllabus and the past week's announcements.
3. Me: write any corrections in `outputs/weekly-review.md` under today's date, as: `Course | Item | Old date | New date | Source` (for example, "AI101 announcement, Oct 3").
4. Me: for each overlap, decide my plan (for example, "start the ANIM223 project the week before") and write it under the same date.
5. If there are corrections, send them back to step 3. If there are none, write "No changes" under today's date.

**Good looks like:** `outputs/weekly-review.md` has an entry for every week of the semester so far, and each entry says either "No changes" or lists the corrections with their source.

**Human check:** Nothing in the next two weeks counts as confirmed until I have checked it against the syllabus and announcements. If a date can't be confirmed, I mark it unconfirmed and ask the instructor before relying on it.
