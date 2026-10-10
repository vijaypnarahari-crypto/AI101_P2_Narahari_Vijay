# Step 2 report: Extract every dated item

Output: `outputs/dated-items.md`. Step 3 has not been started.

| | Items | `NEEDS DATE` | Other flags |
|---|---|---|---|
| AI101 | 32 | 6 | none |
| ANIM223 | 45 | 3 | none |

Neither syllabus marks any `no class` days.

## AI101 date source: resolved by you

- **Your decision:** AI101 dates come from the Class Meeting Dates list (Class 1 = Tue 9/15/26). The Schedule of Classes table dates are ignored.
- **Applied:** all 21 `DATE CONFLICT` rows now show the list date.
- **Grading Opportunities dates:** moved to the Thursday class dates, as you decided.
  - Project 1: 9/23 to Thu 9/24 (Class 4).
  - Project 2: 10/7 to Thu 10/8 (Class 8).
  - Project 3: 10/21 to Thu 10/22 (Class 12).
  - Capstone and Professional Practice: 11/18 to Thu 11/19 (Class 20).
  - The original written date stays in "As written" and Notes.

## Other things to check

- **ANIM223 Assignment 4:** Class 14 says it's due at the start of Class 19, and the Class 19 row says by the end of Class 19. Both are listed.
- **ANIM223 Assignment 3 readings:** It covers chapters 12–24, but readings are only assigned through chapter 22.
- **ANIM223 dates:** The schedule table's Date column is blank in the PDF, so I used its Class Meeting Dates list.
- **PDF versions:** The ANIM223 PDF was captured 9/8/26, and the AI101 PDF 10/4/26. Confirm ANIM223 is still the latest version.

## Judgment calls

- **Extra rows:** I used type `class` for study trips, extra help sessions and midterm conferences, since no type fits. Each row's Notes says so.
- **Left out of the table:** Course evaluations (Weeks 8–10), the "Week 2" GitHub setup, and the optional ANIM223 events. They are listed at the bottom of `dated-items.md`.
- **Where the file lives:** The step files point to `outputs/dated-items.md`, so I saved it there. `outputs/README.md` suggests a `first-run` prefix, and the empty `outputs/first-run/` folder is still there.

## Your human check

- Pick three items per course and compare them with the syllabi.
- Tell the model when to continue.
