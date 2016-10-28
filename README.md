Abl: Code Challenge
=================================

Hi there!  We're ecstatic that you're interested in working for Abl's dev team.  To get a better idea of your current development skills, we'd like for you to complete a code challenge - build a program according to a set of requirements.  The actual business requirements are linked below, but here are the general tech requirements:

1. Write your code using whatever language or framework you feel most comfortable in.
1. It doesn't matter you build this as a front-end app, a service, a command line program, etc.
1. Make sure your solution is runnable on Mac OS X or Linux.
1. Do not require any for-pay software.
1. Include instructions for setting up and running your program.

Feel free to email us at [codechallenge@ablschools.com](codechallenge@ablschools.com) if you have any questions.

## Submission Instructions

1. Clone this repository.
1. Create (and switch to) a new branch in your local repository:

  ```bash
  % git checkout -b new-branch-name
  ```

1. Complete the project as described below within your local repository.
1. Create patches from your commits, and place them in a directory:

  ```bash
  % git format-patch master -o submission_patches
  ```

1. Create a .zip file with the contents of the patches directory:

  ```bash
  % zip -r submission_patches.zip submission_patches
  ```

1. Email the .zip file to [codechallenge@ablschools.com](codechallenge@ablschools.com), and put the position you are applying for in the email's subject.

If you have any questions about this submission process, feel free to email us.

#### Why can't I just fork, and submit a pull request?

Unfortunately, Github no longer allows you to fork a public repo and make it private, so your submission would be visible to the entire world.  We'd love to keep this fair and not give the last responders a possible unfair advantage (since they'd be able to see all prior submissions); hence the patch method.

## The Problem

Write a simple program that does the following:

1) Takes in a student name as input
2) Gets that student's schedule from an API (endpoint URLs provided below)
3) Outputs the percentage of time spent in meetings tagged with "instructional"

We will collaborate on adding new functionality to your solution when you come in so be thoughtful about your approach (don't just do the hacky thing).

API urls:

* Students: https://crystal-pepsi.herokuapp.com/students
* Student Meetings: https://crystal-pepsi.herokuapp.com/students/:student_name/meetings (ex: https://crystal-pepsi.herokuapp.com/students/Orion/meetings)

Things we care about:

* Fulfilling the basic requirements
* Breaking the problem into smaller parts and clearly connecting each part
* What approach you take to testing (if any)
* How you organize your code
* What you would do differently if this was for real (no time constraints, etc.)
* Documenting the method for setting up and running your application
* Following the instructions for submission

We don't care about:

* Arriving at a specific answer or working through all of the edge cases
* Lots of features or anything impressive.  It is ok to keep it simple.
* Creating something beautifully styled and aesthetically pleasing
