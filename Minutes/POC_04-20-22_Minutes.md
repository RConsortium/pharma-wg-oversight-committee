## Minutes of the Pharma Oversight Committee 2022-04-20

### Attendees
* Keaven Anderson
* Bob Engle - Biogen
* Sean Healey = Pfizer
* Andy Nicholls - GSK 
* Joseph Rickert - RStudio

### Absent

* James Black - Roche
* Sumesh Kalappurakal - J&J

Minutes by Joseph Rickert

JBR began the meeting by introducing Sean Healey who was attending his first seating sing since Pfizer joined the R Consortium. 


JBR asked the group to consider the strategic goals for the Pharma working groups in 2022. 

The Submissions working group is heading towards completing the Pilot 2 submission within the next couple of months. It is not clear what direction the group should take after that. The present candidate for Pilot 3 is a submission involving containers. However, it is not clear what technology should be involved and it is also not clear the the FDA will be in a position to work with containers. 

The group agreed that it would be worth while to ask the Submissions WB to try and gather more information about the procedures and equipment setup that the FDA is likely to use to evaluate R submissions through the gateway.

KA noted that Yilong Zhang who has provided leadership and technical expertise in both the Submissions and RTRS WGs is leaving Merck. Both WGs will be hard pressed to replace him.

The discussion then turned towards how we could deepen our relationship with the FDA. KA suggested that we develop a relationship with [Transcelerate](https://www.transceleratebiopharmainc.com/) which can influence FDA activity through the negotiations around [PDUFA](https://phrma.org/policy-issues/Research-and-Development/PDUFA) which occur every five years. 

**Action:** KA agreed to investigate and find a Transcelerate contact.

SH mentioned that the [Accumulus](https://www.accumulus.org/) project and the FDA's [Project Orbis](https://www.fda.gov/about-fda/oncology-center-excellence/project-orbis) are both working to modernize FDA infrastructure. The group agreed that they were both worth investigating.


AN gave a status update for the R Validation Hub WG. This year the group will focus on developing case studies. The general meeting of the WG that will be held next week will feature talks from four companies. A follow up meeting in May will feature four more. AN noted that the project to build out and maintain the [riskmetric](https://cran.r-project.org/package=riskmetric) package will be setback back by Yilong's departure and Doug Kelkhoff stepping back from the project. The group working on the package must fine a new leader. 

AN noted that both the `riskmetric` package and the [risk assessment app](https://github.com/pharmaR/risk_assessment/pull/162) would be more useful if there was a way to run them on the versions of packages being used by the pharma companies and not just the latest versions currently on CRAN. This would require something like being able to feed [MRAN](https://mran.microsoft.com/) snapshots to the app.

**Action:** JBR to discuss the possibility of standing up a cloud base version of the risk metrics software informed my MRAN. 

It was also noted that Mango Solutions might be stepping away from its valid R product. This might present an opportunity for the RC.

**Action:** JBR to investigate

The group briefly discussed that Mike Stackhouse and Michael Rimler have paused the PHUSE [CSRMLW](https://github.com/phuse-org/CSRMLW) working group.

**Action:** JBR to contact Mike Stackhouse and see if RC can help move the project forward.

The next meeting of the group will be on Wednesday, May 18, 2022 at 9AM Pacific Time.


