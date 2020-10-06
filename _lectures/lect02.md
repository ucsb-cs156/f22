---
num: "Lecture 2"
lecture_date: 2020-10-06
desc: "TBD"
ready: false
---

<div style="display:none;">https://ucsb-cs156.github.io/f20/lectures/lect01
</div>

# Recap of Last Tuesday

Last Tuesday, we gathered in teams, and used the Slack channel to get to know our teammates.

* [List of Teams Assignments](https://docs.google.com/spreadsheets/d/e/2PACX-1vQOCADvCf9G46uSJ2m6tpFiGqMDuMOlfG_sSfcHZ8YSmOuonXQTga0dF5ASO_5RiM-UH5Zpc9sMcNgm/pubhtml)

We also discussed some of the things that help to make good teams.   

On Gauchospace, you should find a participation grade for last Tuesday:
* Ind-10/01 (50 pts) is for your individual participation; you earned this if you make a post with your five items (even if it was after class was over).
* Team-10/01 (50 pts) is for the team portion of your grade; you earned this if you participated in the discussion last Tuesday.

# How will grading work in this class?

Your grade will be made up of activities from the following categories:

* Participation Grades (10%) - Each participation grade will be out of 100 points.  The grade for 10/01 is an example of this category.
  
  Particpation grades may vary: some are individual, some are team, and some (like 10/01) may be a combination of the two that adds up to 100.
  
  The lowest three participation grades will be dropped; accordingly, if you need to miss a lecture every now and then because of illness,
  internet problems, etc., it shouldn't affect your grade unless it becomes a persistent problem (in which case you should speak to the instructor as soon as possible about your situation.)
  
* Homeworks / Quizzes (20 %) - These will be administered through Gradescope.  
  Some questions will be graded by hand (e.g. short answer/essay type questions), while others might be autograded
  (e.g. multiple choice, fill in the blank, true/false questions.)  These will typically be based on assigned readings.
  We will drop only the lowest two grades from this category.
  
* Auto-Graded Programming assignments (30 %) - jpa00 is an example of these programming assignments.  None of these will be dropped; you are
  responsible for all of them.   This may include individual assignments (such as jpa00), pair assignments, and/or team assignments.

* Project Grade (40%) - Your project grade will be based on your contributions during the Project phase of the course.   We'll discuss that 
  further in a few weeks, but there are details on the syllabus if you want to check them out.

  In addition, we'll be using peer evaluations through a tool called CATME to assess your individual contributions to the project's success.
  The peer evaluation may apply a multiplier to your project grade, increasing it or decreasing it, per your team's assessment 
  of your contributions.   It is important to be sure that you are meeting your committments to your team for a variety of reasons; your
  grade is among those.

# Today's Team Activity

We'll be discussing this paper: <https://pconrad.github.io/files/paper028.pdf>

Our focus will be Section 4, which is divided into 6 sections:

| Section | Title | Academia | Industry | 
|---------|-------|----------|----------|
| 4.1 | What: Differences in Scope | well-defined, fixed scope | vague, open-ended, evolving scope |
| 4.2 | When: Short vs. Long Time Spans | short time spans (days, weeks)  | long time spans (months, years) |
| 4.3 | Who: Individual vs. Large Team | individuals, pairs, small groups  | larger teams |
| 4.4 | Why: Learning vs. User Needs | to learn something  | to address a user need |
| 4.5 | How: Ad-Hoc vs. Professional | ad-hoc tools and practices |  professional tools and formal practices |
| 4.6 | How Big: Small vs. Large Codebases | small programs | large complex systems |

You'll first assign one person from your team to each section; most teams have six people, so that's team member per section.

You might use the team slack channel, and use first-come, first-served, or some other way to divide up the sections.

If you have fewer than six team members, you can decide to leave one section uncovered.  (If one or more team members is absent,
put a slack message in your team channel mentioning them by `@`-ing them, and letting them know which section(s) are left
to be claimed.)

Then, you'll elect one member of the team as the team scribe (a different one from last time) that can share their screen.

That member of the team should go to the repo for your team on GitHub.  Here are links to these repos:

| 5pm | 6pm | 7pm |
|-----|-----|-----|
| [team-5pm-a-NOTES](https://github.com/ucsb-cs156-f20/team-5pm-a-NOTES) | [team-6pm-a-NOTES](https://github.com/ucsb-cs156-f20/team-6pm-a-NOTES) | [team-7pm-a-NOTES](https://github.com/ucsb-cs156-f20/team-7pm-a-NOTES)  |
| [team-5pm-b-NOTES](https://github.com/ucsb-cs156-f20/team-5pm-b-NOTES) | [team-6pm-b-NOTES](https://github.com/ucsb-cs156-f20/team-6pm-b-NOTES) | [team-7pm-b-NOTES](https://github.com/ucsb-cs156-f20/team-7pm-b-NOTES)  |
| [team-5pm-c-NOTES](https://github.com/ucsb-cs156-f20/team-5pm-c-NOTES) | [team-6pm-c-NOTES](https://github.com/ucsb-cs156-f20/team-6pm-c-NOTES) | [team-7pm-c-NOTES](https://github.com/ucsb-cs156-f20/team-7pm-c-NOTES)  |
| [team-5pm-d-NOTES](https://github.com/ucsb-cs156-f20/team-5pm-d-NOTES) | [team-6pm-d-NOTES](https://github.com/ucsb-cs156-f20/team-6pm-d-NOTES) | [team-7pm-d-NOTES](https://github.com/ucsb-cs156-f20/team-7pm-d-NOTES)  |


That should currently be an empty, private repo, accessible only to the course staff and the members of your team.   The scribe, when they bring up the repo,
will see something like the image shown below.  Click on the README link to create a README.md file:

![click to create README](click-to-create-README-50.png)

Then, your screen will look something like the image below:  
* You will see a text area where you can enter text for the README.md file for this repo.
* There are tabs to toggle between Edit and Preview; the format is Markdown, which is explained on [This Markdown Cheat Sheet](https://guides.github.com/pdfs/markdown-cheatsheet-online.pdf)
* You may have to scroll down to find the "Commit New File" button, which is how you save your changes.


![new README](new-README-50.png)

What content should you type?  Type a list of who is assigned to each section, something like this (you can copy/paste this, then edit it for your group)

```
# Notes from 10/02

Paper Section Assignments:

* 4.1: Alice Z.
* 4.2: Bob Y.
* 4.3: Chris X.
* 4.4: (unassigned)
* 4.5: Danny W.
* 4.6: Emily V.
```

Then, save the file.   This first part is worth 20% towards your group participation grade; each person assigned to a section earns this if/when this 
gets committed to GitHub.

# Each person now creates a file for their section

Next, each member of the team (individually) should create a file pertaining to their own section.  You can do this by following the instructions/images below.

Note: Please follow the naming conventions shown below STRICTLY, including upper vs. lower-case letters.  


First, find the "Create New File" button:

![Create-new-file-50.png](Create-new-file-50.png)

Then, start typing the folder name `10.06`, as shown.  As soon as you type the forward slash `/`, you should see that the filename turns into a folder name.  If you have made a typo, you can hit the delete/backspace key, and it should go back so you can edit the folder name.

![start-typing-folder-50.png](start-typing-folder-50.png)

![after-typing-folder-50.png](after-typing-folder-50.png)

Finally, name your file as shown in the example, and fill in content as shown in the example.  For now, we *only* need the heading; the content can come later.

![fill-in-section-heading-50.png](fill-in-section-heading-50.png)





