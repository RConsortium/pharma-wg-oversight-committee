## Minutes of the Pharma Oversight Committee 2022-03-16

### Attendees
* Keaven Anderson
* James Black - Roche
* Andy Nicholls - GSK 
* Joseph Rickert - RStudio

### Absent
* Bob Engle - Biogen
* Sumesh Kalappurakal - J&J

Minutes by Joseph Rickert

JR began the meeting by noting that the [RC blog post](https://www.r-consortium.org/blog/2022/03/16/update-successful-r-based-test-package-submitted-to-fda) announcing the receipt of the letter from the FDA confirming the success of the part 2 submission for Pilot 1 has been published. He also confirmed that work on Pilot 2, which is focused on submitting a Shiny app to wrap the analyses in Pilot 1, has also begun.

JB noted that there have been intensive discussions within Roche about whether being able to submit Shiny apps to the FDA would obviate the need to also submit "listings".

JR then described the work of the RTRS and Certification working groups and stated that he believed that although the Certification WG was making great progress that they would benefit from additional help. 

JR mentioned two other recent RC development that are related to Certification:

1. Orhun Aydin has started an ISC project to develop teaching materials for doing spatial statistics in R with the hope of awarding badges for the successful completion of the various modules.
2. The RC Board of Directors is considering whether it wants to pursue developing an R Certification program as a source of generating income.

In response to the latter, JB informed the group that Roche has developed a Coursera Course which includes using R for "late stage" i.e. clinical trial settings that might be applicable to certification.

JB then brief those present on Roche's work to validate R packages for internal use at Roche and proposed that the methodology employed could be the basis for an industry wide effort managed under the R Validation Hub working group.

The crucial part of the Roche validation effort is that in addition to a number of automated checks, validation involves a human effort to check whether the package does what the package documentation says it does. This includes labor intensive activities such as looking at all of the unit tests for package functions and confirming that they are reasonable. 

Everyone present agreed that this would be a very valuable service for the Pharma companies if it were possible to reach a broad consensus on the process. 
AN also agreed that it made sense for this new effort to be included as a working group under the Validation Hub if we could find a suitable group leader. JB proposed that Kieran Martin, who is presently leading the Roche internal effort, might take this on. AN proposed to put this idea on the agenda for the next R Validation Hub meeting. It was also agreed that the first order of business for the new working group would be to create a short, perhaps two page, paper to lay out the process for assessing R packages. Those present agreed to cooperate towards setting up this new group.


The next meeting of the committee is scheduled for 9AM Pacific time on Wednesday, 4-20-2022.

