Title: CS 330: Syllabus (@semester@)
Author: @instructor@
Date: @docModDate@
TOC: yes

# Basic Course Information

%if _kennedy

The course schedule and website are located at
<https://www.cs.odu.edu/~tkennedy/cs330/@sem@>.

%endif

%if _hosni

The course schedule and website are located at
<https://www.cs.odu.edu/~tkennedy/cs330/shosni/latest>.

%endif

**Catalog Description**

Laboratory work required. The techniques and idioms of object-oriented
programming in C++ and Java. Methods of object-oriented analysis and design
with the Unified Modeling Language. Multi-thread programs, synchronization, and
graphic user interfaces


%if _kennedy

## When and Where

I am teaching two sections of CS 330, one live and one online. Both sections
use the same syllabus and course materials.


### Live Section

  - CRN 15114 - On Campus

**Meets:** Monday, Wednesday, and Friday from 1:00pm to 1:50pm, Dragas 1117.


### Web Section 

  - CRNs 36559, 36560, and 36561

This course is online and has no regularly scheduled lectures.

%endif

%if _hosni

### Web Section

  - CRNs 20542, 20544, and 20545

This course is online and has no regularly scheduled lectures. There
may be a limited number of attendance-optional network conferences
(announced on Canvas).

%endif


## Objectives

This course will explore the techniques of object-oriented programming,
analysis, and design. The emphasis will be upon the development of clean
interfaces that permit easy modification and reuse of software components.
Other techniques, drawn from outside the object-oriented approach, that
significantly contribute to this goal will also be discussed.

Students will gain facility in an object-oriented programming language and will
learn the constructs that differentiate such languages from others. This course
will explore the idioms and styles of object-oriented programming in C++ and
Java, with emphasis upon how these contribute to reusable software components.

Students will learn how to use object-oriented techniques in support of
programming. In particular, students will be introduced to the process of
object-oriented analysis as a means of understanding an unfamiliar problem
domain. Students will learn to build and use models, expressed in the Unified
Modeling Language (UML) to codify and evaluate that understanding and to evolve
system requirements. Students will learn how to use those models to facilitate
a smooth transition from analysis to design and from there to implementation.

## Textbooks

Most assigned reading will be from books and other sources available on-line.

**Required:**

* Any reasonable C++ text that covers classes and inheritance (e.g.,
  your CS250 or CS 333 textbook)
* <https://en.cppreference.com>

# Communications

## Instructor

%if _kennedy

| **Instructor**    | **Office**   | **Phone #**  | **Email**           | **Home Page & Office Hours**        |
| :------------     | :---------   | :---------   | :-----------        | :---------------------------------- |
| Thomas J. Kennedy | Dragas 1100D | 757.683.7725 | tkennedy@cs.odu.edu | <http://www.cs.odu.edu/~tkennedy>   |

%endif

%if _hosni

| **Instructor** | **Office** | **Phone #** | **Email**      |
| :------------  | :--------- | :---------  | :-----------   |
| Sarah Hosni    | Dragas     |             | shosni@odu.edu |

%endif

Important: All email related to this course should have the phrase **CS 330**
somewhere in the subject line.  This flags your message in my mailbox for
faster attention.

%if _kennedy

\bSidebar

This is my general email policy. However, this is usually $O(n)$ (i.e., an
upper bound).

\eSidebar

I try to respond to all (properly marked) messages
  
  - before I leave campus each day (Monday through Friday)
  - within 48 on weekends & holidays.

**Any delays in replying to email will be noted in a Canvas Announcement.**

%endif


### Office Hours

%if _kennedy

My general office hours are available at <https://www.cs.odu.edu/~tkennedy/>.
Instructions for scheduling a formal appointment are listed on the same page
and [here](doc:officeHours).  My office hours consist of web-conference (Zoom)
appointments.

General questions about course content and reports of website problems should
normally be asked in the Forums on Canvas or via email.

%endif

%if _hosni

My general office hours are:

  - Tuesdays 9:00am to 10:00am
  - Wednesdays 11:00am to 12:00pm

My office hours are typically 15-30 minute Zoom meetings. Please email me
(<shosni@odu.edu>) to schedule a time slot when needed.

%endif

Questions about grades, how to solve assignments and other graded activities
must be send to @email@.

For more discussion on course communications, please refer to the
[Communications policy](doc:communications).


# Course Prerequisites

The prerequisites for this course are:

* CS 250, Problem Solving and
   Programming II, or [CS 333](https://www.cs.odu.edu/~zeil/cs333/latest/), Problem Solving in C++

*  [CS 252](https://www.cs.odu.edu/~zeil/cs252/latest/), Introduction to Unix for Programmers

Note that, if it has been some time since you took CS 250 or 333, or if you
received weak grades in them, then you may need to do some review work to
prepare for this class.

If you are a transfer student who took equivalent courses elsewhere, you would
do well to review the material on those course websites and look for topics
that may not have been covered in your prior courses, because course
"equivalence" is often a very rough approximation. **Pay particular attention
to the material on design, testing, and debugging**, as these are often given
short shrift at other institutions.

Either way, if you need to review any of the prerequisite topics described
below, the time to do so is early in the semester, *before* you need it to
understand the lectures or are called to use it in assignments.


## General Programming Knowledge

Students should be familiar with certain basic programming techniques that are
largely independent of any specific programming language:

  * using editors, compilers and other basic software development tools.
  * basic software design (i.e., stepwise refinement and top-down design)
  * software testing, including the use of scaffolding code (stubs and
    drivers), selection of test cases for black-box testing, and head to head
    testing.

  * debugging, including the use of debugging output, the use of automatic
    debuggers to set breakpoints and trace program execution, and the general
    process of reasoning backwards from failure locations to the faulty code
    responsible for the failure.

## C++

I will assume that you are familiar with the basics of C++, including

  * the various C++ statements and control-flow constructs,
  * the built-in data types,
  * the use of arrays, pointers, pointers to arrays, and linked lists,
  * the use and writing of functions, and
  * the basic use of structs and classes for implementing
       abstract data types.

## Java

No prior knowledge of Java is assumed.

  * In general, CS students at the 300 level should be able to pick up
      new programming languages with only moderate effort. Because Java
      is closely related to C++, this is particularly true of students
      moving from C++ to Java.

  * If you believe that you need a more structured aid to learning
      Java, the 1-credit course
      [CS382](https://secweb.cs.odu.edu/~zeil/cs382/latest) presents the basics of
      the language in a self-paced form. In fact, much of the course
      material for CS382 will be listed as required reading for this
      course.

  * When the CS 330 Outline page lists a section of 382 for
          readings, students are expected to both read the 382 lecture
          notes and to do the associated 382 labs. You will not be
          expected to do the 382 assignments or to take the 382 exam.

    You may, if you wish, choose to register for CS382 and earn
          credit for it. In that case, you will be doing largely the
          same set of readings, but will then be obligated to do the
          assignments and exam for that course.

  * CS 330 will pick up with Java topics more advanced than are
        currently covered in 382, including multi-threading and the
        development of GUIs and in general will explore how to use
        Java in a truly Object-Oriented style.


## Python 3 & Rust

Prior knowledge of [Python](https://docs.python.org/3/) and
[Rust](https://www.rust-lang.org/learn) is neither expected nor assumed.


## Unix/Linux

All students in the course will receive accounts on the CS Dept. network,
and knowledge of how to work with the Linux servers is part of the course
prerequisites. This course does not require familiarity with shell scripting.
All other topics in CS 252 are required.

> Some assignments will require the use of software available only on the Linux
> servers. Others may require (or, at least, be simplified by) use of the X
> windowing system.


## General Computer Literacy

You will be studying techniques in this course for preparing
professional-quality software documentation. The key embedded word in "software
documentation" is "document". Students taking this course should be able to use
word processors and other common tools to produce good quality documents,
including mixing text and graphics in a natural and professional manner.


# Assignments

Assignments for this course will include *programming assignments* (in C++ and
Java), which must be done on an individual basis, and *design assignments*,
which may be done in small teams.


## Expectations

**It is my expectation that you have completed approximately 70% of each
assignment once half the allotted time has passed.** For a two week assignment
this would be one week. This will allow you sufficient time to address any
issues, refine your testing process, and discuss your solution with me during
my office hours.

I expect every student to discuss each assignment with me at least once.


## Assignment Grading

Assignments will be turned in through the CS submission system, rather than
through Canvas--more information is available [here](doc:submitting). Most
of the assignments will be graded by an automatic grader. The results will be
sent to your ODU email account. 

Unless the assignment explicitly states otherwise, you may submit a total of
three times per assignment; the instructor will take the last of the marks,
although you may request that your score be "rolled back" to an earlier one.
You may NOT submit after viewing the sample solution.


### Auto-Grader & Testing

Test driven development is a topic of particular import--not only in academia,
but in industry.

*You will be expected to make use of Blackbox Testing*. This is a topic of
particular import. Blackbox testing is covered in CS 250--a prerequisite for
this course. You will also need to make use of white-box testing and unit
testing. These are topics discussed in CS 250. Take the first week to review
these concepts. You will find the necessary materials on the CS 333 course
site.

Difficulties with the tests performed by the Auto-Grader should be addressed
after the first assignment submission (which should in turn occur no later than
halfway to the assignment deadline). If a program fails a test, there is
usually an edge-–or corner-–case for which you--the student-- did not account.

**All tests are designed by me--the instructor.** The Auto-Grader runs tests
that I use to evaluate my solution. These tests evaluate mechanics of
import--e.g., dynamic binding and function overloading.

Be systematic in all changes to your assignment solution and modifications to
your tests. Do not haphazardly make changes to an assignment and resubmit
hoping for a better grade. Treat each submission attempt as your final
submission. Ask for guidance before each subsequent submission.


## Computer Accounts

Students will need an account on the CS Dept. Unix network to participate in
this class. This account is unrelated to any University-wide account you may
have from the ODU's Information Technology Services (ITS).

If you have had a CS Unix account in the recent past, you should find it still
active with your login name, password, and files unchanged. If you have had an
account and it has not been restored, contact the CS Dept systems staff at
root@cs.odu.edu requesting that it be restored.

If you do not yet have such an account, go to the [CS Dept. home
page](https://www.cs.odu.edu/) and look for "Account Creation" under "Online
Services". All students in this course are responsible for making sure they
have a working CS Unix account **prior to** the first assignment.

## Compilers

The "official" environment in which students' programming assignments will be
evaluated is defined by our Dept. Linux servers. It is the student's
responsibility to be sure that their code compiles and executes using the
compilers and run-time environment provided there. As of this writing, the
compiler versions used are

* C++: g++ 9.3.0
* Java: 11.0.12

[Help is available](doc:faq) for students wishing to install
compatible compilers and IDEs on their own PCs.


# Review Recordings (Recorded Lectures)

Recorded Reviews are included in the course outline. These are, in general, condensed
versions of my live lectures. The full set of recorded Reviews is available
[here](https://github.com/cstkennedy/cs330-examples).

**I expect you to view these Review Recordings**

# Course Policies

## Due Dates and Late Submissions

Late papers, assignments, projects, and make-up exams will not normally be
permitted.

Exceptions will be made only in situations of unusual and
unforeseeable circumstances beyond the student's control, and such
arrangements must be made prior to the due date in any situations
where the conflict is foreseeable.

"*I've fallen behind and can't catch up*", "*I'm having a busier
semester than I expected*", or "*I registered for too many classes
this semester*" are \emph{not} grounds for an extension.

Extensions to due dates will not be granted simply to allow
"porting" from one system to another. "*But I had it working on my home
PC!*" is not an acceptable excuse.


## Academic Honesty

Everything turned in for grading in this course must be your own work. If an
assignment is **explicitly** described as a team assignment, it must be the
work of the team members only.

The instructor reserves the right to question a student orally or in writing
and to use his evaluation of the student's understanding of the assignment and
of the submitted solution as evidence of cheating.  Violations will be reported
to the Office of Student Conduct & Academic Integrity for consideration for
possible punitive action.

Students who contribute to violations by sharing their code/designs with others
may be subject to the same penalties.

* Students are expected to use standard Unix protection mechanisms (`chmod`) to
  keep their assignments from being read by their classmates. Failure to do so
will result in grade penalties, at the very least.

This policy is \emph{not} intended to prevent students from providing
legitimate assistance to one another. Students are encouraged to seek/provide
one another aid in learning to use the operating system, in issues pertaining
to the programming language, or to general issues relating to the course
subject matter.

> Students should avoid, however, explicit discussion of approaches to solving
> a particular programming assignment, and under no circumstances should
> students show one another their code for an ongoing assignment, nor discuss
> such code in detail.


**Use of Online Resources**

You may **not** post details of course assignments, projects, or tests at
online Forums, Bulletin Boards, Homework sites, etc., soliciting help.

You may use information that you have not solicited but have located, subject
to the following restrictions:

* Just as when writing a paper, if you use someone else's
  ideas, you must cite your sources appropriately. Within code, such
  citations appear in comments.

    Example:

        /*...*/
        double x = 23.0;
        double xsqrt = sqrt(x);
        // Search algorithm based upon code by S Zeil at
        // https://www.cs.odu.edu/~zeil/cs361/latest/Public/functionAnalysis/index.html#orderedsequentialsearch
        int loc = 0;
        while (loc < arraySize && numbers[loc] < xsqrt)
        /*...*/

* Just as when writing a paper, if you use someone else's
  words (code), you must cite your sources appropriately **and** mark
  the quoted text. Within code, such
  citations appear in comments.

    Example:

        /*...*/
        double x = 23.0;
        double xsqrt = sqrt(x);

        // Begin quoted code from  S Zeil at
        // https://www.cs.odu.edu/~zeil/cs361/latest/Public/functionAnalysis/index.html#orderedsequentialsearch
        int loc = 0;
        while (loc < listLength && list[loc] < searchItem)
        {
            ++loc;
        }
        // End quoted code

        /*...*/

* Failure to appropriately cite any such "found code" will be taken as
    evidence of plagiarism.

* The overall principle stated in the first sentence of this section remains in
  effect.  "Everything turned in for grading in this course must be your own
  work."   If the bulk of your assignment, project, test answer, etc., are
  copied, even with appropriate citation, to the degree that, in the judgment of
  the instructor, you have not demonstrated your own knowledge of the course
  material, you will receive a zero for that submission.

%if _kennedy

## Attendance

**The Attendence section of the syllabus only applies to the live section.**

Lecture attendance is not required, but you are responsible for all material
covered and announcements made in class. If you are going to miss lecture, be
sure to get notes, handouts, etc., from another class member.

%endif

## Grading

| ------------- | --- |
| Assignments:  | 50% |
| Midterm Exam: | 20% |
| Final Exam:   | 30% |

\bExample{Grading Schmema}

| Percent     | Letter Grade | 4pt Value |
| :---        | :-----:      | :------   |
| $\geq 85$   | A            | 4.0       |
| $\geq 80.5$ | A-           | 3.7       |
| $\geq 74.5$ | B+           | 3.3       |
| $\geq 70$   | B            | 3.0       |
| $\geq 60$   | B-           | 2.7       |
| $\geq 59.5$ | C+           | 2.3       |
| $\geq 55$   | C            | 2.0       |
| $\geq 50.5$ | C-           | 1.7       |
| $\geq 44.5$ | D+           | 1.3       |
| $\geq 40$   | D            | 1.0       |
| N/A         | D-           | 0.7       |
| $< 39$      | F            | 0.0       |

\eExample

Your *Final Course Grade* will be computed by both: 

  - dropping one assignment grade
  - replacing your Midterm Exam grade with your Final Exam grade (iff your
    Final Exam grade is higher).

### Assignment Drop vs Midterm Exam Drop

All final grade computations are based on 4pt scores (as listed on the Scores &
Statistics Page). The computation for dropping an assignment grade is

>  `((sum of all assignment grades) - (lowest assignment grade)) / (number of assignments - 1)`

The result is used as the assignment average (50% of your final grade). The
computation for dropping the Midterm Exam is

> `0.20 * (Final Exam grade) + 0.30 * (Final Exam grade)`


## Exams

The Midterm Exam and Final Exam will be administered online via Canvas.


# Educational Accessibility

Old Dominion University is committed to ensuring equal access to all qualified
students with disabilities in accordance with the Americans with Disabilities
Act. The Office of Educational Accessibility (OEA) is the campus office that
works with students who have disabilities to provide and/or arrange reasonable
accommodations.

* If you experience a disability which will impact your ability to access any
  aspect of my class, please present me with an accommodation letter from OEA
  so that we can work together to ensure that appropriate accommodations are
  available to you.

* If you feel that you will experience barriers to your ability to learn and/or
  testing in my class but do not have an accommodation letter, please consider
  scheduling an appointment with OEA to determine if academic accommodations are
  necessary.

The Office of Educational Accessibility is located at 1021 Student Success
Center and their phone number is (757) 683-4655. Additional information is
available at the OEA website
[http://www.odu.edu/educationalaccessibility/](http://www.odu.edu/educationalaccessibility/)

