SFDC_requireContactRole
=======================

Apex trigger and test class that checks for number of contact roles and a primary contact role on the opportunity object
 - requires 2 custom fields on the opportunity
 - (optional) use validation rules to match sales process
 
Extension
 - add additional checkbox fields on the opp for each required contact role to ensure that all have been assigned
  - requires a few more lines added to the trigger
