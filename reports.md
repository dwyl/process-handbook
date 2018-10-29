# Useful financial reports and how to run them

Xero has loads of helpful reports that work pretty much out of the box.

These are some we've found useful 

* [Finding old rates](#finding-old-rates)
* [Payroll Breakdown Report](#payroll-breakdown-report)
* [Pension Contributions Report](#pension-contributions-report)

## Finding old rates

It's often useful to check what freelancers' rates have been in the past, to make sure we're not over/under-charging for their time. This is especially relevant for e.g. Designers who might work on a project at the start and then not again until much further into the project

### If their role is tracked

We've set up a number of "sales items" which are tracked - Roles like Designer, Architect, Scrum Master. If their role is one of these:

* Go to Xero > Reports > Sales > Receivable Invoice Detail
* Fix the date range you need
* Open the Custom settings
* At the bottom - Filters - add a filter for `Item Code` and set it to the relevant role
  * If you want to limit this to a specific client, you can also put a filter on for that
* Voila - all the charges put down to that Role will be displayed 

### If their roles isn't tracked

* Go to Xero > Reports > Sales > Customer Invoice Report
* Fix the date range you need
* Select Sort By Contact
* Now you'll have to scroll down until you find the client you're interested in
* Once you've found it I'm afraid you're just going to have to look through each invoice manually to find the info you need.

## Payroll breakdown report

In order to fill in staff details on the R&D tax credits spreadsheet, you need a breakdown of how much was paid *per employee* in `Employer's National Insurance`.

* Go to Xero > Reports > Payroll > Payroll Activity Summary
  * (The Payroll Activity *Detail* report might also be useful if you need a monthly breakdown)
* Under `Employees` select "Individual"
* Under date range select your required date range (likely to be last financial year)
* Hit update and you've got totals for
  * Earnings
  * Employee Tax
  * Net Pay
  * Employer Tax
* Repeat for each employee

## Pension contributions report

In order to fill in staff details on the R&D tax credits spreadsheet, you need a breakdown of how much was paid *per employee* in `Pension contributions`.

* Go to Xero > Reports > Payroll > Pension Contribution Report
* Under `Employees` select "Individual"
* Under date range select your required date range (likely to be last financial year)
* Hit update
* Repeat for each employee
