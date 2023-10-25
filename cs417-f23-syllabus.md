Title: CS 417 (@semester@)
Date: @docModDate@
TOC: yes
Author: Thomas J. Kennedy


# Course Description

**Catalog Description**

Algorithms and software for fundamental problems in scientific computing.
Topics: properties of floating point arithmetic, linear systems of equations,
matrix factorizations, stability of algorithms, conditioning of problems,
least-squares problems, eigenvalue computations, numerical integration and
differentiation, nonlinear equations, iterative solution of linear systems.


## Instructors

Mr. Thomas Kennedy & Dr. Nikos Chrisochoides


### Office Hours

Office Hours are listed on my CS homepage, <https://www.cs.odu.edu/~tkennedy>.

The best way to get help is to come to office hours. If you cannot make office
hours, please send an email to discuss your questions. I am available via
email, <tkennedy@cs.odu.edu>, and network conferencing. In general you can
expect a response within 24 hours. On holidays or weekends, turn-around-time
will be closer to 48 hours.


## Prerequisites

Students are expected to have a strong foundation in mathematics and
programming:

1.  **Math 316** - Good understanding of calculus and linear algebra.
2.  **CS 250 or CS 251 or CS 253** - Programming skills in a language such as:
    C/C++, Python, Rust, or Java.


## Meeting Times & Delivery Method

- **Location:** Gornto 0201 and Via Zoom (refer to Course Collaboration Tool in
  Canvas)
- **Time:** Tuesday and Thursday from 1:30pm to 2:45pm

%if _covid

> The provision of face-to-face lectures and live Zoom streams are contingent
> on the setup of the classroom and supporting equipment, and the general level
> of Covid-19 activity in the Norfolk/Virginia Beach area. If I become
> uncomfortable with the safety precautions being taken, or feel that the 
> classroom environment and equipment detract from the quality of the course,
> then I reserve the right to change to a pure web conferencing delivery mode.

%endif

# Basic Course Information

## Reference Texts

**Class notes are available on Canvas and the course site**. Supplemental
texts are optional:

1.  (Optional) Elementary Numerical Analysis: An Algorithmic Approach,
    by Samuel Daniel Conte, Carl De Boor

2.  (Optional) Numerical Analysis: An Introduction, By Walter Gautschi.

3.  (Optional) Data Structures and Algorithms in Python Book by Michael
    H. Goldwasser, Michael T. Goodrich, and Roberto Tamassia

4.  (Optional) Advanced Calculus: Second Edition by David V. Widder


# Course Policies

## Class Attendance

During lectures, we will be covering material from my notes. Lecture
will also consist of the exploration of several real world problems not
covered in any book. I may assign (or announce through Canvas) a
reading assignment or thinking assignment at the end of each lecture.

You are responsible for the contents of all lectures. Ideally, I expect you to
attend lecture and to arrive on time. If you must miss a class, you are
responsible for all material (e.g., lecture and assignments). I expect you to
watch the recorded lecture within 24 hours.


## Due Dates & Late Submissions

I do not accept late work. Exceptions to this and other grading policies will
be made only in situations of unusual and unforeseeable circumstances beyond
your control, and such arrangements must be made prior to the due date in any
situations where the conflict is foreseeable.


## Classroom Conduct

Please be respectful of your classmates and instructor by minimizing
distractions during class. Cell phones must be turned off during class.


## Academic Integrity

By enrolling in CS417 & CS517, you are expected to uphold the standards
of academic integrity set by the Old Dominion University
(<https://www.odu.edu/oscai>).


## Submission (Written Exercises)

All written exercises must be submitted through Canvas in PDF
format. Each such submission must take the form of a single multi-page
PDF document. **Failure to follow these requirements will result in a zero.**

All work must be readable. Make sure that all submitted PDFs are readable,
e.g.,

  - content is not cut off
  - writing (or text) is not faded (i.e., too light to read)

Problems must be submitted in order. Any scans with the problems listed out of
order will result in a zero.

**Show your work.** Partial credit will not be awarded if:

  - intermediary steps are not shown
  - intermediary steps are not legible

If there is insufficient work to show how you arrived at an answer, you will
not receive full credit.


## Scroll Down

**Make sure to scroll down. Most exercises (Homework Assignments, Machine
Assignments, and Exams) consist of multiple pages.**


## Submission (Programming Exercises)

All programming exercises (e.g., Machine Assignments) must be submitted
as a single zip file (zip) or tarball (tar.gz, tar, or tgz). Unless
explicitly stated in the prompt, other formats will not be accepted.
Each submission must include:

  1. A brief [ReadMe file](doc:exampleReadme) that specifies how to compile and
     run your code.
  2. Makefiles (or equivalent build files) for any compilable code.

    - For C/C++, I recommend make or Cmake
    - For Java, I recommend Gradle
    - For Rust, stick with Cargo
    - For Python, no build file is required. Python is an interpreted language

IDE (e.g., Code::Blocks, Eclipse, or VSCode) projects are **not** build files.
No credit (i.e., zero points) will be awarded for any compilable code
submitted without an appropriate build file.

All code must follow best practices, including:

  - Documentation
  - Indentation and spacing
  - Naming conventions
  - Top-down design (i.e., no monolithic functions)
  - D.R.Y
  - Language specific best practices


### Permitted Languages

You may used any combination of C, C++, Java, Python (3.8+), and Rust. All
other languages must be discussed with the instructor before assignment/project
submission.

Extra consideration will be given to **novel solutions (e.g., those
written in a functional language)**.


## Computer Accounts

Students will need an account on the CS Dept. Linux network to participate in
this class. This account is unrelated to any University-wide account you may
have from ODU's Information Technology Services (ITS).

If you have had a CS Unix account in the recent past, you should find it still
active with your login name, password, and files unchanged. If you have had an
account and it has not been restored, contact the CS Dept systems staff at
root@cs.odu.edu requesting that it be restored.

If you do not yet have such an account, go to the [CS Dept. home
page](https://www.cs.odu.edu/) and look for "Account Creation" under "Online
Services". All students in this course are responsible for making sure they
have a working CS Unix account **prior to** the second week of class.


# Grading <sup>3 </sup>

Final grades will be computed using the following weights:

|                            | **CS 417**    | **CS 517**    |
| :------------------------- | ------------: | ------------: |
| **Homework**               | 30\%          | 25\%          |
| **Machine Assignments**    | \-\-          | 5\%           |
| **Exam 1**                 | 15\%          | 15\%          |
| **Exam 2**                 | 15\%          | 15\%          |
| **Semester Project**       | 10\%          | 10\%          |
| **Final Exam**             | 30\%          | 30\%          |
| **Total**                  | 100\%         | 100\%         |

Final course grades will be assigned based on the standard 10-point
scale <sup>1</sup>:


| **Point Range**    | **Letter Grade** |
| :----------------- | :--------------  |
| 90 – 100           | A                |
| 80 – 89            | B                |
| 70 – 79            | C                |
| 60 – 69            | D                |
| 59 and Below       | F                |

1.  I will apply pluses (+) and minuses (-) to letter grades as
    appropriate.

2.  **CS417 students are encouraged to complete Machine Assignments. 5\% of your
    Machine Assignment average will be added to your Final Grade.**

3. Your Final Exam percentage can be used to replace your Exam 1 or Exam 2
   grade... if your Final Exam percentage is higher. *Note that both Exam 1 and
   Exam 2 can potentially be replaced.*

%if _percentageChange
4.  **Grade weights may be adjusted. Particular consideration will be
    given to the Semester Project weight.**
%endif

# Exams

Exams will be administered online through Canvas.


# Tentative Topics

**Part I\***

1.  MACHINE ARITHMETIC AND RELATED MATTERS
    - Machine Arithmetic and Rounding
    - The Condition of a Problem and Algorithm
2.  APPROXIMATION
    - Least Squares Approximation
3.  INTERPOLATION
    - Polynomial Interpolation
    - Approximation and Interpolation by Spline Functions
4.  NONLINEAR EQUATIONS
    - Examples, Iteration, Convergence, and Efficiency
    - Method of False Position
    - Secant Method
    - Newton’s Method

------------------------------------------------------------------------

**Part II\***

1.  NUMERICAL DIFFERENTIATION AND INTEGRATION
    -   Numerical Differentiation
    -   Numerical Integration

------------------------------------------------------------------------

**Topics of Interest\* (Time Permitting)**


2.  MATRIX COMPUTATIONS -- SYSTEMS OF LINEAR EQUATIONS
    -   Gauss Elimination and LU Factorization: Basic Algorithms
    -   Iterative Methods: Basic Algorithms

\* **The topics covered and time spent on each topic may change based on
class performance and class pacing.**


## Objectives

This course is designed as an introduction to the basics numerical
analysis. At the end of this course students will be able to:

1.  Examine the impact of finite arithmetic on computation.
2.  Formulate numerical approximation problems and investigate their
    solutions via programming.
3.  Investigate the relationship between mathematical models and their
    matrix representations.
4.  Synthesize solutions from simpler parts.
5.  Design algorithms and prove their correctness using theory/analysis
    as building blocks.
6.  Examine the spatial complexity, temporal complexity, and
    computational complexity of numerical solvers.
7.  Implement numerical software using existing libraries.
8.  Test and verify the correctness of their own codes using model
    problems and principles from theory.
9.  Utilize vocabulary and terminology used by engineers and applied
    mathematicians.
10. Summarize the literature and utilize basic software packages on
    numerical approximation.
11. Discuss research issues in numerical computing.


## Expectations

This course covers theory oriented and math oriented topics and problems. You
are expected to review required mathematics, programming, and theory as
directed. If whilst reviewing you would like direction or clarification contact
the instructor (via email or in the discusion board).

We discuss various notations (for math and pseudocode) in this course. Keep in
 mind _"That it is just notation."_ Familiarizing oneself with unfamiliar
notations is a skill we will endeaver to develop this semester.

**If you have questions... Ask the instructor** The cliché *"If you have a
question... at least one of your classmates has the same question."* is true
(especially this semester).


# Academic Accessibility

Old Dominion University is committed to ensuring equal access to all
qualified students with disabilities in accordance with the Americans
with Disabilities Act. The Office of Educational Accessibility (OEA) is
the campus office that works with students who have disabilities to
provide and/or arrange reasonable accommodations.

- If you experience a disability which will impact your ability to
  access any aspect of my class, please present me with an
  accommodation letter from OEA so that we can work together to ensure
  that appropriate accommodations are available to you.

- If you feel that you will experience barriers to your ability to
  learn and/or testing in my class but do not have an accommodation
  letter, please consider scheduling an appointment with OEA to
  determine if academic accommodations are necessary.

The Office of Educational Accessibility is located at 1021 Student
Success Center and their phone number is (757) 683-4655. Additional
information is available at the OEA website
(<http://www.odu.edu/educationalaccessibility/>).
