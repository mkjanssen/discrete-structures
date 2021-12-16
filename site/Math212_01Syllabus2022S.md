---
title: 'Math 212: Discrete Structures'
date: "Spring 2022"
lang: "en"
titlepage: false
titlepage-rule-color: "508ac3"
mainfont: 'Concourse 3 Regular.otf'
mainfontoptions:
- Path=/Users/mjanssen/Library/Fonts/
- BoldFont=Concourse 3 Caps Regular.otf
- ItalicFont=Concourse 3 Caps Regular.otf
sansfont: 'Concourse 3 Regular.otf'
sansfontoptions:
- Path=/Users/mjanssen/Library/Fonts/
- BoldFont=Concourse 3 Bold.otf
- ItalicFont=Concourse 3 Italic.otf
monofont: 'Triplicate B Regular.otf'
monofontoptions:
- Path=/Users/mjanssen/Library/Fonts/
- BoldFont=Triplicate B Bold.otf
- ItalicFont=Triplicate B Italic.otf
header-includes: |
    \setmathfont{Fira Math}
---

## Course Information

* **Institution**: Dordt University
* **Course**: Math 212-01 (3 cr.)
* **Term**: Spring 2022
* **Instructor**: Dr. Mike Janssen, Associate Professor of Mathematics
* **Classroom**: SB 1641
* **Class time**: 2:00-2:50pm MWF
* **Office**: SB 1612
* **Student Hours**: [Make an appointment](https://calendly.com/mkjanssen/student-hours) or drop by
* **Course Notes**: [\texttt{https://prof.mkjanssen.org/ds/notes/}](https://prof.mkjanssen.org/ds/notes/)
* **Course website**: [\texttt{https://prof.mkjanssen.org/ds/}](https://prof.mkjanssen.org/ds/)
* **Catalog Course Description**: A study of topics in discrete mathematics that are relevant to computer science and mathematics, including logic and proof, induction and recursion, elementary set theory, combinatorics, relations and functions, Boolean algebra, and introductory graph theory. Prerequisite: a grade of C- or better in Math 152.


### Required Resources


Regular access to:

 * A copy of _Mathematics for Human Flourishing_, by Francis E. Su
 * the [course notes](notes/)
 * [Canvas](https://dordt.instructure.com/courses/3391427) to access assignments and other course information
 * [Overleaf](https:/.www.overleaf.com/) for producing your homework


## Learning Objectives

In this course, students will:

In this course, students will:

* be _communicators_ through regular presentations to the Math 212 learning community and growing fluency in the writing of mathematical proofs. (CD)
* be _explorers_ by engaging with in-class activities and regular work outside the classroom. (CD)
* be _connectors_ by building relationships between real-world questions and discrete mathematical tools for answering them. (CS)
* be _learners_ by leveraging knowledge of logic, functions, and sets to explore foundational questions in discrete mathematics. (CS)
* be _ambassadors_ by reflecting on the ways the practice of mathematics can promote human flourishing. (RO, CD, CR)


## Course Liturgies


The best way to learn mathematics is to _do_ mathematics. There are two main types of regular work in this course: daily work, and written work. 

### Daily Work

The work of the course will be primarily driven by you, the student. In fact, each of you will have a job _every day_ to ensure that our course meetings are productive, that mathematical questions are asked and answered, and a record of each meeting kept.

#### Problems and Presentations

You will be assigned approximately five to six problems from the book to work on before coming to class. **You may not use any outside resources to help you solve these problems--no books, no websites, no friends who have taken this course before**. Using these resources will constitute plagiarism and will be reported to the Student Life Committee. You _may_ work with others currently enrolled in the course, but you will need to ensure that you can completely understand and explain the solutions and proofs you come up with.

One of the main goals of this course is to improve your mathematical communication. Thus, the majority of each class period will be devoted to you **presenting your work** on these problems to the class. You should expect that approximately 90% of the typical class period will consist of presentations and discussion. 

By 12:00pm before each class, you will claim on Canvas problems whose solutions you are willing to present. In general, you will be allowed to present at most one problem per class meeting. You will earn 0.1 daily work points per problem you sign up to present, even if you are not ultimately the person to present it.

You will be notified by 1:00pm on Canvas of any problems you are assigned to present. 


You will then write the problem and solution up on the board, highlight the main points of the proof/solution, and generally lead the class discussion. **That is, merely writing the solution on the board will not be sufficient to earn full credit**. The presenter will earn points as follows.


**$1$ point.** The solution/proof is correct and complete, and all questions are answered.

**$1/2$ point.** The solution/proof was prepared, but there are gaps and/or questions that are not satisfactorily answered.

**$-0.1$ points.** The solution/proof was either not prepared or is in completely the wrong direction.


#### Support

Of course, not everyone can be assigned the problems they sign up for. However, you may be assigned as _support_ for a given problem, typically a problem you've indicated a willingness to present. Prior to the presentation, it is your job to make sure that the presenter's written proof is clear. During and following the presentation, it is your job to try to answer any questions the presenter cannot. Satisfactorily engaging as a problem support person will earn you half the credit of the presenter.


#### Scribes


Each presented problem will also have a _scribe_ assigned on Canvas by 1:00pm. The first problems will be scribed in alphabetical order by last name, and subsequent scribes will be assigned in ascending order from least daily work points to most.
The scribe will have the responsibility of taking notes on the presented proof and asking questions when something is not clear. They then will write up a formal version of the proof and discussion and post it to our Overleaf document. The scribe will earn 1/4 point when a correct proof is submitted.


#### Discussion Leader

Finally, you may be assigned to be one of the day's _discussion leaders_. It will be your job to make sure that everyone has sufficient time to absorb the solution and ask any questions they might have. It is also your job to think of a question to ask _of each presenter_ if your classmates do not. You will earn 1 point each time you serve as an engaged, productive discussion leader.


#### Academic Integrity

This course structure effectively models the way professional mathematicians conduct and share their research. 
Thus, we will abide by the Policy Statement on Ethical Guidelines[^1] adopted by the American Mathematical Society, in particular Section I on mathematical research and its presentation. As this statement describes, "[t]he knowing presentation of another person's mathematical discovery as one's own constitutes plagiarism and is a serious violation of professional ethics. Plagiarism may occur for any type of work, whether written or oral and whether published or not." When you present your work in this class, both orally and in writing, you must cite **any conversations** you have had about this problem with **anyone in the class**. Looking to **any resource** outside of the people in our class for information about the problems at hand constitutes plagiarism and will be reported to the Student Life Committee.

[^1]: See [the AMS website](http://www.ams.org/about-us/governance/policy-statements/sec-ethics) for more: \texttt{http://www.ams.org/about-us/governance/policy-statements/sec-ethics}.



Daily work points will be monitored and factored into the [final grade](#grading).

### Written Work

Roughly every other week (other than the weeks we have exams), you will be assigned three problems to solve, write up, and submit online by 5:00pm on **Jan. 19, 26; Feb. 16; Mar. 2, 30; Apr. 13, 27**. These will be written in LaTeX, and will generally not be problems that have been presented in class (though they may have been assigned as daily work). 
Each problem will be graded on a four-level scale (each explained more fully on the proof rubric distributed [here](https://prof.mkjanssen.org/ProofRubric.pdf)) as: 

**E**xceeds expectations. Dr. Janssen would be happy to post this as the official class solution.

**M**eets expectations. The logic is generally correct and it is reasonably well written, but there is room for improvement.

**R**evision needed. Some major gaps in logic, misuse of notation, or unclear communication requires revision.

**N**ot assessable. This is difficult to read, abuses notation, or contains significant mathematical flaws.



<!-- ### Exams -->

Writing proofs is as much art as science, and initially it can seem daunting and confusing. If you submit by the deadline, you will receive a first round of feedback from an experienced teaching assistant by the following Monday. You'll then have until Friday of _that_ week to submit a revised version of the homework based on the TA feedback. Dr. Janssen will then give an initial assessment and feedback which may be revised once before becoming final.



In short, your submissions will go through the following workflow (with the number representing the number of days since the Wednesday submission):

* Day $0$: Initial submission due 5:00pm Wednesday
* Day $5$: TA feedback returned by class time on Monday
* Day $10$: Revised submission due at 5:00pm Friday
* Day $10+n$, $1\le n\le 7$: Feedback and initial assessment (EMRN) on each problem from Dr. Janssen
* Day $17+n$, $1 \le n \le 7$: Final version of problems submitted to Dr. Janssen, to be graded within a week.

Work submitted late or work initially assessed at an N requires a meeting with Dr. Janssen and short accompanying reflection on why the work was assessed at an N and how such assessments will be avoided in the future. If earning an N becomes a regular occurrence on written assignments due to perceived lack of effort, you may lose the grace afforded by the submission/feedback/resubmission process and only be allowed a single submission.

### Portfolio

At the end of the semester, you will compile a selection of your work (both written and daily), along with 3-5 new problems, into a portfolio, due at the final exam time. More details to come.

### Reading Reflections

As we mature in our mathematical studies, we'll consider the formative nature of mathematical practice. (Former Dordt First Mondays Speaker) Francis Su argues that mathematics can help inculcate certain virtues in its practitioners. We'll read Su's book in chunks, complete reflection essays, and discuss them in class. See the [schedule](#schedule) and the reflection assignments' Canvas pages for more details.


### Exams

There will be two exams, the first in class on **March 2**, and the second (oral) exam during the last week of class/finals week. The first will be cumulative up to the previous class, and worth 50 points, while the second will be cumulative over the whole semester, but with an emphasis on material covered since the first exam, and worth 75 points. The first will be a written in-class exam, while the second will be an oral exam. Your exam average will be a major factor in your final grade.

\begin{center}
\boxed{\textbf{I reserve the right to make changes to these policies at any time.}}
\end{center}

### Other Polices and Advice

* I am generally fairly accepting of late work, with a built-in 24-hour grace period for any non-classroom activities (e.g., non-TA written work submissions,  reflections). Additional time beyond the 24-hour grace period must be approved ahead of time.
* Student hours are your time to ask questions about all aspects of the class and college life. If you can’t [find an appointment](https://calendly.com/mkjanssen/student-hours), send me an email! I will do my very best to accommodate your schedule.
* **Email Policy**: I check my email twice per school day: once in the morning, where I'll deal with any emergencies, and once in the afternoon, when I'll respond to other emails (including any that have come in since the morning). If you require a more immediate response, you're welcome to come find me in my office.

\newpage


## <a id="grading"></a>Grading

In general, your final grade will be the **highest fully completed row** in the following table.


| Grade | Daily Work | Written Work (M or higher) | Written Work (E) | Exam Average | Portfolio |
|:-----:|:----------:|:--------------------------:|:----------------:|:------------:|:-------:|
|   A   |     43[^2]     |            18/19           |        13        |      87%     |    E    |
|   A-  |     42     |            17/19           |        11        |      84%     |    E    |
|   B+  |     40     |            16/19           |        9        |      80%     |    E    |
|   B   |     38     |            15/19           |         8        |      77%     |    M    |
|   B-  |     36     |            14/19           |         7        |      74%     |    M    |
|   C+  |     34     |            13/19           |         6        |      70%     |    M    |
|   C   |     32     |            12/19           |         4        |      67%     |    M    |
|   C-  |     29     |            11/19           |         2        |      64%     |    M    |
|   D   |     25     |            10/19           |         0        |      55%     |    -    |


[^2]: The benchmark for A-level daily work was computed as follows: 12 full-credit presentations, 6 full-credit supports, 4 classes as discussion leader, 12 problems scribed ($12\cdot 0.25 = 3$ points), 18 points of problem signups. We see $12 + 6 + 4 + 3 + 18 = 43$.


### Additional Information

#### Dordt University Student’s Right to Accommodations Policy

Dordt University is committed to providing reasonable accommodations for students with documented qualifying disabilities in accordance with federal laws and university policy.  Any student who needs access to accommodations based on the impact of a documented disability should contact the Coordinator of Services for Students with Disabilities (CSSD): Sharon Rosenboom, Academic Enrichment Center, Office: L168, (712) 722-6490, Email: Sharon.Rosenboom@dordt.edu.


#### Dordt University Academic Dishonesty Policy

Dordt University is committed to developing a community of Christian scholars where all members accept the responsibility of practicing personal and academic integrity in obedience to biblical teaching. For students, this means not lying, cheating, or stealing others’ work to gain academic advantage; it also means opposing academic dishonesty. Students found to be academically dishonest will receive academic sanctions from their professor (from a failing grade on the particular academic task to a failing grade in the course) and will be reported to the Student Life Committee for possible institutional sanctions (from a warning to dismissal from the university). Appeals in such matters will be handled by the student disciplinary process. For more information, see the [Student Handbook](http://www.dordt.edu/campus_life/student_handbook/general_information.shtml#academic_integrity).

####  Classroom Attendance Protocol

As we begin the Spring 2022 semester, class attendance policies and procedures as outlined in the Student Handbook are in place.  To paraphrase the Student Handbook, Dordt University as an institution remains committed to in person instruction for face-to-face courses.  As a result, you are expected to be present for every class period and laboratory period.  Should you need to miss class for any reason, contact your instructor as soon as possible (either prior to the absence or immediately following).  Absences for Dordt-sponsored curricular or co-curricular activities will be communicated by the activity sponsor and are considered excused.

Methods of making arrangements for missed work are back to normal (pre-COVID).  You are responsible to contact your instructor.  Your instructor is not required to provide real time (synchronous) learning for you should you be absent for class for any reason (ex.  Zooming into your real time class).  Your instructor is also not required to provide asynchronous virtual learning materials for you (ex. recordings of missed classes, slide decks, other materials on Canvas).  While some instructors might utilize some of the synchronous/asynchronous methods of making up work on occasion, you should not expect all instructors to provide these experiences automatically. Methods of making up missed work might include:  contacting a fellow student to get notes from class, extensions on assignments or labs, or other methods as determined by your instructor.  Making arrangements for missed class work is your responsibility!
    
Please see your instructor’s specific attendance policy.




### <a id="schedule"></a>Tentative Schedule

As the course will be driven by your work and interests, it is difficult to predict the amount of time that will be spent in each section. However, here is my best guess.

- Chapter 1, Logic: January 17-January 26
- Chapter 2, Intro to Graphs: January 28-February 4
- Chapter 3, Proof Techniques: February 7-February 21
- Chapter 4, Set Theory: Feb 23-March 25
- Chapter 5, Functions: March 28-April 8
- Chapter 6, Graphs: April 11-May 6