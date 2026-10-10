# Start Here: Syllabus to Calendar

## Goal

Turn the syllabi for my two courses, AI101 and ANIM223, into one accurate calendar of every class meeting, assignment, project, and test, so I never miss a due date or get surprised by deadlines that pile up in the same week.

## How to use this folder

1. Read `process-map.canvas` to see the steps in order.
2. Follow the step files in order: `01-collect-syllabi.md` through `05-review-weekly.md`.
3. Do one step at a time. After each step, stop and report what you did before moving on.

Folder layout:

- `input/syllabi/AI101.pdf` and `input/syllabi/ANIM223.pdf`: the two syllabi. Each one lists its own class meeting dates.
- `outputs/`: everything the model creates goes here.

## Rules

- The syllabus is the only source for dates. Do not use an academic calendar, a website, or general knowledge about semesters.
- Convert "Class N" and "Week N" using the class meeting dates listed in that same course's syllabus. Never use one course's schedule to convert the other course's items.
- Never guess a date. If an item cannot be matched to a date in its syllabus, list it with `NEEDS DATE` and move on.
- Copy item names exactly as they appear in the syllabus. Do not shorten, merge, or rename them.
- Label every item with its course code, `AI101` or `ANIM223`, so items from the two courses are never mixed up.
- Only write to `outputs/`. Never edit or delete anything in `input/`. When two sources disagree (for example, the syllabus and an instructor announcement), list both and do not pick one.

## What stays my decision

- Which date is correct when sources disagree or a date is unclear.
- How to handle an overlap: what to start early, what to move in my study plan. The model flags overlaps; it does not resolve them.
- Whether an item is removed or changed after the calendar is built.
- When the calendar is final. Nothing is final until I complete the human check in `05-review-weekly.md`.
