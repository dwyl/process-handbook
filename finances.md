# Finances

# TOC

* [What](#what)
* [Why](#why)
* [How](#how)
* [Payroll](#payroll)
* [Bookkeeping](#bookkeeping)
* [Expenses](#expenses)
* [dwyler Invoicing](#dwyler-invoicing)
* [Refunds, reversals, cancellations, etc.](#refunds-reversals-cancellations-etc)
* [Grants & Tax Credits](#grants--tax-credits)
* [Corporation Tax Return](#corporation-tax-return)
* [Budgeting](#budgeting)
* [Forecasting](#forecasting)
* [VAT Return](#vat-return)

# What?

A document that summarises our current financial processes and systems.

# Why?

So that we have a record of our processes in case someone else other than the person who normally carries them out needs to do them.

# How?

By creating and writing this document and including it as part of our process handbook.


# Payroll

Payroll is currently processed on the last business day of the month, follow these steps to post a payrun:

1. Log in to Xero, click Payroll, click Pay Runs

2. The new payrun will be automatically selected under 'New Pay Run' - click Process Pay Run

3. Post the new pay run to Xero, you'll receive a message, "*Pay run successfully processed. Payroll expense journal has been posted automatically and now includes an automatic entry for any Employment Allowance, where applicable.*"

4. Log in to the Santander bank account, go to `Multiple payments`, and select the existing `Payroll` template

4a. Check there are sufficient funds in the Santander account for the whole pay run (the `total cost` is at the top of the pay run screen in Xero)

5. Add payments of the net income amount (amount after tax) to the respective individuals with the reference `"DWYL SALARY" + MONTH` (**NB**: references from the previous payroll will be autofilled so make sure to check this)

5a. Add a payment to HMRC CUMBERNAULD, where the payment
reference is **Accounts Office Reference Number** + YY/**YY** + **MM** (17 characters),
where YY/YY is the tax year and MM is the tax month, e.g. YY/YY = 17/18 and MM = 01, so that *March 2018* = **1218** and *April 2018* = **0119**  

**The tax year starts in April, so April is the first month, i.e. April = 01**.  
+ To find the correct amount to pay, go to Payroll > Taxes & Filings - you'll be
able to see here what the amount due is for the latest payrun
  + For reference, the payment should equal the total of the following from the
   relevant payrun in Xero: Income tax, Student Loan deductions, Employee National
   Insurance Contribution (NIC), Employer NIC.  
  + **NOTE:** We have an [employment allowance of £3,000 _annually_](https://www.gov.uk/claim-employment-allowance). This means that
  starting in April of _every_ year, we do not have to pay Employ***er*** NIC
  until we get to that £3,000 sum. Once our employer NIC reaches £3,000, we need
  to start paying it again (but Xero will work this out for you and factor it into
  the Amount Due).

For reference, each time a pay run is posted, Xero will automatically report to
HMRC with a [Full Payment Submission (FPS)](https://www.gov.uk/running-payroll/reporting-to-hmrc)
using the PAYE Real Time Information (RTI) service.

6. Check all the figures against the Xero pay run amounts and ensure they match before making submitting the `multiple payment` (for which you'll only need one OTP, rather than seven :smiley:)

7. In the relevant pay run in Xero, click Options > Email Payslips to email
everyone a copy of their payslip

Please note: HMRC don't confirm the submission of the FPS until the 12th of the month - so don't be surprised when you get an email out of the blue saying that the submission has just been accepted

### Holidays & Leave

All employees have Xero logins so they can request holidays and see their remaining leave entitlement.

Xero is very fiddly with holidays so you should always double-check a pay run which includes any holidays. Once a holiday has been approved and included in a `pay run`, it can't be amended.

Because until 2018, holidays weren't tracked on Xero (CharlieHR), people's 2017 balance had to be added to their 2018 allowance manually as an `opening balance` (this will be written up separately as part of the `on-boarding process`). 

Holidays that fall within an employee's annual allowance can be booked, approved, and included in a pay run automatically.

I've added an `unpaid leave` category for holidays that exceed an employee's annual allowance - whoever approves the holiday should change the `holiday type` to "Unpaid leave" after it's approved and **before** it's included in a `pay run`. 

# Bookkeeping

Bookkeeping is the activity or occupation of keeping records of the financial affairs of a business. Our bookkeeping is kept up to date in Xero, the majority of it has been done by our accountants at iHorizon. When working with the accountants you will need to provide information about transactions in order to assist in reconciliations. A reconciliation is when a bank transaction is matched to a corresponding bill or invoice or marked and categorised appropriately according to the accounts. If not done by accountants., reconciliations can be done by a member of the team. Xero has many guides that explain how this is done: https://help.xero.com/uk/BankAccounts_Details_Reconciliation

# Expenses

The expenses policy can be found here:
https://docs.google.com/document/d/1SeXnzTD4P-Ley-RfcEpM4X5aYgjB8SN9mwywtXMPi-o/edit. Expenses are captured in Xero according to the policy document.

## Foreign currency expenses

The reasons for this ludicrous process are explained [here](https://github.com/dwyl/hq/issues/430#issuecomment-376168913). 

In short, Xero doesn't accommodate foreign currency expenses so we have to put them through as `bills`

* Before you start, **arrange all your receipts by date** (because Xero does currency conversions based on the date)
* Yes, you guessed it, this means you need to **create one bill per date**
  * Though you can get away without doing this when it won't make too much of a difference, like when you're putting in loads of `dwylsummer` receipts for small amounts from the same fortnight 
* Using your phone's camera or the Xero app, take a photo of each receipt and name it according to the following convention:
  * `{date}-{amount}-{description}-{client}`
  * `account` will be e.g. `Braga` or `dwyl-summer` or `Thomas Cook`
  * Date is important (see above)
  * Description should be minimal - e.g. "food" 
* Just upload the files to the `file library`, rather than attaching them to an expense claim
![screenshot 2018-03-26 at 14 25 02](https://user-images.githubusercontent.com/11595920/37908967-8c026036-3101-11e8-91e7-e53b34e3c2bf.png)
* Open a new bill
  * Set the payee (the `from` field)
  * Set the currency
  * Set the date
  * Set the reference as `{dwyler name}`-exp-`{YYMMDD}`
* Now, because of your diligence in naming the receipt files, you can add them all to the bill and fill in the `amount`, the `description`, and the `client` from the filename rather than having to inspect each individual file (_very_ time-consuming in Xero)
* All done right? :laughing: Wrong. Xero doesn't display foreign currency bills converted to our base currency, so...
![screenshot 2018-05-08 at 14 58 18](https://user-images.githubusercontent.com/11595920/39762671-29933148-52d3-11e8-82e9-43da23267ca3.png)
  * If it's just one bill, you can hover over the currency in Euro or Dollars and see the converted amount (screenshot above)
  * If it's multiple bills and you don't want to add them all up manually, you need to go to the `payee`'s `contact` page and click on `View recent bills report` at the top of the page, and the `GBP` amount is in that report
* All these steps reproduce the functionality of an expense claim, so now that you have the total amount to be paid, you can just pay it and reconcile it as usual

# dwyler Invoicing

`dwylers` submit invoices at (https://invoice.dwyl.com); this saves the details in the invoicing spreadsheet (search `Invoicing Responses` in Drive) and generates a PDF, which is saved in the `dwyl drive` and, more importantly, is sent to our bookkeeping software's files inbox. (The process is outlined [here](https://github.com/dwyl/process-handbook/blob/master/incoming-invoices.md)

Every week, we do a `Finance day`, so the following needs to be done (ideally before 5pm so payments go through on the same day)

* Company Director to approve latest invoices in the invoicing spreadsheet
* Go to Xero inbox and create bills from all `dwyler` invoices, and approve them all
* Go to the `awaiting payment` section (Accounts > Purchases > Awaiting Payment tab)
* Select the bills you want to pay and click the `batch payments` button
* (Currently we're unable to export the batch and import into our online banking system, but will update if this is sorted) (https://github.com/dwyl/hq/issues/399)
* **Manually** add up how much each `dwyler` gets *in total* (as in the next steps there's only one line per person, not per bill)
* Go to our online banking system, log in, go to `Multiple payments`, and create a new payment
* Add the `dwylers` who need paying
* Input each dwyler's total (the two unmarked input boxes are `pounds` and `pence`), and for the reference put in the number of each invoice (so the ref is of the format `DWYL123, DWYL124, DWYL125`)
* Check that the total for the `multiple payment` is the same as the total for the `batch payment` in Xero
* Pay using the online banking system in one go
* Get in the habit of refreshing the bank feed in Xero then reconciling the payment immediately if possible
* Go back to the invoicing spreadsheet and mark the invoices as `paid`
* Send a courtesy note to people you've paid informing them that they've been paid

### Xero notes
* To add a new `pay item` (e.g. if someone goes onto a new day rate), go to `Accounts > Inventory` and you'll be able to add/edit items there. Add day rates in the format `00£££ - £££ GBP Day Rate` (e.g. `00150 - 150 GBP Day Rate`)

# Refunds, reversals, cancellations etc.

We've created an account called `999 - Reversed/Cancelled Transactions`.

This is ***ONLY*** for when £X has gone in and £X has gone out (or vice versa :wink:) - the balance of the account should ***ALWAYS*** be `0`.

Items should therefore only *be coded as 999 in pairs* - so they **immediately** cancel each other out.

**NB**: you shouldn't be adding *ad hoc* transactions and coding them as `999` - it's only when there's a `bank feed item` with the money going in and a `bank feed item` with the money going out.

Do not use code `999` for any other reason than this. 

# Grants & Tax Credits

We have applied for the ZEN Grants Scheme for Cycling. This is a scheme that grants businesses up to £2k towards promoting sustainable travel.

We are also currently looking into partnering with an organisation to claim R&D tax credits. This is still being looked into, possible partners to deliver this include Leyton, ihorizon and GrantTree.

# Corporation Tax Return

Every year the company must file a CT600 corporation tax return. These instructions should be updated when we file the 16/17 accounts. Previous returns can be found here:
https://drive.google.com/drive/folders/0B0XeQ2t5WSK2eFVVWkR5R3dWQ1E

# Budgeting

We have yet to set annual / monthly budgets for activities (e.g. https://github.com/dwyl/hq/issues/331). Budgeting is currently decided on an ad hoc basis.

# Forecasting

We have yet to develop sophisticated forecasting tools; to do our current forecasting we are using Xero and management accounts.

# VAT return

We are VAT-registered so we need to submit a quarterly VAT return, and pay/reclaim VAT due. Fortunately Xero makes this **very easy**, as long as we've been diligent in storing invoices and receipts.

* Our VAT periods are Nov-Jan, Feb-Apr (also year-end), May-Jul, Aug-Oct
* VAT Return must be submitted **within one month and one week of the period end**
* To prepare to run the report in Xero...
  * Ensure you've reconciled all account transactions (including expenses) within the relevant period (or _at the very least_, make sure to do the purchases with VAT on them)
  * (Let's assume you've been very diligent and always inputted invoices with the correct VAT amount)
  * Ensure VAT receipts/invoices have been uploaded to Xero where possible - if the VAT man comes knocking, we'll need them 
  * If there are any charges from before the VAT period, that's fine, they can still be submitted - just reconcile them as usual
  * (And don't worry about `outgoing invoices` - they will all have VAT included correctly)
* Now you can run a dummy report and sense-check it:
  * Reports > VAT Return > `select correct quarter` > `click VAT Audit Report` - this is a breakdown of all transactions in the quarter
  * If you like you can export the report to `Google Sheets`, but if you work within Xero, you can click through from a line in the report to the transaction in Xero, which is a great time-saver
  * There's no real process for sense-checking - just scroll through and make sure the transactions under each category seem like they belong there. e.g. 
    * `412 - contractors` should usually be `Zero-rated` or `No VAT`; 
    * International purchases, domain names, SaaS charges - tend to be `Reverse charge`
    * "Stuff" bought in the UK (everything from food to hoodies to stationery) tends to be 20% VAT
    * Services paid for in the UK tend to be 20% VAT
* Now you can submit the return through Xero - just hit `File VAT return` on the VAT Return page. You'll need the `Gov Gateway` account details
* And finally, you need to pay HMRC
  * Bank details are already stored in our Santander account, but can be found [here](https://www.gov.uk/pay-vat/bank-details)
  * Xero will helpfully tell you how much we owe (#5 on the VAT Return report page, in bold)
  * Pay it with our `VAT Registration Number` as the reference (search through old payments if you need to find it, it's the first nine numbers from previous payments) 
