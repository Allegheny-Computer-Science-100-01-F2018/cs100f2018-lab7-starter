
# cs100f2018-lab7-starter

Designed for use with [GitHub Classroom](https://classroom.github.com/), this
repository contains the starter for Laboratory 7 in Computer Science 100.

 Since the Travis builds for this repository will initially fail (as evidenced by
 a red &#x2717; appearing in the commit logs instead of a green &#x2714;), the
 programmer is responsible for completing all of the steps needed to satisfy the
 requirements for the assignment, thus causing a &#x2714; to instead appear in
 the commit logs.


## Introduction

This assignment requires programmers to implement and test an bank ATM system.
First, the program will display a welcome message and read the user's card information
from the text file. Then, it will read in user's preferred actions and, finally, produce output
that meets the requirements outlined later in the assignment. As verified by
[Checkstyle](https://github.com/checkstyle/checkstyle), the source programs
must adhere to all of the requirements in the [Google
Java Style Guide](https://google.github.io/styleguide/javaguide.html).

The programmers are also responsible for writing a three-paragraph reflection,
stored in the file `writing/reflection.md`, that explains the challenges that
they faced and the solutions they developed and their strategy for testing their
solution. This is a Markdown file that must adhere to the standards
described in the [Markdown Syntax
Guide](https://guides.github.com/features/mastering-markdown/). Remember, you
can preview the contents of a committed Markdown file by clicking on the name of
the file in your GitHub repository.

The source code of the two Java file must also pass additional tests set by the
[GatorGrader tool](https://github.com/GatorEducator/gatorgrader). As before,
GatorGrader will check to ensure that one of the Java files uses the `new
Date()` construct in the Java code. Moreover, GatorGrader will check the
following characteristics of your implementation:

* The `Atm` program must:
  * Contain at least five single-line comments and two multi-line comments
  * Use at least two `if` and `else` statements
  * Contain at least ten `println` statements to display output
  * Call methods of the other provided class

* The `Account` program must:
  * Contain at least five multi-line comments
  * Not include any `println` statements
  * Include a constructor as specified by the UML diagram in the assignment sheet
  * Include `withdraw`, `deposit` and `getBalance` methods as outlined in the assignment sheet

* The `Offer` program must:
  * Contain at least five multi-line comments
  * Not include any `println` statements
  * Include a constructor as specified by the UML diagram in the assignment sheet
  * Include `setOffer`, `getOfferText` and `getOfferId` methods as outlined in the assignment sheet

When you use the `git commit` command to transfer your source code to your
GitHub repository, [Travis CI](https://travis-ci.com/) will initialize a build
of your assignment, checking to see if it meets all of the requirements. If both
your source code and writing meet all of the established requirements, then you
will see a green &#x2714; in the listing of commits in GitHub. If your
submission does not meet the requirements, a red &#x2717; will appear instead.
The instructor will reduce a programmer's grade for this assignment if the red
&#x2717; appears on the last commit in GitHub immediately before the
assignment's due date.

A carefully formatted assignment sheet for this project provides more details
about the steps that a computer scientist should take to complete this
assignment. You can view this assignment sheet by visiting the listing of
laboratories on the course web site.

## Learning

If you have not done so already, please read all of the relevant [GitHub
Guides](https://guides.github.com/) that explain how to use many of the features
that GitHub provides.

To do well on this assignment, you should also review Chapters 1 through 3 and study
Sections 4.1 through 4.5. To enhance your understanding of some points in this
laboratory assignment, you should also review the class exercise. Please see
the course instructor or one of the teaching assistants or tutors if you have
questions about any of these reading assignments.

## Commands

To get started in using the GatorGrader tool, you can change into the directory
for this assignment and type the command `gradle grade` in your terminal.
Running this command will produce a lot of output that you should carefully
inspect. If the output indicates that GatorGrader judges that there are no
mistakes in the assignment, then this means that your source code and writing
are passing all of the automated baseline checks. However, if the output
indicates that there are mistakes, then you will need to understand what they
are and then try to fix them. Travis is not used for this assignment, but
your submission must pass all of the GatorGrader checks locally.

You can also complete several important Java programming tasks by using the
`gradle` tool. For instance, you can compile (i.e., create bytecode from the
program's source code if it is a correct program) the program using the command
`gradle build`. There are other additional commands that you can type:

- `gradle clean`: clean the project of all the derived files
- `gradle check`: check the quality of the code using Checkstyle
- `gradle build`: create the bytecode from the Java source code
- `gradle run`: run the Java program in the command-line
- `gradle tasks`: display details about the Gradle system

To run one of these commands, you must be in the main  directory
for this assignment where the `build.gradle` file is located. Then, you can type
the command in the terminal and study the output.

## Problems

If you have found a problem with this assignment's provided source code, then
you can go to the [Computer Science 100 Lab 7
Starter](https://github.com/Allegheny-Computer-Science-100-01-F2018/cs100f2018-lab7-starter)
repository and create an issue by clicking the "Issues" tab and then clicking
the green "New Issue" button. If you have found a problem with the [GatorGrader tool](https://github.com/GatorEducator/gatorgrader) and the way that it checks you
assignment, then you can follow the aforementioned steps to create an issue in
its repository. To ensure that your issue is properly resolved, please provide
as many details as is possible about the problem that you experienced.

Students who find, and use the appropriate GitHub issue tracker to correctly
document, a mistake in any aspect of this laboratory assignment will receive
 extra credit towards their grade for it.

## Assistance

If you are having trouble completing any part of this project, then please talk
with either the course instructor or a teaching assistant during the laboratory
session. Alternatively, you may ask questions in the Slack team for this
course. Finally, you can schedule a meeting during the course instructor's
office hours.
