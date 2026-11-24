# Atweaman SHS — Timetable Generator

Sample data · generate a draft, fine-tune, print by teacher/class/subject, or download

Zoom 100% School name on prints Print

Class Timetable

Exam Timetable

Bell Schedule

Exam Bell

Workload Summary

Master Overview

☰ Manage class data

New class Short name

New teacher Short name [ ] Also add as invigilator

New subject Short name

Class Subject Short name Teacher Periods/week Room needed Periods per lesson Max per day Taken by Parallel group (optional)

Give two or more subjects for this same class the same parallel-group name to run them side by side in one slot — e.g. elective options, or a subject split into Level 1 / Level 2 streams.

Joint with (optional — held together with "Class" above, e.g. a combined Assembly or shared elective)\
none

CSV with header `Class,Subject,Teacher,Periods/week,Periods/lesson,Room` (Room: blank, lab, or studio) — or a previously downloaded curriculum JSON file.

Edit a previously added subject's details, choose exactly which day and starting period each of its occurrences uses, or delete it.

Lesson

Class Teacher Periods/week Periods/lesson Max per day Taken by Parallel group Room needed Short name

Exact day/period for each occurrence (leave "Auto" to let the generator decide):

Name a set of classes once (e.g. "All Form 2", "Science stream") to quick-pick them together when joining classes or copying a subject.

Group name none

Who within a class takes a subject — the entire class, or just part of it (a stream, a set, boys/girls). Pick one when adding or editing a subject. Add your own labels here, or use the built-in ones.

New group label

Used by **Print → Department**. A subject belongs to the first department whose keywords appear in its name — unless you pick it yourself with **Subjects…**, which always wins. Keywords can be edited.

New department

Stop the generator from placing lessons in a period — for a whole-school event (Assembly, Sports Day), one class only, or one subject only.

Blocks Which

Tick exactly the day × period cells to block — periods run across, weekdays run down.

Label Students do (optional) Teachers do (optional)

[ ] Hide blocked-period labels on prints (still blocks placement — just shows an empty cell)

Drag a lesson onto another slot to swap; click ✎ to edit or delete. Cell color = class, dot = subject.

☰ Manage exam data

Name Type Capacity

New invigilator

For each exam subject, enter the **number of candidates in each form** (leave a box empty to use the class lists) and choose the **supervisor**. The generator uses the candidate numbers to fill rooms and halls and to keep forms, rooms and subjects from clashing.

[x] Keep a subject's papers for different forms in different sessions

Candidates per invigilator

With a number in the first box, every room or hall gets one invigilator for each that many candidates (a 180-candidate hall at 40 per invigilator gets 5). Leave it empty for one invigilator per room. Supervisors are matched to a subject they teach, so they can correct its question paper.

A supervisor oversees a whole exam session (separate from room invigilators). One is auto-assigned per session when you generate; mark their attendance directly on the exam timetable.

New supervisor

Start date Exam days [x] Skip weekends

Drag an exam onto another session to move it; click ✎ to edit invigilators or remove it.

Separate from the class Bell Schedule. Sessions are numbered in order and every exam day repeats this pattern; breaks show between sessions on the exam timetable. Use ▲▼ to reorder, then Save.

### Day-specific additions

Add a session (or break) that happens on **one exam day only**. Day # is the exam day number (1 = first exam day). It is slotted into that day's pattern by start time; leave the start blank to put it at the end of the day.

This bell schedule applies Mon–Fri and drives every period column above. Edit times, add or remove periods, then save and re-generate the class timetable.

A whole-school picture of everything set up so far — every class, subject, teacher, room, weekday, period and break. Generate the class (and exam) timetable first to fill the grids.

Grid rows by

Computed straight from the curriculum — no need to generate a timetable first. Refreshes automatically when you add or delete a subject.