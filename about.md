---
layout: page
title: Syllabus and Course Policies
description: >-
    Course policies and information.
---

# About
{:.no_toc}

## Table of contents
{: .no_toc .text-delta }

1. TOC
{:toc}

---

## Lecture
Mondays, Wednesdays 2:00-3:15pm

## Textbook(s)

There are two excellent NLP textbooks that are freely available online. Readings will be assigned from both.  There is value in seeing multiple perspectives on the same material. If a concept you encounter seems confusing at first, try reading about it in the other book to get a different perspective.

- [Dan Jurafsky and James H. Martin. Speech and Language Processing (3rd Edition)](https://web.stanford.edu/~jurafsky/slp3/)
- [Jacob Eisenstein Natural Language Processing](https://github.com/jacobeisenstein/gt-nlp-class/blob/master/notes/eisenstein-nlp-notes.pdf)
- There will be other assigned readings as well.

## Computing Resources / Colab Pro

The programming assignments will ask you to implement state-of-the-art natural language processing algorithms using neural networks.  For this purpose we will use [Pytorch](https://pytorch.org/), and you will require access to GPUs.  The class will use [Google Colab](https://research.google.com/colaboratory/faq.html), which provides easy access to GPUs.
We **highly** recommend signing up for [Colab Pro](https://colab.research.google.com/signup) (once you start working on the part of the homework that uses Pytorch).  This costs $10 / month, which is roughly equivalent to the cost of a textbook over the course of the semester.  This will provide a better experience working on the homework assignments by giving you access to better GPUs, etc.  We have investigated other options to provide students access to GPUs for the homework assignments (Google cloud credits and PACE/ICE), and have found Colab Pro is the best solution.  Of course you are welcome to use other GPU resources to complete the assignments if you choose, but we cannot provide support for this.  You will need to submit your code and program output in Jupyter Notebook format.

## Attendance

We are planning to record and stream lectures over BlueJeans, so it should be possible to attend the course remotely if you like.  Please wear a mask if you decide to attend class in person, out of respect for others.  This will help make the classroom a safe environment for everyone (especially those who may have underlying health conditions or be living with those who do).

## Resources

- [Piazza](https://piazza.com/class/kxuyn4sdh0p6ve) (announcements, questions, discussion)
- [Gradescope](https://www.gradescope.com/courses/344493) (homework assignments, submission and grading)
- [Tentative Course Schedule](https://docs.google.com/spreadsheets/d/1GZHMzZ_p4APtYRTiReEJ_PU4wkdQSHgUGTd3xptCO8Q/edit?usp=sharing)

## Prerequisites

This is an advanced undergraduate course on Natural Language Processing.  Modern NLP is based heavily on Machine Learning and Deep Learning.  This course involves a lot of math and hands-on programming exercises to implement the algorithms we will discuss in the lecture.  To succeed, you need to have a very strong programming background, in addition to a firm grasp of probability, linear algebra, and multivariable calculus.  You should be comfortable working on medium-to-large software projects in Python and be comfortable learning and using new Python libraries, or you should have developed the ability to independently learn a new programming language and environment very quickly.

There will be a math background test (due in the 1st week) and a warmup programming assignment due shortly afterward.
If you find these problems difficult, you should expect a lot of extra work and challenges to catch up – we strongly suggest you wait and take this class in a later semester.  Please reach out to the
course staff to discuss whether you have the right background to succeed in this course if there are any symbols or concepts on these assignments which you are unfamiliar with.

(**For students on the wait list:** we don't have any additional information on whether you will be able to enroll in the course, but if you plan to try and enroll, please complete and submit Problem Set 1, which is due during the first week.  Please post a private Piazza message to get the access code to access Gradescope.)

## Assignments / Grading

Graded work will include written and programming assignments. Assignments should be submitted to Gradescope by 11:59pm on the day they are due.
Please email your homework to the instructor in case of any technical issues with submission.

Each student will have six flexible days to turn in late homework throughout the semester. The late days will be applied to homework assignments in the order of submission. As an example, you could turn in the first homework 2 days late and the second homework 1 day late without any penalty. After that you will loose 20% for each day an assignment is handed in late.
Late days and penalties handled in in units of days - there are no ``half'' late days.  Late penalties are also applied to the entire assignment, so it is not possible to turn part of an assignment on time and the other part late.
These six late days are meant for personal emergencies; if you use late days for non-emergency situations but later encounter emergencies in the semester, you will not be given extra late days. No late days will be allowed for the final course project, due to the tight deadline for posting final grades as required by the university.

All homework will be rescaled proportionally into a final numerical grade, which will then be mapped to letter grade according to a cutoff based on the overall class grade distribution. The standard cutoff is 90/80/70% for A/B/C, but we may curve up (never down), i.e., use lower cutoffs than these. The cutoffs will only be determined after we grade the final project at the end of the semester.

### Programming Assignments (Projects) - 40%

We plan to assign four programming assignments that provide hands-on experience implementing algorithms discussed during lecture.  The assignments are in Python, and make use of [Numpy](https://numpy.org/) and [Pytorch](https://pytorch.org/).  These will require non-trivial computation to complete; we recommend using Google's [Colab](http://colab.research.google.com/) platform which provides free access to GPUs.  Completing these projects will require waiting for your models to train (this can range from about 30 minutes to hours depending on the efficiency of your implementation), so we strongly recommend starting work on these programming assignments well in advance of the deadline.  If you start working on an assignment the day before it is due, it is unlikely you will be able to complete it on time.

### Written Assignments (Problem Sets) - 20%

Written assignments will mostly be mathematical.  You can scan and upload your solutions to Gradescope.  Please write answers clearly, as we won't be able to award credit for answers that we are not legible.

### Midterm Exam - 15%

The midterm will be similar in format to the written assignments (problem sets).

### Participation - 5%

You will receive credit for asking and answering thoughtful questions related to the course content on Piazza, engaging in discussion in class and generally for participating in the class.  There are many ways to show participation.  Asking a question that is marked as a ``good question'' by an instructor on Piazza, or having an answer that is marked as an ``endorsed answer'' is one example.  Please be polite and respectful towards TAs and other students in the class.

### Final Project - 20%

The final project is an open-ended assignment, with the goal of gaining experience applying the techniques presented in class to real-world datasets. Students should work in groups of 2-4. It is a good idea to discuss your planned project with the instructor to get feedback.  The final project report should be 4 pages. The report should describe the problem you are solving, what data is being used, the proposed technique you are applying in addition to what baseline is used to compare against.

The grading rubric for the final project is as follows:

- Clarity (1-5) For the reasonably well-prepared reader, is it clear what was done and why? Is the report well-written and well structured?
- Originality / Innovativeness (1-5) How original is the approach? Does this project break new ground in topic, methodology, or content? How exciting and innovative is the work that it describes?
- Soundness / Correctness (1-5) First, is the technical approach sound and well-chosen? Second, can one trust the claims of the report – are they supported by proper experiments, proofs, or other argumentation?
- Meaningful Comparison (1-5) Does the author make clear where the problems and methods sit with respect to existing literature? Are any experimental results meaningfully compared with the best prior approaches?
- Substance (1-5) Does this project have enough substance, or would it benefit from more ideas or results?  Note that this question mainly concerns the amount of work; its quality is evaluated in other categories.
- Overall (1-5)

## Academic Integrity

Any assignment or exam that you hand in must be your own work (with the exception of group projects). However, talking with others to better understand the material is strongly encouraged. Copying a solution or letting someone copy your solution is considered cheating. Everything you hand in must be your own words. Code you hand in must be written by you, with the exception of any code provided as part of the assignment. Any collaboration during an exam is considered cheating. Any student who is caught cheating will be reported to the Office of Student Integrity. Please don't take a chance - if you are having trouble understanding the material, let us know and we will be happy to help.
