# R&D Tax Relief

## Background

> R&D reliefs support companies that work on innovative projects in science and technology. 
It can be claimed by a range of companies that seek to research or develop an advance in their field. 
It can even be claimed on unsuccessful projects.

> To get R&D relief you need to explain how a project:

> * looked for an advance in science and technology
> * had to overcome uncertainty
> * tried to overcome this uncertainty
> * couldn’t be easily worked out by a professional in the field

Put simply, if your company works on projects that meet some/all of the aspects outlined above, 
you may be able to claim Corportation Tax Relief

Source: https://www.gov.uk/guidance/corporation-tax-research-and-development-rd-relief

**DISCLAIMER: this document is written only with dwyl's business in mind. 
This is NOT financial advice: you are responsible for ensuring your submissions to HMRC are correct for your business.**

## Process

Outline: our R&D consultant sends us template spreadsheets which we fill in with the relevant R&D projects we've worked on,
along with how much staff time and freelancer costs were expended.

We then send this information along with our annual accounts and Corporation Tax computations to our consultants, and they process the claim for tax relief.

**NB: It's best to have your annual accounts ready (but not filed) before you go through the R&D process, 
so you don't have to pay your accountants to re-file the accounts with your R&D claim**

### Defining Criteria

You'll want to define the criteria for claimable projects in conjunction with your accountants / dedicated R&D consultants

dwyl's agreed criteria are: 

+ All projects that are technically challenging (this includes anything we've done in elixir or elm as these are so new)
+ Both client projects and our own projects, both open source and closed
  + Our clients can also claim for these same projects
+ Any code that we have created for our `learn-...` tutorials, but not the `README` itself
+ Both full time dwylers and freelancers
* Admin / finance / other non-coding roles count

Unless there have been significant changes to your business since your last claim, it's unlikely you'll have to redefine criteria year-to-year.

### Before you start

You will need...

* For payroll employees, you'll need to know how much the company has paid per employee in 
**Employer's National Insurance Contributions** (Employer NICs), **Pension Contributions**, and **salaries**
  * `Xero > Reports > Payroll > Payroll Activity Summary` -  then select the financial period you need (likely to be "last financial year")
  and select each employee from the dropdown
![screenshot 2019-02-05 at 14 44 54](https://user-images.githubusercontent.com/11595920/52280854-b4462b80-2954-11e9-9dcc-8629eb48388d.png)
* A spreadsheet with your **freelancer costs** for the relevant financial year (preferably filterable by person and project)
* A calendar or similar account of how many days each member of staff on payroll worked on each project
* The template spreadsheets from your consultant. Ours sent two:
  * Project details
  * Cost collection

### Project details

The template from your consultants should explain all of this as well.

In response to a query about how much detail is needed, our consultants said...

> you can get away doing detailed descriptions for the main ones with just a few bulleted advancements and uncertainties for the rest

* Make a list of all the projects from the relevant financial year, which you think qualify 
* Fill in any explanatory sections for each project
  * Project dates
  * Objectives: "overall objective of this part of the system and how it helps achieve the overall objective of the solution"
  * Technology stack / languages / frameworks
  * Technological advancements
    * How is your solution technologically more superior to other similar solutions in the market?
    * What are some of the particular functionalities the solution is capable of achieving that you find to be a unique combination that has not been attempted in the past?
    * Unique 3rd party integrations, if any
  * Technological challenges experienced
    * Performance issues
    * Browser compatibility issues
    * Platform/Mobile devices compatibility Issues
    * Integration Issues with APIs
    * Multi-formatted data issues
    * Deployment Issues
    * Security Issues
  * "Number of people involved / initial estimation of the percentage of their time spent resolving the uncertainties" 
  - it might be best to leave this for later; it's easier to produce this after the next section is complete, otherwise you'll be doing it from memory.

### Cost collection

This is the meat of the piece and can get quite fiddly; but if you've got all the info outlined above to hand, 
it should be much easier than it's been for us so far (with info spread across various spreadsheets and platforms)

Our template is split between "Staffing costs" (i.e. workers on payroll) and "Externally provided workers" (i.e. freelance workers)

* First, get down all the projects you listed out in the other spreadsheet 
  * For payroll staff, our template has one block per project, broken down by month:
![screenshot 2019-02-05 at 15 22 28](https://user-images.githubusercontent.com/11595920/52283149-e1490d00-2959-11e9-83cd-cca501b2c7b8.png)
  * For freelancers it's just a straigtforward list with the person's start and end dates, no granular breakdown of time spent
* Input payroll staff's details:
  * Name
  * Start / end date at the company (only if they fall within this financial year, i.e. if the employee left or joined in this period)
  * Gross Salary
  * Employer NICs
  * Pension contributions
  * Reimbursed travel costs
  * Bonuses
* Now go through your `Company Calendar` / whatever time-tracking system you use 
and input how much time each employee spent on each relevant project, each month. (Yes, this will take a _very_ long time)
  * Given the nature of our work, someone might be contributing work to a project that isn't captured in your usual time-tracking system
  You'll need to use your best judgment as to how much time to add on if someone was e.g. doing project management, admin, etc. that wasn't explicitly captured
  * You _can_ also go through client invoices to sense-check - but bear in mind that extra work is often done on top of what's directly charge to the client
  * It can also be useful to look through a github user/repo's commit history, to see who's put time down to that project and when
    * User: https://github.com/**{INSERT USERNAME}**?tab=overview&from=2017-06-01&to=2017-06-30
  * Finally, you should write some simple spreadsheet formulae to sum each employee's monthly totals, to check that someone's not working more days than there are in the month
    * Each month has about 21 working days, so use this as a guide
    * (If people have worked over weekends, this should be captured, but won't affect the results, as we don't pay overtime)
* Next, you'll do the same thing for freelancers (this is where that filterable spreadsheet from above comes in handy :wink:)
  * List each project and its freelance personnel 
  * Since you only need their start and end dates, just find their first and last invoice for each project
  * Now input the sum total of all of their invoices for each project 
  * Since this is a **cost** collection excercise, your freelancer invoices are an account of your costs - no sense-checking needed here! 
  
### Wrapping up

We've already mentioned sense-checking against invoices, github etc. 
Ideally you'd also spend a couple of hours with someone who's close enough to each project to tell you if staff worked on them without it being captured.

Once that's done, send your project list, cost collection sheet, and corporation tax / annual account details to your consultant and let them earn their fee.

### Checklist

* [ ] Fill in list of projects with details on why each one qualifies for R&D relief
* [ ] Fill in cost collection spreadsheet with details of staff and freelancer time/cost on each project
* [ ] Send the above to consultants along with corporation tax / annual accounts
* [ ] Await tax relief paperwork from consultants, then file with HMRC
* [ ] Receive decision from HMRC
* [ ] Check you've received £££ relief in your account
* [ ] Open issue for next year
