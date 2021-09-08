---
jupytext:
  formats: ipynb,md:myst
  text_representation:
    extension: .md
    format_name: myst
    format_version: 0.13
    jupytext_version: 1.10.3
kernelspec:
  display_name: Python 3 (ipykernel)
  language: python
  name: python3
---

# Course Overview

Mathematical computer-based problem solving in Earth and planetary sciences. 

## Who

* Phil Austin, instructor (paustin@eoas.ubc.ca) 
* Catherine Johnson, instructor (cjohnson@eoas.ubc.ca)  

* Andrew Loeppky, TA (andrew.loeppky@gmail.com)
* Anya Jacksteit, TA (ajacksteit@eoas.ubc.ca) 
* Francis Rossmann, TA (frossmann@eoas.ubc.ca)
* Sean Wanket, TA (swanket97@gmail.com)
    
*NOTE: The times for TA office hours will be confirmed at the start of week 2.*

+++

## Schedule

* Lectures: Tues/Thur, 11:00 am - 12:50 pm.  ESB 1012  
* Labs:     Wed 12:00 -2:00 pm; 4:00 -6:00 pm.  EOS-Main 203/210

+++

## What do I need to do this course? 

* **Course website:**  __[EOSC211](https://phaustin.github.io/eosc211_students)__ course materials, labs etc.  The text is open source and relevant readings are incorporated into the course website.  New material is continually added through the term, so check regularly.
* **Software:**  We will write code in python using Jupyter notebooks.  You do not need to install python on your laptop for the course - the Jupyter notebooks will run in the cloud on a JupyterHub hosted in EOAS.  This is all introduced in the first lab.
* **Submitting work:** We will use Canvas for submission of labs and assignments. If you need to contact the instructors you can message us in Canvas.
* **Contacting your peers:** We encourage the use of piazza for discussion with your peers.  
* **Prereqs:** This course requires a knowledge of math at the level of integral and/or differential calculus. Linear algebra is helpful but not necessary.

+++

## Course Level Learning Goals
1.  Be able to write computer programs to model and analyze data in the solid earth, atmospheric, and oceanographic sciences. This requires:

2.  Breaking problems into logical steps using flowcharts and pseudocode to specify algorithms,

3.  Writing and debugging python code to correctly implement algorithms,

4.  Modifying existing python code,  using the elements of good programming style,  to make  it  more  efficient,  readable,  and  documented  for  future  use,

5.  Creating scientifically informative and visually appealing plots.

### HARD SKILLS:

- Differentiate between and know the basic operations related to
  string, int, float, boolean, none, list, set, tuple, dictionary.
- Manipulate numpy arrays
- Make pretty plots
- Define functions so you DRY (don't repeat yourself)
- debug code
- Google your way out of problems (yes, really!)
- Use a shell or terminal to do stuff (we will cover as an extra)
- Develop a workflow that works BEYOND eosc211 - e.g., I do all my h/w assignments now in jupyter...

### SOFT SKILLS:

- Be confident going from a earth/ocean/atmosphere problem -> numerical dataset -> code -> scientific conclusion
- Appreciate computational principles and apply some of them: abstraction, efficiency, modularization
- Understand the relationship between GUIs, high level languages, low level languages, assembly code
- Foster an appropriate desire for efficient/elegant/pythonic code and dislike/avoidance of cluges without going overboard
- Appreciate that there are many ways to solve a single problem and some are better than others
- Confidence in viewing/using a computer like a programmer - shells/terminals, code, vocabulary

### BIG PRINCIPLES
- Coding is hard. I feel like I have no idea what I'm doing and that everyone is smarter than me.  Don't worry, practice is key.
- Clear and precise thinking
- DRY and YANGNI
- Make it look good
- Keep your hard drive organized just like you would a lab bench

+++

## Class Assessment

Total marks for the course will be divided as follows (**subject to modifications as needed during term**)

    1. Labs (7 or 8) – 30%.  You can drop the lowest grade, so ~4-5% each. 
    2. Assignments – 25%.  Two (12.5% each)
    3. Mini-quizzes (~11) – 10%.  Based on pre-class reading.  You can drop the lowest grade, so ~1% each.  
    4. Midterm – 10% (8% from individual score, 2% from group score)
    5. Final – 25% (20% from individual score, 5% from group score)


This breakdown applies ONLY if you “pass” the “individual exam” portion of the course. In other words, you should on average score 50% on each of the quizzes, and the individual portion of the midterm and final. However, it’s your total exam score that matters, so for example, if you just fail the midterm you can still pass the course as long as you do ok on the quizzes and/or final.  The quizzes, and individual portions of the midterm and final exam add up to 38% of the course grade, so at least 19% of your course grade must come from these quizzes/exams. If it is less than this then your “exam” mark is your course mark. This is to ensure that you are assigned a fair mark based on your learning.

### Labs and Assignments

The Tuesday class time will be used to introduce/practice new concepts relevant to that week’s lab, based on pre-readings. The Thursday class time will be used as a lab wrap-up, and/or to practice the new material.

Labs are an integral part of this course and are necessary to learn the course material. They also build on each other, so please don’t skip lab sessions! Expect to spend more than the scheduled 2 hours to complete each lab. We  typically run labs with what is called a “pair-programming” approach, in which you work on labs in pairs.

Labs are submitted via Canvas. Labs must be submitted before 4:00 pm each Friday. Late submissions are not possible!They will be marked with one of the following 4 possibilities:
* “Satisfactory” (100%)
* “Some problems” (80%)
* “Major problems” (50%) - non-running code is in this category 
* “Not submitted” (0%) - not a bona fide attempt is also in this category

In addition to labs, there are also two larger assignments that should be done in pairs or in groups of three (if you prefer to work alone you may do so with the permission of the instructor). You may select your partner(s), they need not be the same as people with whom you have worked during labs. Assignments are due at 4pm on the due date (see schedule / class announcements) and one assignment per pair / group must be submitted on Canvas. Please follow the instructions carefully as to exactly what to submit and submit only these items. Assignments are graded as follows:
* A+ : all done correctly, no errors, nice pictures.
* A : one small error, pictures OK.
* B : One large or several small errors, figures reasonable.
* C : Several large errors, incomplete, figures misleading/incorrect. 
* D : Many errors, parts of assignment incomplete
* F : Not handed in, not seriously attempted, other failings.

### Exams:  Final/Midterm/Quizzes

There is one in-class midterm, scheduled for October 21, 2020. The final exam will be scheduled by the registrar in the regular exam period. The midterm and exam are both OPEN BOOK, but NO ELECTRONIC AIDS are allowed. 

The exams are 2-part exams.  Part 1 will be done individually. Then you will hand it in and do Part 2 with your group. Your exam mark will be a weighted sum of the marks from both parts. The individual part is weighted 80% of  and the group part 20%. 

Quizzes will typically be done in the Tues class and will be based on the pre-readings.  They will be short, open book to test your retention of the material. If you have completed the readings, these should be easy.

+++

## Academic Integrity: Policies for this Course

The purpose of the class is to learn a skill, and for many people it is beneficial to collaborate with others in order to do so. This is a realistic environment, and past experience shows that working with others (a) gets the work done faster, (b) tends to prevent getting “stuck”, (c) makes the experience more enjoyable, and (d) does not degrade learning outcomes, as long as all parties are contributing.

In class, we will randomly assign you to small groups (~4 people/group) each class. You will complete worksheets and class exercises in that group.

For labs and assignments, we encourage collaboration using a pair-programming method. However, you are expected to TRUTHFULLY REPORT: (a) the name of your partner(s), and (b) the level of collaboration. Using someone else’s code and claiming it as your own is plagiarism and will be treated as such.

The use of python, googling solutions, or receiving a solution from someone else are FORBIDDEN in the quizzes, mid-term and final exam.

+++

## Workload
You are expected to do the pre-readings to be ready for the problems assigned on the worksheets. It is not necessary to read the labs before lab times. You are expected to work outside of scheduled lab and class hours.
Although some people may complete the labs in the time provided (2 hours), typically 3 or 4 hours is required. If you need more than 6 please talk with an instructor or a teaching assistant.
Assignments typically take about 10–15 hours to complete over two weeks. You can work on assignments during the scheduled lab period if you wish. TAs are available at that time, as well as during office hours.
