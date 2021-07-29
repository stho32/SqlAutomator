# SqlAutomator
Define Sql Queries and dependent sql actions that should be executed

- What if you had a table of sql queries for your database
- which would be executed at configurable frequencies
- and when returning rows you perform 1..n actions
- e.g. execute another sql, that uses the returned results as an input
- or execute an external program using the results as parameters
- 1 row at a time
- or maybe exporting everything into a csv and calling a program once
- define a take action if t-sql-script you can further fine tune when an action should be performed

Sql Queries and Actions can be executed within the same sql connection or not (for interdatabase transfers).

