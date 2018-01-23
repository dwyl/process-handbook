# Incoming invoices

dwyl has a simple invoicing "app" set up so freelancers and companies can invoice us quickly and easily. 

It's based on a `Google Form` which can be accessed at [invoice.dwyl.com](https://invoice.dwyl.com).

Once that `Google Form` is submitted, the fields are sent to a `Google Sheet` which automagically compiles an invoice template using `Autocrat`, and sends copies to **dwyl**, `xero`, and the *invoicer*.

## Process outline

* Get banking and contact details from invoicer and input into spreadsheet to set them up (if they aren't already)
* Add their name to the `name` question on the form (if they're not there already)
* Ask invoicer to fill in the form at [invoice.dwyl.com](https://invoice.dwyl.com)
* At this stage, `Autocrat` should take care of the rest as it's set up to run on form change
  * The output will be an email with PDF invoice from `no-reply@dwyl.com` to the invoicer, copying in `finance@dwyl.com`, and sending a copy to `Xero`  
  * If nothing happens, go to the spreadsheet and trigger it manually (instructions below)

### Setting up new invoicer

After being granted access to the *Finance (private)* folder, go to `Invoicing`, where you'll find a file called `dwyl invoicing (responses)`.

![screenshot 2018-01-16 at 11 37 23](https://user-images.githubusercontent.com/11595920/34987222-525a3f14-fab2-11e7-866b-6a1cd6adac09.png)

Go to `sheet 2` and fill in the invoicer's details there - banking, contact, etc. (screenshot).

Now go to the `Google Form` itself, `dwyl invoicing`, accessible from the same folder. 

![screenshot 2018-01-16 at 11 43 43](https://user-images.githubusercontent.com/11595920/34987291-8c3da2fc-fab2-11e7-9b13-a5de5bfe90c5.png)

Update the first question (name) with the invoicer's name **exactly as it appears in the `Contractor Name` field in the spreadsheet**. (screenshot).

Their name will now be available in the Form dropdown, and will link up to their banking/contact details in the `Sheet`. (This is why the name field in the `form` has to be identical with the name in the `sheet`.

### Amending existing invoicer details

If you're amending someone's **name**, follow the first two steps from `Setting up a new invoicer` above, and just change what's in the `Contractor Name` field. AND THEN you'll need to follow the final step above where you change their `name` in the `Google Form` to match (otherwise Autocrat won't be able to link the form submission with their invoicer details).

If you're amending any details **other than name**, you don't need to do anything extra. So e.g. if you want to give a dwyler a pay bump, just increase their day rate in `sheet 2`. The next time they submit an invoice, Autocrat will run it against the updated rate.

### Sending 

`Autocrat` is configured to send & compile automatically, and pretty instantly, IN THEORY.

For currently unknown reasons this doesn't always happen, so you may have to check the Sheet and trigger manually...

At the end of the `Google Form`, there's a note which asks the invoicer to contact finance@dwyl.com if they haven't received their invoice within an hour. So if you receive such an email, obviously go check the `dwyl invoicing (responses)` spreadsheet in case you need to trigger `autocrat` manually.

For safety, it's probably best that whoever is in charge of invoicing to check in once a week to ensure nothing has slipped through the cracks.

![screenshot 2018-01-16 at 10 10 50](https://user-images.githubusercontent.com/11595920/34987513-54a16ee0-fab3-11e7-9ced-9ca81963b827.png)

To open `autocrat`, go to the `dwyl invoicing (responses)` Sheet, hit `add-ons > autocrat > open` (screenshot). Be patient, it can take some time to load.

![screenshot 2018-01-16 at 11 58 27](https://user-images.githubusercontent.com/11595920/34987875-9a12c75c-fab4-11e7-9849-42be685d4309.png)

Press play - Autocrat will run; or hit preview to see what will happen when it runs (screenshot).

![screenshot 2018-01-16 at 10 21 28](https://user-images.githubusercontent.com/11595920/34987935-d53111c2-fab4-11e7-889f-01bd27b77d4b.png)

If you see an alert icon (screenshot), you probably don't have folder permission (or Autocrat just doesn't like you).

![screenshot 2018-01-16 at 10 26 29](https://user-images.githubusercontent.com/11595920/34988022-2294e45c-fab5-11e7-9f50-3a5ef0b4c6b2.png)

In which case, hit `edit` to enter the `Autocrat` job, keep pressing `next` until you reach where it asks you for a folder, and set it to `Invoices` (path in screenshot).

### Updating the autocrat job

An `Autocrat` job is when there's a *new* row in the `dwyl invoicing (responses)` (i.e. a form submission from the `Google Form`), and `Autocrat` creates the invoice and associated email.

If you want to change the template or the wording of the automated email, or make any other changes, just follow the steps above to open the `autocrat` job.

Then just go through the steps to find the bit you want to change - this part at least is easy :smile_cat:.

If it's not easy, however, you can get an `Autocrat` refresher from [this comment](https://github.com/dwyl/process-handbook/issues/70#issuecomment-339266181)
