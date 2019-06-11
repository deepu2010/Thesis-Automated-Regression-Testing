# Thesis-Automated-Regression-Testing

I did a thesis on **Automated Regression Testing**, as part of my graduate course **CPSC 543 - Software Maintenance** guided by **Dr.James Choi**.

This thesis provides guidelines for implementing automated regression testing in an Agile environment. Regression Testing is a type of software testing used to find whether any new problems occur as a result of software changes. Before applying a change in a program, a program is first tested. After a change is applied, the program is retested in selected areas to determine whether the change has created new bugs or issues, or if the actual change has achieved it’s the planned objective.

**Regression Testing:**

Regression Testing is one of the successful testing method which analyzes the impact of recent changes made to the existing features or new features of the software. Regression testing mainly checks whether the newly added features has modified the existing behavior of software. During regression testing we retest previous test cases to assure all the existing features are working as expected.

**Problem Statement**

Regression tests can be performed manually on small projects and in agile projects regression testing strategy is considered endangered as it consumes more time than other testing strategy such as smoke tests. However, regression testing strategy improves the quality of the software and helps the professionals to revisit test cases after the completion of each sprint. In this document, we recommend best practices to the companies to adapt regression testing in Agile environment. We recommend two approaches

  1. *Risk Based Testing fused with Regression testing strategy*.
  2. *5 step-process model* to implement automated regression testing. 
  
In addition to the 5-process model, we also recommend companies to use Testing Whiz tool to implement automate regression testing effectively.

## Five Step process model for effectively implementing regression testing in Agile Environment:

We recommend following the below practices to successfully implement automated regression testing:

1. Creating the inventory of the workflow present in the application
2. Transform the workflow into test scripts
3. Maintain the version-control of the test scripts as software assets
4. Automate the operation of test scripts based on changes to the application
5. Use the test results as inputs to management's business risk analysis

![Alt Text](https://raw.githubusercontent.com/deepu2010/Thesis-Automated-Regression-Testing/master/5%20step%20process%20model.JPG)

**Three main reasons to perform regression testing are following:**

• When developers fix a bug, add a new functionality, or modify an existing one, they always change a program code. Even a little change may result in a bunch of new bugs. Regression testing is required to identify those bugs.

• In case of changing operating environment, a software tester can reveal and localize undesirable side effects by performing of regression testing.

• Effective regression testing is a key to the successful integration testing. A software tester should keep in mind that new bugs and side effects may appear after fixing bugs that were found during regression testing. However, a high-quality software product cannot be built without complete and systematic regression testing.


