# Banking Feeds

Xero includes the ability to have bank feeds which feed transactions into the
application and can be automatically updated.

Some banks however, do not provide this facility.

## Updating Santander feed into Xero

This *can* be automatically updated. Just requires a user account with permission, and can easily be done from your main Xero Dashboard, or by clicking into the Bank Account. 

## Updating Co-operative Bank feed into Xero

### 1. Get export from Co-operative Bank
1. Start by checking the Dashboard in Xero to see when the Co-op Bank feed was last
updated. This will be your `Statement balance` date:

![image](https://user-images.githubusercontent.com/4185328/46742115-45a2db00-cc9e-11e8-86de-120e7c233c01.png)

2. Log into the Co-operative Bank online banking (at the time of writing, it's
pretty shocking UI, we know :ghost:) and click into the account.
3. Limit the _range_ of transactions you see to include only the ones since the
last bank feed update (in the case above, since 27th September) until today.
4. Click on `Reports`.

![image](https://user-images.githubusercontent.com/4185328/46742164-6408d680-cc9e-11e8-9be7-610e94eb3674.png)

5. Choose the `CSV` option and Generate the report.

![image](https://user-images.githubusercontent.com/4185328/46742189-6d923e80-cc9e-11e8-9219-c09c0f88684d.png)


### 2. Updating the export
Xero will not be able to read the export just as it is so we need to update the formatting to make it compatible with Xero.

1. Open the CSV in `Numbers` (on Mac) or Excel (on Windows).
2. Delete all of the rows apart from the field titles row and the transactions rows.
  + Note that if there are a lot of transactions, you may end up with a row that
   says `Page 1 of 1` _in between_ the transaction rows
3. Manually merge (copy & paste) the `Bank Reference` and `Customer Reference` columns together so that the column you end up with contains both the client name and the invoice reference if one was given:

##### Before:
![image](https://user-images.githubusercontent.com/4185328/46742426-e8f3f000-cc9e-11e8-98cb-3b2265f35693.png)


##### After:
![image](https://user-images.githubusercontent.com/4185328/46742501-0de86300-cc9f-11e8-899e-9fa7152035a0.png)


4. Manually merge the `Credit` and `Debit` columns so that debits appear as negative values (the credits remain the same)
  + Note: All the credit figures include VAT which we pay back to HMRC but you
  don't have to worry about this now as it's dealt with separately in the VAT
  and bank reconciliation processes

##### Before:
![image](https://user-images.githubusercontent.com/4185328/46742718-86e7ba80-cc9f-11e8-96b0-ebf3da59751b.png)

##### After:
![image](https://user-images.githubusercontent.com/4185328/46742770-a1219880-cc9f-11e8-995a-46e9611f0252.png)

5. Delete _all_ columns except:
  + Date
  + Customer Reference (which now contains the information from `Bank Reference`
  as per step 3 above)
  + Credit (which now contains the information from `Debit` as per step 4 above)
6. Export your 3 column table to CSV:

![image](https://user-images.githubusercontent.com/4185328/46743240-8996df80-cca0-11e8-97f6-fea2fc1fa941.png)

### 3. Import to Xero

In Xero, go to the '3 dot' menu on the Co-operative Bank account on the dashboard and click `Import a Statement`:

![image](https://user-images.githubusercontent.com/4185328/46743404-e2667800-cca0-11e8-81ae-489fec31300d.png)

Follow the steps to upload  & import your CSV.

**NOTE:** The first couple of times you do this and then sporadically from then on, a table will appear at the bottom of the import page - **you _must_ make sure that Xero is interpreting the lines correctly**.

For example, in the screenshot below, Xero recognised that the first column was the transaction date correctly but couldn't recognise the second column:
![screen shot 2018-08-01 at 11 52 30](https://user-images.githubusercontent.com/4185328/46743677-7fc1ac00-cca1-11e8-98d8-dbd02d785a45.png)

Choose the correct column name from the drop-down menu (in this case, description of the transaction):
![screen shot 2018-08-01 at 11 52 45](https://user-images.githubusercontent.com/4185328/46743649-6e789f80-cca1-11e8-821a-9014bca0a551.png)

### Success!
![image](https://user-images.githubusercontent.com/4185328/46743845-d16a3680-cca1-11e8-9295-a71d5fb529d2.png)
