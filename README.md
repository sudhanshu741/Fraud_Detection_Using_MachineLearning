# Fraud_Detection_Using_Machine_Learning
This project aims to develop a robust machine learning model predicting fraudulent transactions for a financial company and use insights from the model to develop actionable plan .

Given features in our fraud dataset:

> **step** - _maps a unit of time in the real world. In this case 1 step is 1 hour of time. Total steps 744 (30 days simulation).
_
> **type** - _CASH-IN, CASH-OUT, DEBIT, PAYMENT and TRANSFER._

> **amount** - _amount of the transaction in local currency._

> **nameOrig** - _customer who started the transaction_

> **oldbalanceOrg** - _initial balance before the transaction_

> **newbalanceOrig** - _new balance after the transaction_

> **nameDest** - _customer who is the recipient of the transaction_

> **oldbalanceDest** - _initial balance recipient before the transaction. Note that there is not information for customers that start with M (Merchants).
_
> **newbalanceDest** - _new balance recipient after the transaction. Note that there is not information for customers that start with M (Merchants)._

> **isFraud** - _This is the transactions made by the fraudulent agents inside the simulation. In this specific dataset the fraudulent behavior of the agents aims to profit by taking control or customers accounts and try to empty the funds by transferring to another account and then cashing out of the system._

> **isFlaggedFraud** -_ The business model aims to control massive transfers from one account to another and flags illegal attempts. An illegal attempt in this dataset is an attempt to transfer more than 200.000 in a single transaction._
