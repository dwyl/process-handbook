# Incoming invoices

dwyl has a simple invoicing "app" set up so freelancers and companies can invoice us quickly and easily. 

It's based on a `Google Form` which can be accessed at [invoice.dwyl.com](https://invoice.dwyl.com).

Once that form is submitted, the fields are sent to a `Google Sheet` which automagically compiles an invoice template using `Autocrat`, and sends copies to **dwyl**, `xero`, and the *invoicer*

## Process outline

* Get banking and contact details from invoicer and input into spreadsheet to set them up (if they aren't already)
* Add their name to the `name` question on the form (if they're not there already)
* Ask invoicer to fill in the form at [invoice.dwyl.com](https://invoice.dwyl.com)
* At this stage, `Autocrat` should take care of the rest as it's set up to run on form change
  * The output will be an email with PDF invoice from `no-reply@dwyl.com` to the invoicer, copying in `finance@dwyl.com`, and sending a copy to `Xero`  
  * If nothing happens, go to the spreadsheet and trigger it manually (instructions below)

### Setting up new invoicer / amending existing details

After being granted access to the *Finance (private)* folder, go to `Invoicing`, where you'll find a file called `dwyl invoicing (responses)`

![screenshot 2018-01-16 at 11 37 23](https://user-images.githubusercontent.com/11595920/34987222-525a3f14-fab2-11e7-866b-6a1cd6adac09.png)

Go to `sheet 2` and fill in the invoicer's details there - banking, contact, etc. (screenshot)

Now go to the form itself, `dwyl invoicing`, accessible from the same folder. 

![screenshot 2018-01-16 at 11 43 43](https://user-images.githubusercontent.com/11595920/34987291-8c3da2fc-fab2-11e7-9b13-a5de5bfe90c5.png)

Update the first question (name) with the invoicer's name **exactly as it appears in the `Contractor Name` field in the spreadsheet**. (screenshot)

Their name will now be available in the Form dropdown, and will link up to their banking/contact details in the Sheet

### Sending 

`Autocrat` is configured to send & compile automatically, and pretty instantly, IN THEORY.

For currently unknown reasons this doesn't always happen, so you may have to check the Sheet and trigger manually

![screenshot 2018-01-16 at 10 10 50](https://user-images.githubusercontent.com/11595920/34987513-54a16ee0-fab3-11e7-9ced-9ca81963b827.png)

Go to the `dwyl invoicing (responses)` Sheet, hit `add-ons > autocrat > open` (screenshot). Be patient, it can take some time to load.

![screenshot 2018-01-16 at 11 58 27](https://user-images.githubusercontent.com/11595920/34987875-9a12c75c-fab4-11e7-9849-42be685d4309.png)

Press play - Autocrat will run; or hit preview to see what will happen when it runs (screenshot)

![screenshot 2018-01-16 at 10 21 28](https://user-images.githubusercontent.com/11595920/34987935-d53111c2-fab4-11e7-889f-01bd27b77d4b.png)

If you see an alert icon (screenshot), you probably don't have folder permission (or Autocrat just doesn't like you).

![screenshot 2018-01-16 at 10 26 29](https://user-images.githubusercontent.com/11595920/34988022-2294e45c-fab5-11e7-9f50-3a5ef0b4c6b2.png)

In which case, hit `edit` to enter the `Autocrat` job, keep pressing `next` until you reach where it asks you for a folder, and set it to `Invoices` (path in screenshot)

### Updating the autocrat job

If you want to change the template or the wording of the automated email, or make any other changes, just follow the steps above to open the `autocrat` job

Then just go through the steps to find the bit you want to change - this part at least is easy :smile_cat:
