
# Expense Claim



**Expense Claim is made when employees make expenses out of their pocket on behalf of the company.**


For example, if they take a customer out for lunch, they can make a request for reimbursement via the Expense Claim form.


To access an Expense Claim, go to:


> Human Resources > Expense Claims > Expense Claim


## 1. Prerequisites


1. [Employee](/docs/en/human-resources/employee)
2. [Department](/docs/en/human-resources/department)
3. [Chart of Accounts](/docs/en/accounts/chart-of-accounts)


## 2. How to create a Expense Claim


1. Go to: Expense Claim > New.
2. Select the Employee Name in the 'From Employee' field.
3. Select the Expense Approver.
4. Enter the Expense Date, Expense Claim Type and the Amount.
5. Additionally, you can also enter the Expense Taxes and Charges.
6. In Accounting Details, select the Company's Default Payable Account.
7. Save and Submit.


![Expense Claim](/files/expense_claim.png)


Set the Employee ID, date, the list of expenses, and corresponding taxes that are to be claimed and “Submit” the record.


![Expense Claim](/files/expense-claim-expenses.png)


Expense claim workflow



 <iframe src="https://www.youtube.com/embed/5SZHJF--ZFY?rel=0" frameborder="0" allow="autoplay; encrypted-media" allowfullscreen="">
 </iframe>

### Approving Expenses


Approver for the Expense Claim is selected by an Employee himself. Employee can choose from the list of users who are configured as *Expense Approvers* for their [Department](/docs/en/human-resources/department).


When a new Expense Claim is created, if the selected expense approver does not have access to it, the document is shared with the approver with "submit" permission.


After saving Expense Claim, Employee should [Assign document to Approver](https://docs.erpnext.com/docs/en/using-erpnext/assignment). On assignment, approving user will also receive email notification. To automate email notification, you can also setup Email Alert


Expense Claim Approver can update the “Sanctioned Amounts” against Claimed Amount of an Employee. If submitting, Approval Status should be submitted to Approved or Rejected. If Approved, then Expense Claim gets submitted. If rejected, then Expense Approver's comments can be added in the Comments section explaining why the claim was approved or rejected.


### Booking the Expense


On submission of Expense Claim, system books an expense against the expense account and the employee account
![Expense Claim](/files/expense_claim_book.png)


User can view unpaid expense claim using report "Unclaimed Expense Claims"
![Expense Claim](/files/unclaimed_expense_claims.png)


### Payment for Expense Claim


To make payment against the expense claim, user has to click on Create > Payment.


#### Expense Claim


![Create Payment](/files/expense_claim_create_payment.png)


#### Payment Entry


> Note: This amount should not be clubbed with Salary because the amount will then be taxable to the Employee.


![Expense Claim](/files/expense_claim_payment_entry.png)


Alternatively, a Payment Entry can be made for an employee and all outstanding Expense Claims will be pulled in.


> Accounting > Payment Entry > New Payment Entry


Set the Payment Type to "Pay", the Party Type to Employee, the Party to the employee being paid and the account being paid from. All outstanding expense claims will be pulled in and payments amounts can be allocated to each expense.


### Linking with Task & Project


* To Link Expense Claim with Task or Project specify the Task or the Project while making an Expense Claim


![Expense Claim - Project Link](/files/project-expense-claim-1.png)


This will update the Project cost with the Expense claim amounts


![Expense Claim - Project Link](/files/project-expense-claim-2.png)




