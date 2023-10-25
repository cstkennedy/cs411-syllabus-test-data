Title: Syllabus: CS 350 Introduction to Software Engineering (@semester@)
Author: @instructor@
Date: @docModDate@
TOC: yes



# Course Description

This course explores the software development process. It will discuss
the major activities common to software development processes, and
some of the ways in which those activities are organized and managed.

Heavy emphasis will be placed on the day-to-day skills required during
software construction. The course will explore lessons and tools
offered by the major successful open-source software efforts.

The course requires each student to participate as a member of a team in a
significant team project. Each student will be required to demonstrate
proficiency in several software development tools.

## Meeting Times and Delivery Method

Students must register for both a lecture section and a recitation
section.

%if _online

* Lectures: No regularly scheduled meetings

    Lecture materials for this course will be available on-line, primarily in
    printed/text form.

* Recitations: Tuesdays 3:50pm to 5:50pm **or** Thursdays 3:50pm-5:50pm (selected weeks)

    **Refer to LeoOnline/BannerXE for your recitation time**

    Recitations will be conducted by network conferencing.

    Attendance is **mandatory** in the scheduled weeks.

    Recordings will **not** be available.

%else

* Lectures: M,W 3:00-4:15, OCNPS 0200 / Zoom

    Real-time attendance is optional. A Zoom stream and recordings
    will be available, with links provided via Canvas.


* Recitations: Tu 9:00-11:00AM, W 9:00-11:00AM (selected weeks)

    Recitations will be conducted by Zoom.

    Attendance is **mandatory**.

    Recordings will **not** be available.

%endif

    * The primary purpose of the recitation is to allow project teams to meet
      with the instructor for periodic evaluation of their progress.

        * For the purpose of these meetings, it will be important that students
          be seated at or connected to their chosen development machine and
          prepared to demonstrate aspects of the project under review.

    Recitation sections will not meet every week, but the scheduled meetings
    listed in the [course outline](doc:outline) are mandatory. During weeks when recitations are not scheduled, project teams
    may wish to use that time for their own meetings.

    As necessary, the instructor may announce open "help" sessions during the
    recitation time periods to provide aid on assignments and labs. Attendance at
    these sessions will be optional.



## Instructor

%if _zeil

|:-------------------------------------------- |:----------------|
| [Steven Zeil](https://www.cs.odu.edu/~zeil)   |  E&CS 3208      |
| (757) 683-4928                               | zeil@cs.odu.edu |

Please make sure to include the course name "CS350" in the subject
line of any email related to this course.

### Office Hours

Office hours are posted online at <http://www.cs.odu.edu/~zeil/officehours/>

General questions about course content and reports of website problems
should normally be asked in MS Teams or via email.

Questions about grades, how to solve assignments and other graded
activities **must** be sent to @email@, not posted in Teams.

For more discussion on course communications, please refer to the
[Communications policy](doc:communications).

%endif

%if _polawar

|:-------------------------------------------- |:----------------|
| [Nisha Polawar](https://www.cs.odu.edu/~npolawar)   |  DRGS:1103A      |
| (757) 683-7740                               | npolawar@cs.odu.edu |

Please make sure to include the course name "CS350" in the subject
line of any email related to this course.

### Office Hours

My office hours :  T,R:1-3pm
                     F:10-12pm

General questions about course content and reports of website problems
should normally be asked in the Forums on Canvas or via email.

Questions about grades, how to solve assignments and other graded
activities **must** be sent to @email@, not posted in Forums.

For more discussion on course communications, please refer to the
[Communications policy](doc:communications).

%endif




%if _kennedy

| **Instructor**    | **Office**   | **Phone #**  | **Email**           | **Home Page & Office Hours**        |
| :------------     | :---------   | :---------   | :-----------        | :---------------------------------- |
| Thomas J. Kennedy | Dragas 1100D | 757.683.7725 | tkennedy@cs.odu.edu | <http://www.cs.odu.edu/~tkennedy>   |

**All email related to this course must have the phrase **CS 350**
somewhere in the subject line.**

\bSidebar

This is my general email policy. However, this is usually $O(n)$ (i.e., an
upper bound).

\eSidebar

I try to respond to all (properly marked) messages before I leave campus each
day (Monday through Friday). On weekends and holidays replies may take a little
longer (around 48 hours).


### Office Hours

My general office hours are available at <https://www.cs.odu.edu/~tkennedy/>.
Instructions for scheduling a formal appointment are listed
[here](doc:officeHours). Note that my office hours are exclusively
web-conference based appointments.

General questions about course content and reports of website problems
should normally be asked in the Forums on Canvas or via email.

Questions about grades, how to solve assignments and other graded
activities must be sent to @email@.

For more discussion on course communications, please refer to the
[Communications policy](doc:communications).

%endif




## Course Pre-requisites

* CS 252 (Introduction to Unix for Programmers)
*  CS 330 (Object-Oriented Programming and Design), *or*
*  CS 361 (Advanced Data Structures and Algorithms)
      * Students who have not taken CS 330 are encouraged to take
      CS 382 (Introduction to Java) as a pre-requisite or, at the very
      least, to work through that
      [courses's website](doc:cs382:outline)
      during the first few weeks of the semester.



%if _kennedy

## Review Recordings

I provide recorded Reviews on the course site. These are, in general, condensed
versions of what would traditionally be live lectures. My recorded Reviews are
available [here](https://github.com/cstkennedy/cs350-examples).

**I expect you to view these Review Recordings**

%endif


# Basic Course Information

## Required Text

Readings from the Internet will be assigned from the course website.

%if _online
## Resources for Getting Started

* ODU [Online Student Orientation](http://www.clt.odu.edu/oso)

%endif

## Computer Accounts

Students will need two network accounts to participate in this class:

* An ODU Midas account. This is the account associated with your
    `@odu.edu` email. It will allow you to log into the course's
    Canvas site. All ODU students automatically receive this
    account, though you may need to activate yours if you are new to
    ODU.

* An account on the CS Dept. network. This will be used for access to
    the CS dept computing resources, and for accessing and submitting
    assignments. You may have a CS account already if you were
    registered for a CS class last semester. If not, the account setup
    can be initiated at <http://www.cs.odu.edu/> by clicking on
    "Account Creation" under "Online Services".


## Hardware & Software Requirements

Students will need frequent access to a PC capable of hosting software
development activities or of connecting remotely to CS Dept servers where such
activities can be performed.

Students will be attending network conferences **requiring** the use of a
microphone. Webcams are optional.

For both remote access to CS Dept servers and for network conferencing, a
good-quality internet connection is important.

The course will introduce students to a wide variety of software packages. All
of these are open-source, free software, but students may need to install some
of these on their chosen development machine (whether their own PC or in their
account on the CS network).


# Course Policies

## Recitation Attendance


Project review sessions will be scheduled for selected
weeks during the recitation periods. Attendance at these is
mandatory. Failure to attend will result in substantial grade
penalties for that portion of the project.

Attendance at other scheduled recitation sessions, as announced in the
course outline, is also mandatory. Failure to attend may result in
grade penalties.

## Due Dates and Late Submissions

%if _kennedy

Late assignments and make-up exams will not normally be permitted.

%else

Programming-style assignments that are automatically graded will be accepted one day late at a 10% penalty, two days late at a 20% penalty, but not accepted after that.

Otherwise, late assignments and make-up exams will not normally be permitted.

%endif

Exceptions to this and other grading policies will be made only in situations
of unusual and unforeseeable circumstances beyond the student's control.
Arrangements must be made prior to the due date in any situations where
the conflict is foreseeable.

"*I've fallen behind and can't catch up*", "*I'm having a busier semester
than I expected*", or "*I registered for too many classes this semester*"
are \emph{not} grounds for an extension.



## Academic Honesty

Everything turned in for grading in this course must be your own work, or, for
team projects, the work of your own team. Opportunities for teamwork will be
clearly identified as such.

Students are expected to conform to academic standards in
[avoiding plagiarism](https://www.odu.edu/content/dam/odu/col-dept/al/docs/plagiarismrev3.ppt).

* Among other things, this means that if you use ideas found on the internet
  (outside of the course website) in your answers to an assignment or exam
  question (including when coding!), you _must_ cite your sources appropriately.

    If you use text directly taken from such sources you must appropriately
    designate the quoted material as such.

The instructor reserves the right to question a student orally or in writing
and to use his evaluation of the student's understanding of the assignment and
of the submitted solution as evidence of cheating.

Students who contribute to violations by sharing their code/designs with others
may be subject to the same penalties.  Students are expected to use standard
Unix protection mechanisms (`chmod`) to keep their assignments from being read
by their classmates. Failure to do so will result in grade penalties, at the
very least.

This policy is \emph{not} intended to prevent students from providing
legitimate assistance to one another. Students are encouraged to seek/provide
one another aid in learning to use the operating system, in issues pertaining
to the programming language, or to general issues relating to the course
subject matter.

> Student discussions should avoid, however, explicit discussion of approaches
> to solving a particular programming assignment, and under no circumstances
> should students show one another their code for an ongoing assignment, nor
> discuss such code in detail.

Violations of this policy will be reported to the Office of Student Conduct and
Academic Integrity for consideration for punitive action.

### Use of Online Resources

You may **not** post details of course assignments, projects, or tests at
online Forums, Bulletin Boards, Homework sites, etc., soliciting help.

You **may** use information that you have not solicited but have located, subject
to the following restrictions:

* If you use someone else's ideas in your your writing or in your code, you must cite
  your sources appropriately. Within code, such citations appear in comments.

    Example:

        /*...*/
        double x = 23.0;
        double xsqrt = sqrt(x);
        // Search algorithm based upon code by S Zeil at
        // https://www.cs.odu.edu/~zeil/cs361/latest/Public/functionAnalysis/index.html#orderedsequentialsearch
        int loc = 0;
        while (loc < arraySize && numbers[loc] < xsqrt)
        /*...*/

* If you use someone else's words, in your writing or in your code, you
  must cite your sources appropriately **and** mark the quoted text. Within
  code, such citations appear in comments.

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

* Failure to appropriately cite any such "found code" will be taken as evidence
  of plagiarism.

* The overall principle stated in the first sentence of this section remains in
  effect. "Everything turned in for grading in this course must be your own
  work." If the bulk of your assignment, code, paper, etc., are
  copied, even with appropriate citation, to the degree that, in the judgment of
  the instructor, you have not demonstrated your own knowledge of the course
  material, you will receive a zero for that exercise.
    * In other words, you only be graded on what _you_ have written.



## Grading

%if _kennedy

| -------------:   | :--- |
| Assignments      | 10%  |
| Semester Project | 60%  |
| Midterm Exam     | 15%  |
| Final Exam       | 15%  |

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

The computation for dropping an assignment grade is

>  `((sum of all assignment grades) - (lowest assignment grade)) / (number of assignments - 1)`

The result is used as the assignment average. The
computation for dropping the Midterm Exam is

> `0.15 * (Final Exam grade) + 0.15 * (Final Exam grade)`


%else

More details on the grading is available [here](doc:grading).

| -------------:   | :--- |
| Assignments      | 15%  |
| Semester Project | 50%  |
| Midterm Exam     | 15%  |
| Final Exam       | 20%  |

I will drop the lowest assignment score.

%endif



# Assignment Grading

Exercises (Assignmetns & Semester Project Phases) will be submitted via GitHub,
with the exception of phases 1 and of the team project, which will be submitted
via Canvas and Trello, respectively.

Unless otherwise announced, the last submission prior to the due date will
be the one graded. If you believe an earlier submission might have scored higher,
it is up to you to recover that earlier submission from git and to commit
and push the earlier code.

Late submissions will not be accepted except as provided for in
 [Due Dates and Late Submissions](#due-dates-and-late-submissions), above.



# Exams

The Midterm Exam and Final Exam will be administered online via Canvas.


%if _kennedy

%else
Students will be required to use
[SmarterProctoring](https://online.odu.edu/academics/exams-and-proctors) to
arrange for a live or online proctor.

%endif


# Topics

Topics will include:

* Software development processes, including the waterfall, unified OO, and
  extreme programming models
* Revision management: local, centralized, & distributed approaches
* Configuration Management: project configuration, managing external libraries
* Continuous Integration, including testing in the cloud (AWS)
* Analysis tools, including CheckStyle, SpotBugs, & PMD
* Build Management, including Ant, Maven, and Gradle
* Unit & Integration Testing: coverage, JUnit-style frameworks, mocking, designing for
  testability
* Test-driven development
* Issue tracking
* Software Forges & Repositories
* Dev-Ops


## Objectives

Students completing this course should be able to:

* Demonstrate an understanding of the overall strategy of software development:

    - Discuss the phases and component activities of software development

    - Assess the likely impact of popular software process development
      models on a project.

    - Discuss common team organizations and roles in software development.

* Work with software requirements documents

    - Read common forms of requirements documents

    - Write at least one standard form of requirements document

    - Apply requirements to guide the subsequent construction of software

* Apply best practices in collaborative software construction

    - Discuss the issues and problems involved in collaborative
      development of software.

    - Evaluate the suitability of alternative best practices for a
      software construction project.

    - Support common best practices of via a modern IDE and associated tools

    - Apply a variety of software measurement and evaluation techniques.


## Expectations

Students will engage in team projects in this course. Students are expected to
**actively** participate in and contribute to their teams, and the level of
engagement with the team will be part of the grade.

Procrastination and just-before-the-deadline submissions are detrimental to any
team dynamic, and will result in lowered grades.


# Semester Project - Civility among Team Members

You will be working with your team for many weeks, and there will be
a lot of communication expected among team members.

In accordance with the [Monarch
Creed](https://www.odu.edu/about/monarchcitizenship#tab152=2) and
[Code of Ethics](https://www.odu.edu/about/monarchcitizenship/code-of-ethics),
I expect all students to maintain _civility_ in their dealings with one
another.

> Language that is abusive, harassing, or threatening to members of the class
> or that fosters high levels of personal and emotional anxiety may, at the
> instructor's discretion, result in expulsion from the team.  Given the
> importance of the team project to this course, that is likely to result in
> a failing grade. Egregious or repeated violations will be referred to
> appropriate authorities for possible disciplinary action.


# Educational Accessibility

Old Dominion University is committed to ensuring equal access to all
qualified students with disabilities in accordance with the Americans
with Disabilities Act. The Office of Educational Accessibility (OEA)
is the campus office that works with students who have disabilities to
provide and/or arrange reasonable accommodations.

* If you experience a disability which will impact your ability to
  access any aspect of my class, please present me with an
  accommodation letter from OEA so that we can work together to ensure
  that appropriate accommodations are available to you.

* If you feel that you will experience barriers to your ability to
  learn and/or testing in my class but do not have an accommodation
  letter, please consider scheduling an appointment with OEA to
  determine if academic accommodations are necessary.

The Office of Educational Accessibility is located at 1021 Student
Success Center and their phone number is (757) 683-4655. Additional
information is available at the OEA website
[http://www.odu.edu/educationalaccessibility/](http://www.odu.edu/educationalaccessibility/)

# General University Policies

The [ODU Catalog](http://catalog.odu.edu/) lays out a wide variety of
University policies that are binding upon both students and faculty. All
students are required to abide by these.
