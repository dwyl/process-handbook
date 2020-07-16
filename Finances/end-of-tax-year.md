# Background

**DISCLAIMER: this guide is written with DWYL ltd in mind and is provided for information only. 
You are responsible for ensuring your submissions to HMRC & Companies House are correct for your business**

The UK tax year ends on 5th April. If you're an Employer running Payroll, you have certain obligations, including:

* Submitting your final payroll of the year to HMRC
* Updating your employee records
* Updating your payroll software
* Sending your employees a P60 form

But good news: if you use Xero or a similar accounting system, this is all done for you!

## Checklist

* [ ] Run the last payroll of the tax year a couple of weeks early. This is so you can check for any discrepancies _before_ submitting 
documents to HMRC (you can amend things afterwards, but obviously it's much trickier to do this after submission)
* [ ] Ensure all payroll payments have been [properly reconciled](https://github.com/dwyl/hq/issues/449) [link to process doc TBC]
* [ ] Now check the numbers - ensure that the total paid to employees plus the total paid to HMRC matches the amount leaving your bank account,
and that there are no random transactions in the wrong place (e.g. put reconciled to wrong account)
  * Run _gross to net_ payroll report `(reports > all reports > payroll > gross to net)`.
  Select all employees and use the custom date range and change for the tax year e.g. 06/04/17 to 5/04/18
  * Run _account transactions_ accounting report `(reports > all reports > accounting > account transactions)`.
  Select accounts 814, 825, 826, 947, 477, 479, 482
  * Run _P32_ report: `Xero > Reports > Payroll > P32 Employer Record`
  * Check that `Gross Earnings` from _Gross to Net_ matches the sum of `Direct Wages` and `Salaries` in _Account Transactions_
  * Check that the sum of `Employer pension` and `Employee pension` in _Gross to Net_ matches the `Pensions payable` amount in _Account transactions_ 
  * Check that the `Employer pension` in _Gross to Net_ matches the `Pensions Costs` in _Acount transactions_
  * Check the `Closing Liability` for `NIC payable` and `PAYE payable` in _Account Transactions_ match the figures in the last row
  of the _P32 Summary_ for the `Gross NICs` and `Income Tax (PAYE)` columns
  * Check the `PAYE total` in _Account Transactions_ matches the figures in P32 and `Gross to net`
  * Check `NIC Payable` in _Account Transactions_ and `P32` matches the sum of the NIC columns (`EE NIC` & `ER NIC`) in `Gross to net`
  * Check the `Grand Total` from the _P32 Summary_ (very bottom right) matches the sum of `PAYE total` and `NIC Payable` (from the previous two steps)
  * Check the `Net Pay` amount in _Gross to Net_ matches `Wages Payable` in _Account transactions_
  * Congratulations! You've just completed all the early checks - now you can process payroll as usual
  
### After running the year's final payroll...
* [ ] If anyone's tax codes need to change, HMRC will have sent you a formal letter explaining this - look out for form P9T/P9X. Add the new code to Xero
  * `Xero > Payroll > Employees > Select employee > Taxes`
  * Here you can see old tax codes and add new ones. 
  * If you've not received anything from HMRC, Xero will update the tax codes for you automatically (but check anyway!)
* [ ] Send P60 forms to all employees for their records: `Xero > Payroll > Select all employees > Hit "send P60"`
* [ ] We're entitled to a £3k employment allowance which Xero processes automatically - so just double-check: `Xero > Settings > Payroll Settings` and the 
Employment Allowance tickbox should be checked
* [ ] Finally, check all employee details are correct in the Xero Payroll section - director status, student loans status, home addresses
