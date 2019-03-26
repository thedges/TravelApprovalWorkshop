# TravelApprovalWorkshop
THIS SOFTWARE IS COVERED BY [THIS DISCLAIMER](https://raw.githubusercontent.com/thedges/Disclaimer/master/disclaimer.txt).

Package of completed Travel Approval workshop. Use to install completed workshop in to a new org.

Post package installation steps:
  1. Go to <b>Setup > Apps > App Manager</b>. Edit the "Travel Approval" app and make sure to assign it to relevant user profiles in the 5th step.
  2. Add the <b>Travel Approval Workshop</b> permset to your workshop users.
  3. Edit the <b>Travel Approval Request</b> approval process. Change the second approval step from "Let the submitter choose the approver manually." to the "Automatically assign to approver" and select your user record.
  4. Follow Workshop lab guide section <b>Create an Application, Object & Fields > Import Departments</b> to load departments
  5. For Reports and Dashboards to work, follow Workshop lab guide section <b>Analyze with Reports and Dashboard > Load Data</b> to load sample travel approval records.


<a href="https://githubsfdeploy.herokuapp.com">
  <img alt="Deploy to Salesforce"
       src="https://raw.githubusercontent.com/afawcett/githubsfdeploy/master/deploy.png">
</a>
