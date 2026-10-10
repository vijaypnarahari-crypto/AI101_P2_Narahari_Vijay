# Step 1: Collect the syllabi

**What starts this step:** A new syllabus is posted for AI101 or ANIM223.

**What goes in:** The current syllabus for each course, downloaded from Blackboard, as a PDF.

**What this step does:** I gather the two syllabi and put them where the model can read them. The model does not start until this step is done.

**Directions (done by me, not the model):**

1. Save the AI101 syllabus as `input/syllabi/AI101.pdf`.
2. Save the ANIM223 syllabus as `input/syllabi/ANIM223.pdf`.
3. Open each one and confirm it has a course schedule that lists class meeting dates.
4. Tell the model: "Inputs are ready. Start step 2."

**Good looks like:** I can open `input/syllabi/` and see exactly two files, `AI101.pdf` and `ANIM223.pdf`, each the latest version posted, and each with a schedule of class meeting dates.

**Human check:** I confirm both syllabi are the most recent versions on the course sites and that both include class meeting dates. If either file is missing, outdated, or has no meeting dates, the run does not move to step 2.
