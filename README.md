# AB_test
This project is an interpretation of the results of the AB test, which tests the new payment mechanism of the educational platform.  

During testing of one hypotesis, for the target group was offered a new mechanism for paying for services on site. The control group remained with the basic mechanism.
**The task is to analyze results of experiment and decide wether it is worth launching the new payment mechanism for all users.**

Data
groups.csv - a file with information whether user belongs to the control group (A) or from the target group (B)

groups_add.csv - an additional file with users that was sent 2 days after data transfer

active_studs.csv - a file with information about users who logged into the platform on the days of the experiment

checks.csv - a file with information about user payments on the days of the experiment

During the implementation of the project following metrics were calculated:
- CR
- ARPU
- ARPPU

**The chi-square test was used to compare CR in the two groups.**
**The bootstrap was used to compare medians of revenue distribution in two groups.**
