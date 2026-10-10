# Step 2: Extract every dated item

**What starts this step:** I say "Start step 2" after finishing step 1.

**What goes in:** `input/syllabi/AI101.pdf` and `input/syllabi/ANIM223.pdf`.

**What this step does:** The model finds every item in each syllabus that has a date or a class/week reference and turns it into one list with real calendar dates, using each syllabus's own schedule.

**Directions for the model:**

1. Read each syllabus from top to bottom, including tables, schedules, and footnotes. Pull out every class meeting, reading, assignment, project, quiz, and test.
2. For each item, record the date exactly as written in the syllabus (for example, "Class 7" or "Week 3").
3. Convert relative dates to calendar dates (step 2a), using only the class meeting dates listed in that course's own syllabus:
   - "Class N" = the date the syllabus lists for class meeting N.
   - "Week N" = the dates the syllabus lists for week N. If the item names a day (for example, "Week 3, Friday"), use that day within week N. If it names no day, use the first class meeting date of week N.
   - Days the syllabus marks as no class (holidays, breaks, cancelled sessions) stay on the list as type `no class`.
   - If an item cannot be matched to a date in its syllabus, write `NEEDS DATE` in the date column. Do not guess.
4. Save the result as a table in `outputs/dated-items.md` with these columns: `Course` (AI101 or ANIM223), `Item (exact syllabus wording)`, `Type` (class / no class / reading / assignment / project / test), `As written`, `Calendar date`, `Notes`.
5. Sort by calendar date. Put all `NEEDS DATE` rows at the bottom.
6. Stop and report: how many items for AI101, how many for ANIM223, and how many are `NEEDS DATE`.

**Good looks like:** I can pick any three items in the syllabi and find each one in `outputs/dated-items.md` with its exact wording, and its calendar date matches the date the syllabus schedule gives for that class or week.

**Human check:** For each course, I pick three converted items and look up their class or week number in that syllabus's schedule. If any date doesn't match, the run stops: I tell the model which item is wrong, and step 2 runs again before step 3.
