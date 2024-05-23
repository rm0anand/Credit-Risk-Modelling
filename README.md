# Credit-Risk-Modelling
## Problem Statemnt:
We have customer data and we are trying to predict whether or not to give the loan.
### For banks ->
* Asset: Loan Product(Trade Line - TL)
  1. Housing Loan
  2. Personal Loan
  3. Vehicle Loan
  4. group Loan
  5. Education Loan
  6. Credit Card

* Liability
  1. Current Account
  2. Savings Account(Both together known as CASA)
  3. Fixed Deposit
  4. Recurring Deposit(Both together Known as TD, Term deposit)

### Terminologies
1. Disbursed Amount (DA):
   principle or Loan Amount given to customer
2. Outstanding Principl(OSP):
   Amount left to be paid from principle
3. Amortization
4. Days past due(DPD): Amount of days someone defaulted on paying EMI(Should ideally be zero ofcourse)
5. Portfolio at risk (PAR): OSP when DPD>0
6. Non Performing Asset (NPA): Loan account when DPD > 90 days

### Credit Risk Types in Banking
* DPD(Zero) : Non Delinquint Account (not defaulted)
* DPD(1 to 30) : SMA1 (Standard Monitoring Account)
* DDP(31 to 60) : SMA2 (Standard Monitoring Account)
* DPD(61 to 90) : SMA3 (Standard Monitoring Account)
* DPD(91 to 180) : NPA (Non Performing Asset)
* DPD(>180) : Written off (Loan which has not any accountability)
---
Loans are normally written off to improve the loan portfolio of bank
which will lead to better market sentiments

### NPA
* GNPA (Gross NPA): (3-5%)=> OSP default
* NNPA (Net NPA): (0.01 to 0.06)=> after subtracting provisioning amount
