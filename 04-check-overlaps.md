# Step 4: Check for overlapping due dates

**What starts this step:** Step 3 finishes.

**What goes in:** `outputs/calendar.md`.

**What this step does:** The model finds places where AI101 and ANIM223 due dates land close together and flags them for me. It does not fix them.

**Directions for the model:**

1. Find every date where AI101 and ANIM223 both have an assignment, project, or test due.
2. Find every week (Monday through Sunday) with three or more due items across both courses, or with a test in both courses.
3. List each overlap in `outputs/overlaps.md` as a table with columns: `Dates`, `Items (course + exact name)`, `Why it is flagged` (same day / heavy week / two tests).
4. Do not suggest moving any due date. Do not rank which item matters more.
5. Stop and report how many overlaps were found.

**Good looks like:** I can look at any week in `outputs/calendar.md` with three or more due items, or with tests in both courses, and find it listed in `outputs/overlaps.md`.

**Human check:** I scan the three busiest weeks in the calendar myself. If any of them is missing from `outputs/overlaps.md`, the run stops and step 4 runs again.
