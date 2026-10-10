# intent.md — your process, before any AI


## My problem

I receive syllabi from my two professors. How can I create a calendar to see when my assignments are due without me being late on submissions?

## What I receive

I receive the syllabus with the details on what is covered in each class, and also the type of assignments with the due dates, the grading criteria, textbook and material requirements.

## My steps now

1. collect syllabi
2. extract every dated item
	1. convert words like class 1 and week 1 to corresponding dates
3. add events
	1. add fixed events
	2. add dates for assignments, projects, and tests. 
4. check for overlaps on due dates from my two courses
5. review and update the calendar every week


## Where it breaks down

It can break down in step 2, because sometimes I can miss adding the correct due date, and we can go wrong in converting relative date.

## What a good output looks like

All the due dates are listed correctly in the calendar, and it needs to send a reminder of when an assignment is due, and needs to flag when more than one assignment is due on the same date.

## What AI must not decide

unclear or missing date - If the date is unclear or not there in the syllabus, AI should not suggest a likely date, but it should mark it as "not known". I will ask the professor for the correct date.

## Material I will run the workflow on

- https://scad.simplesyllabus.com/en-US/doc/i8tjqv6j0/Fall-2026-AI-SAV-101-12976-Survey-of-AI-Applications?mode=view

- https://scad.simplesyllabus.com/en-US/doc/xq1emdebz/Fall-2026-ANIM-SAV-223-11769-Historical-Adventures-in-Cinematic-Animation?mode=view
