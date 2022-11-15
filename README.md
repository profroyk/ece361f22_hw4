# ECE 361 Homework #4 -- Stack ADT, Reverse Polish Notation calculator, and make
## <i>This assignment will be worth 100 points and is due by 10:00 PM on Sunday 20-Nov-2022</i>
## <b>No late assignments accepted after 10:00 PM on Tue, 22-Nov-2022 - I am planning to review the solutions in class on Wed</b>

### After completing this assignment students should have:
- Gained experience developing and using reusable ADT's (Abstract Data Types)
- Developed an ADT for a stack
- Developed and tested a stack-based application using the Stack ADT you created
- Created a make file to control the build process of your applications


### Introduction

We are using GitHub classroom for this assignment so make sure you make a final push to your GitHub repository for the assignment before the deadline.  Source code for your programming solutions should have a .c extension.  Header files should have a .h extension.  Your transcripts (bash terminal log files) should be submitted as text files (.txt).  Name all of the files in the repository with descriptive names.  Be sure your code is organized well, uses meaningful variable names, and includes comments that aid in understanding the code.

<b><i> NOTE: Each of your console log files should identify you as the owner of the transcript and list the current working directory for your transcript.  This can be done by clearing the screen (clear to the bash prompt) and executing a whoami command followed by a pwd and/or by including code in your application that starts with a greeting message and displays the current working directory.  See the code in previous assignments for the snippet of code to do this.

You will submit your work via a private repository using GitHub classroom. We would also like you to submit an archive (.zip) after your final commit to GitHUB to your Canvas Homework #4 dropbox.

NOTES:
-  If you decide to leverage (borrow) existing code for your solutions other than the code we provided please acknowledge the source. We know how to use Google, too, so copying existing code from the web without acknowledging the source will lead to serious consequences if you are caught cheating.

- You may collaborate with your classmates in the design of the application, but you are all expected to submit original work.  You should do, and submit, your own work. There is a difference between collaboration and copying - you don't want to be caught doing the latter since that could affect both your final grade and the grade of the student you copied from.

- Please post questions on the assignment to the Homework #4 discussion forum on Canvas.  Doing so helps your fellow students understand the assignment, makes it easier for Emily and I to keep up with questions, and avoids the risk that your question will slip out of our view.  You may post anonymously in the forum.



### Assignment:
Not much to say here.  The assignment is described in ece361f21_hw4.pdf. - Problem 2 asks you to create a make file for one of your RPN calculator applications.  Your make file should control the build process and include a "clean" target to delete all but the .c and .h source code files.   Once you create your make file create a new transcript that uses the make file to build your application.  Next execute the program.  Finish off by running your make file with the clean target and do an ls to show that the intermediate and executable have been deleted.

The assignment includes an extra credit opportunity worth up to 5 points.  Make sure your base application works reliable and is well documented before you tackle the extra credit.  Do the math; 5 points vs. up to 80 points. We will grade your base application whether you do the extra credit version or not.  The extra credit points will only apply if your base application is functional.  
