---
content_type: page
description: This projects section provides description and timetable along with student
  final reports for the final project.
learning_resource_types:
- Projects
ocw_type: CourseSection
title: Projects
uid: 093f7fe0-0555-3f32-9c47-34c6496785fe
---

The project is the major component of this course. A project description and [timetable](#timetable) are provided below along with [student final reports](#student_final_reports).

Projects
--------

The centerpiece of the course is a semester-long project, done in groups of 2-4 students. The project should make a research contribution in the area of tool support for programming tasks. As a research contribution, it should answer a question whose answer no one previously knew.

A non-exhaustive list of types of acceptable projects are:

*   Proposing and evaluating a fundamental new technique
*   Developing and assessing new algorithms to replace currently-used ones
*   Translating a methodology to a new problem domain
*   Applying known techniques to new problem domains, such as operating systems, networks, embedded systems, security, biology, aerospace, etc.
*   Evaluation of existing techniques or tools, via case studies or controlled experiments
*   Port an existing tool to a new domain (e.g., a new programming language or a new version of one)

A list of specific potential projects will be distributed at the second class meeting. (It is intentionally not being distributed until after you have completed Assignment 1.) You may select (or modify) a project from among the list of suggested ones, from your answers to Assignment 1, from other students' answers to Assignment 1, or from other sources. The lecturer will help you choose and refine a project.

For instance, you might start from a programming problem that has vexed you and devise a solution (or demonstrate that it is a broader problem than previously recognized). You might take a paper of particular interest to you and attack one of the problems listed in its future work section. You might take a promising paper that lacks experimental evaluation, or whose methodology is flawed, and perform a proper experimental evaluation.

You should also consider building on your strengths and finding ways to leverage other work that you are doing. For instance, if you do work in AI, you might consider how machine learning could be applied to problems of program comprehension or to filtering output from program analysis tools. You also might consider using a project that you are working on, or that you worked on in the past, as a test case for a tool. Synergies with your other work are welcomed!

Your final project report should be written in the style of a conference paper, and you will present it in a 6.883 conference at the end of the semester. (You are not required to submit your work to a conference or workshop, but you might choose to do so, and this is the standard of work expected.) You need not close the book on the area of research you choose, but you should do a good job of learning and clearly communicating new knowledge in that area. Do not feel overwhelmed by the final project or final report. The instructor will meet with you repeatedly for discussions, feedback, and assistance on all aspects of your project.

{{< anchor "timetable" >}}{{< /anchor >}}Timetable
--------------------------------------------------

*   By Week 4: Select a group, select a project, write a short (1-2 pages) project proposal that includes its thesis and technical approach, and meet with the instructor for feedback on and approval of your project proposal.
*   By Lec #7: Submit a version of your report that includes the introduction, description of the technical approach (e.g., algorithmic details), related work, and experimental methodology (i.e., evaluation plan). The evaluation plan should indicate what subject programs you will use and what metrics you will measure. It should explain why those are the right metrics, and what they reveal about your work. (For example, do they address the novel part of your technique, or are they end-to-end measures? Can they be directly compared to previous work, or not?) It should also indicate your criteria for success. (You should lay those out now, so that you have an objective measure when the research is complete.) Include the division of labor among members of your group. Do not stint on this component of the project: a prototype implementation and draft report is due in just three weeks.
*   By Lec #12: Submit a preliminary version of the report, including at least partial results. In particular, you should have a prototype implementation that can run end-to-end on a small example program. (For example, your compiler should be able to compile the factorial program.) Having a working implementation now will enable you to enhance it and to run experiments during the next several weeks; if you do not even yet have working code, you are unlikely to be able to complete a quality project in time.
*   Lec #15-17: Present your project in class. You should plan to talk for 20-25 minutes, followed by 5-10 minutes for questions though the questions may come during rather than after the talk. As with any talk, be sure to practice it before you present in class.
*   By Lec #17 (last day of MIT classes): Submit your final report.

{{< anchor "student_final_reports" >}}{{< /anchor >}}Student Final Reports
--------------------------------------------------------------------------

All work is courtesy of the students named and are used with permission.

{{< tableopen >}}
{{< theadopen >}}
{{< tropen >}}
{{< thopen >}}
project topics
{{< thclose >}}
{{< thopen >}}
group members
{{< thclose >}}

{{< trclose >}}

{{< theadclose >}}
{{< tropen >}}
{{< tdopen >}}
Javarifier: Inferring Reference Immutability for Java® ({{% resource_link e0cdb8c7-dda2-b85b-3ae3-77bf45cc1bbb "PDF" %}})
{{< tdclose >}}
{{< tdopen >}}
Matthew Tschantz, Chen Xiao, and Vineet Sinha
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
Automated Test-case Generation with SAT ({{% resource_link 520791ae-3d97-7103-9f39-53ac50e5ffd0 "PDF" %}})
{{< tdclose >}}
{{< tdopen >}}
Greg Dennis and Robert Seater
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
Annotation-less Unit Type Inference for C ({{% resource_link b068226d-bde9-32a8-42bb-87bccf8b7ee3 "PDF" %}})
{{< tdclose >}}
{{< tdopen >}}
Philip Guo and Stephen McCamant
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
Safe Test Case Reduction ({{% resource_link 90bc3e21-0a22-f16a-d95c-d83864952878 "PDF" %}})
{{< tdclose >}}
{{< tdopen >}}
Brad Howes and Anonymous
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
Automatic Generation of Unit Regression Tests ({{% resource_link 7803dd4d-e903-0c6e-9774-651041871734 "PDF" %}})
{{< tdclose >}}
{{< tdopen >}}
Shay Artzi, Adam Kiezun, Carlos Pacheco, and Jeff Perkins
{{< tdclose >}}

{{< trclose >}}

{{< tableclose >}}