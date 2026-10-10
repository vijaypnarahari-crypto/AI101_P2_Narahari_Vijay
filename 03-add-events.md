# Step 3: Add events to the calendar

**What starts this step:** Step 2 is approved, or step 5 sends back corrections.

**What goes in:** `outputs/dated-items.md`, plus any corrections I list in `outputs/weekly-review.md`.

**What this step does:** The model builds the calendar from the dated list, with fixed events first and then due dates.

**Directions for the model:**

1. Add fixed events (step 3a): every row in `outputs/dated-items.md` with type `class` or `no class`, for both AI101 and ANIM223. Title them `[AI101] Class` or `[ANIM223] No class: <reason from syllabus>`, add weekly class and professor's office hours if mentioned.
2. Add due dates (step 3b): every assignment, project, and test in `outputs/dated-items.md`. Format each title as `[Course] Type: exact item name`, for example `[AI101] Project: Project 2` or `[ANIM223] Test: Midterm`.
3. Do not add `NEEDS DATE` items to the calendar. List them under a heading `Not yet scheduled` at the end of the file.
4. If this step is running because of corrections from step 5, apply only the changes I listed. Do not change anything else.
5. Save the calendar in `outputs/calendar.md` as a table with columns `Date`, `Day`, `Course`, `Event`, grouped by week with a heading for each week (for example, `Week of Oct 5–Oct 11`).
6. Stop and report: how many events were added or changed, and how many are in `Not yet scheduled`.

**Good looks like:** Every row in `outputs/dated-items.md` that has a date appears once in `outputs/calendar.md`, with the same date and wording. No item appears twice.

**Human check:** I compare the number of dated items in `outputs/dated-items.md` with the number of events in `outputs/calendar.md`. If the counts don't match, the run stops until the model finds the missing or duplicate items.
