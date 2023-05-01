Download Link: https://assignmentchef.com/product/solved-assignment-8-solved
<br>
–Write one statement in the given space beneath each problem description–to answer the query.

–Partial credits is possible.

–Each clause of SELECT, FROM, WHERE, and ORDER BY is expected to be coded–on its own line and use proper indentation on each line to make your–code more readable for grading.

–Do not include statements other than the one for grading.

–Do not change the file name and its extension.use AP;

/*1. For items in InvoiceLineItems table whose AccountNo is an even number like150 or 574, use a CASE function to display their AccountNo,InvoiceLineItemDescription, and DescriptionLength. Depending on the totalnumber of characters of the InvoiceLineItemDescription, each DescriptionLengthshows one of the following three strings:

‘Shorter than 10 characters’, or‘Between 10 and 19 characters’, or’20 or more characters’

Also sort your output by AccountNo.

Hint: Use one of the operators listed on p.97 to determine if a number is an evenor odd number.

Here is a sample output of first few lines:

AccountNo InvoiceLineItemDescription DescriptionLength——— ————————– —————————–150 Supplies Shorter than 10 characters160 MVS Online Library Between 10 and 19 characters160 MSDN Shorter than 10 characters160 Quarterly Maintenance 20 or more characters170 Network wiring Between 10 and 19 characters400 CICS Desk Reference Between 10 and 19 characters………*//*2. Display InvoiceLineItemDescription such that the one with thelongest first word is printed at top and no duplicate rows.To verify your output, display the length of the first word ofInvoiceLineItemDescription in the second column as FirstWordLength.

Hint: use string functions discussed in lecture.

Here is a sample output of first few lines:

InvoiceLineItemDescription FirstWordLength————————– ——————Propane-forklift 16International pkg. 13International shipment 13Publishers Marketing 10DiCicco’s 9Quarterly Maintenance 9Telephone (Line 1) 9…..…*/

/*3. The manager wants to have a report of detail information of all invoice line itemswith the desired column title shown below. She wants the items to be listed based onthe AccountNo (a-&gt;z) and item with the highest amount within each account is printedfirst (see sample output below). In case of same amount value, items should be printedby their InvoiceID in ascending order.

Finally, all items should be continuously and uniquely ranked from 1 within each account.

—————————————————————————————-Item Rank Account No Item Amount Invoice ID Item Description Invoice Sequence—————————————————————————————-…..

1 570 75.60 12 Kinko’s 22 570 58.40 12 Office Max 33 570 41.80 74 Coffee 11 572 2433.00 56 Card deck 12 572 1575.00 47 Catalog ad 13 572 600.00 95 Books for research 14 572 579.42 98 Catalog ad 15 572 9.95 16 Monthly access fee 16 572 9.95 23 Monthly access fee 11 574 856.92 15 Property Taxes 11 580 50.00 12 DiCicco’s 11 582 503.20 105 Bronco lease 11 589 7125.34 31 Web site design 1…..…*/

—————END—————