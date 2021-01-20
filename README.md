# budget-tracker-3

## Objective

To track debit / credit transactions in online / offline environments and the end results on the database collection of those transactions.

## Software

a) Express
b) Mongoose

## SCREENSHOTS

## " ONLINE TRANSACTION "

## Paycheck being added

![](imageS/paycheck.png)

## Result of Paycheck Deposit

![](imageS/paycheckaddresult.png)

## MongoDB result of transaction

![](imageS/mongodbresult.png)

## " OFFLINE " TRANSACTION

Transaction below shows $100 transaction and the results
in the " terminal " window

![](imageS/offlinePurchase.png)

## Mongodb result ( no transaction retrieved)

![](imageS/offlinemongodb.png)

## Reapply Transaction with Developer Tool Confirmation

![](imageS/reapply.png)

## Mongodb results of offline reapply

![](imageS/mongodbreapply.png)

## Testing

## Online Transaction

Added Transaction , reviewed Graph , checked Developer tools for possible issues , reviewed MongoDB to see if transaction inserted .

## Offline Transaction

Set Network to " offline " , created Transaction , checked budget db through developer tools" to see if transaction was in " Pending " state . Restarted Server , checked graph to see if transaction was applied , checked developer tools to made sure their were no " pending " transactions and confirmed through mongodb that transaction had been applied .
