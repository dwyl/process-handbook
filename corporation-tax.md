# Corporation Tax

Generally we pay accountants to file our annual company accounts and calculate the Corporation Tax for us. If you have anything even slightly complicated, anything from fixed assets to losses brought forward from another period to R&D tax relief and beyond, _it might well make sense for your business to hire an accountant_: a couple of hundred pounds is very well worth it for **peace of mind**!

(That said, if you're short of cash or just like being in total control of your accounts, there's nothing to stop you doing the whole thing yourself.)

With FocusHub, however, they are simple enough for us to file ourselves - which is why it's worth capturing the process here.

## DISCLAIMER

**This process is for filing your company tax return with UK HMRC online. It is correct _only_ at the time of writing (November 2018). This is not legal or financial advice. You are entirely responsible for your HMRC filings.**

This documentation is written *entirely* with FocusHub (a **micro-entity** company) in mind. **Use it only as a guide**, and make sure you are reading every question fully, and answering truthfully and accurately for *your* business.

Please also note that your accounting software might use different terminology (e.g. `sales` vs `revenue` vs `turnover`)

## Before you start

* Identify the period you're filing for
* Filter whatever accounting platform (Xero, FreeAgent) we're using to only include the period you're filing for
* Ensure all transactions during that period (money in or out) have been reconciled, categorised to the correct account (e.g. office supplies, travel), and with the right VAT rate
  * In Xero this is easily done by looking at `account transactions` - the column on the right tells you whether something is reconciled or not
  * In FreeAgent it's slightly trickier - you need to make sure to check each transaction category in the dropdown (screenshot) as FreeAgent has a habit of "hiding" things
![screenshot 2018-10-16 at 15 44 12](https://user-images.githubusercontent.com/11595920/47025046-bc3a4f80-d15a-11e8-9155-41a17f58e272.png)
* Make sure you have all the info you need in advance - HMRC logged me out three times while I was looking for something - very frustrating
  * P&L / Balance sheet reports
  * Company Reg no (on Companies House page)
  * Authentication code (sent to you by post from Companies House)

* PLEASE NOTE: **"Figures should be rounded to whole numbers. Round down income and round up spending."** (This pretty essential information is displayed once at the start of the process, and never again.)

* PLEASE BE AWARE: the HMRC system is fiddly and annoying. You are likely to make mistakes like putting the right figure in the wrong box. This is fine - you can go back and edit them as long as you've haven't submitted the final accounts (to be clear, even if you've "approved" the accounts, you can still edit them and approve them again). Just don't be surprised if you try to go back to page 15 but it instead takes you back to page 5 and makes you click through 10 pages to get to where you want to be - this happens a lot.
  * Basically, edit as much as you like, but only `submit` when you're 100% sure

## HMRC

(This process is written with FocusHub in mind. Please see disclaimer above and make sure you're answering correctly for your own business)

* Log in to the relevant HMRC account. The details are in the usual spreadsheet.
  * NB: 2FA is enabled; check with @iteles for account holders 
* Hit `Complete corporation tax return` and press `continue` until you see a green button that says `Create New Submission`
* "No - I don't want to amend an existing Company Tax Return"
* "No - my accounts haven't been audited"
* "Private limited company"
* "No - my company is not one of these" (insurance, investment, credit, property)
* "No - my company is not part of a group"
* "Yes - my company is registered in the UK"
* "No - I don't need to report these" (currency, adjustments, instruments, restructuring)
* "No - I don't need to report any of these things" (shares stuff)
* "No - I don't need to report investment assets" 
* "No - I don't need to report contingent assets"
* "No - I don't need to report these"
* "No - I don't need to claim capital allowances"
* `Who do you want to file to?` - "Companies House and HMRC"
* Company reg number is on Companies House, and authentication code is in the usual spreadsheet, but next to Companies House not HMRC
* Continue and check/confirm the filing period dates
* "No - my company wasn't dormant"
* Answers to "about your business" should be obvious
* `What type of accounts have you prepared?` - "Microentity Accounts"
* Now you're ready to... *begin* the process...

## Return

### Profit & Loss

Here comes the Maths bit - concentrate...

Be aware that HMRC only accepts £ pounds not pence - always round down income and round up spending.

Start with running Profit & Loss reports fixed to the dates of the current filing period AND the last filing period. (`Reports > P&L`)

* "No - I haven't prepared a directors' report"
* Turnover - `Also called sales, revenue or income. The total amount this period from selling goods or services, not including VAT.`
  * On FreeAgent this is just called `Turnover` at the top of the report 
* Other income - `Any other income not included in turnover.`
  * For Focus Hub this only includes a couple of minimal interest payments
* Cost of raw materials and consumables - `The costs of buying or producing the goods or services sold, for example, materials used to make products.`
  * n/a
* Staff costs - `Salaries or wages paid by the company for work done this period, including employers' National Insurance and the cost of a payroll service.`
  * For FocusHub, n/a
* Depreciation - `The amount the company wrote off assets this period to reflect the fall in their value over the period.`
  * For FocusHub, n/a
* Other charges - `Any other spending for the period, not including fixed (physical) assets.`
  * For FocusHub, this is nought, which is common for "services" companies
* Tax on Profit - `Work out Corporation Tax due on company profits using the latest rates. Company profits = turnover plus other income, minus all outgoings.`
  * This is nought if we've made a loss, otherwise profits are taxed at 19%
* Profit (or loss) - `Calculation: Turnover plus other income, minus all outgoings, minus tax.`
  * This is automatically calculated from what you've entered

----

* File profit and loss to Companies House? `If you choose to file your profit and loss account to Companies House, it will be publicly available in the official government register of UK companies.`
  * Select "No" - as a microentity company, there's no need for us to submit this information. This is referred to as "filleting" our accounts and seems to be the preferred process for small companies, as long as all shareholders have agreed


### Balance sheet

(Again, the answers here are based on FocusHub)

* Called up share capital not paid - `The total amount owed to your company by investors who haven't paid in full for their shares in your business.`
  * Mercifully, nought
* Total fixed assets - `The total value of the company's physical (for example, machinery, office equipment or buildings) and non-physical (for example, patents, trademarks, licences, goodwill) assets, taking account of depreciation.`
  * Again, mercifully nought
* Total current assets - `Value of any cash, or assets that can be converted into cash within one year, held by the company at the end of the period. For example, unsold goods. Include amounts owed (debtors) here.`
  * This is called "Current Assets" in FreeAgent
* Prepayments and accrued income - `Prepayments: The amount you paid for goods and services that you hadn't received at the end of the period, for example, advance rent payments. Accrued income: The amount you've earned (excluding from debtors) but haven't received, for example, interest earned on a bond to be paid in the future.`
  * As above
* Creditors - amounts falling due within one year - `Debts you expect to settle within a year, for example, unpaid supplier invoices, bank loans or overdrafts.`
  * As above
* Creditors - amounts falling due within one year - `Debts you expect to settle after more than one year, for example, bank loans with instalments due after more than a year.`
  * This is `Current liabilities` in FreeAgent
* Provision for liabilities - `An amount set aside to cover future costs, for example, for tax, costs of restructuring or providing pensions.`
  * Nought
* Accruals and deferred income - `Accruals: Expenses that are not yet paid for, for example, electricity already used but to be paid in the future. Deferred income: The amount you were paid for goods and services that you hadn't provided at the end of the period, for example, a client deposit paid before work starts.`
  * Nought
* Capital and reserves - `The current amount the owners have invested in the company, or the amount owed to the owner, plus any surplus funds. This must match the 'total net assets or liabilities' figure.`
  * Just enter the same figures as the boxes above - they have to match

----

* Now just keep hitting `continue` and ignore request for footnotes etc. until you get to the "Approve Accounts" section, then approve the accounts and you can start on the `Computations` section

----

### Computations

NB: there are *loads* of fields which I'm not going to cover because they aren't relevant to the FocusHub business and the accounts we have filed (e.g.  Donations, Vehicle expenses).

* Trading account details
  * Turnover/sales - prepopulated
  * Cost of sales - `Cost of sales is the direct cost attributable to the production of goods or sale of services supplied by your company. This value includes the cost of materials and direct labour costs, but excludes distribution and sales force costs.`
    * Called "cost of sales" in FreeAgent
  * Gross Profit/loss - auto-calculated
* Property costs
  * Heating, Light, Power - you have to add this up manually from the `Office Costs` report (click through from P&L)
  * Maintenance - weekly cleaner's costs (again, add this up from `Office Costs`)
  * Rent & Rates - add up rent and rates displayed on P&L report
* General administrative expenses
  * Bad Debts - displayed on P&L report 
  * Bank, Credit card charges - displayed on P&L report
  * Insurance - displayed on P&L report
* Income from property - nought
* Trading losses - "yes" for *this period only*
* Charitable donations, grassroot sports donations - since we've not made any profit, you can just say "no" to all of these.
* Close company - yes, FH is a close company
* Loans - no loans made at all, just hit No
* Tax avoidance - we're not required to do this
* About your return
  * Are you owed a repayment for this period? - No
  * Are you owed a repayment for an earlier period? - No
  * Are any of your figures estimated? - No
  * Did you receive any franked investment income? - No
* Tax already paid - nought
* Repayments - if there are repayments to be had, decide where you'd like them to go. Even if you know you're not getting repayments, you still have to go through this part. So just pick whichever you like; then enter our bank details in the next section

----

* At this stage, it's just a matter of checking over all of your figures in the various `summary` sections and completing declarations like "The board has approved these accounts"

## DISCLAIMER II

**Again, this process is for filing your company tax return with UK HMRC online. It is correct _only_ at the time of writing (November 2018). This is not legal or financial advice. You are entirely responsible for your HMRC filings.**

