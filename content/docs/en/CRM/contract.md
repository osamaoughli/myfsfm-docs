
# Contract



**A contract is a legally binding agreement between a Supplier and a Customer over the sale or products or services.**


A contract is legally enforceable because it meets the requirements and approval of the law. An agreement typically involves the exchange of goods, services, money, or promises of any of those.


To access the Contract list, go to:



> 
> Home > Sales Pipeline > Contract
> 
> 
> 


## 1. How to Create a Contract


1. Go to the Contract list and click on New.
2. Choose the Customer.
3. Enter the Contract Terms. A template can also be created for easily fetching the terms.
4. Save.
![Contract](/files/contract.png)


**Party User**: The employee from your Company who is in contact with the Customer.


### 1.1 Statuses


* **Unsigned**: The Contract has not yet been signed by the Customer.
* **Active**: The Contract has been signed and is active under the Contract Period.
* **Inactive**: The Contract is out of the Contract Period and not valid anymore.


## 2. Features


### 2.1 Contract Period


The Start and End date within which the Contract is valid.


### 2.2 Signee Details


This section will appear when the 'Signed' checkbox is ticked to indicate that the Customer has signed and accepted the Contract.


![Contract Signee](/files/contract-signee.png)


* **Signee**: Enter the name of the person that has signed the Contract.
* **Signed On**: The date on which the Contract was signed.


### 2.3 Contract Details


Enter the terms of the Contract in the Contract Terms field. You can create a Contract Template and the template can be selected to fetch the Contract Terms.


### 2.4 Fulfilment Details


If the Contract requires some fulfilment from the Supplier's (your) end, their details can be recorded in the Fulfilment Terms table.


![Contract Fulfilment](/files/contract-fulfilment.png)


* **Requirement**: Enter a requirement that needs to be fulfiled. For example, 'installation'.
* **Notes**: Any notes about the requirement can be entered here.


### 2.5 Contract Template


A contract template is a standardized outline of a contract without the specifics involved. You can create a new template by going to:



> 
> Home > CRM > Contract Template
> 
> 
> 


You can create templates by using Jinja. Eg:



```
The parties enter into this contract on &lcub;&lcub; start_date }}.

```

When you create a new contract using this template, the `&lcub;&lcub; start_date }}` is replaced by the date entered into the field of the same name.


![Contract Template](/files/contract-template-jinja.gif)


### 2.6 References


If the Contract can be linked to a transaction in ERPNext. Select the transaction type and the specific transaction. The documents that can be linked are:


* Quotation
* Project
* Sales Order
* Purchase Order
* Sales Invoice
* Purchase Invoice


![Contract References](/files/contract-reference.png)


### 3. Related Topics


1. [Quotation](/docs/en/selling/quotation)
2. [Purchase Order](/docs/en/buying/purchase-order)
3. [Sales Order](/docs/en/selling/sales-order)
4. [Purchase Receipt](/docs/en/stock/purchase-receipt)
5. [Delivery Note](/docs/en/stock/delivery-note)
6. [Sales Invoice](/docs/en/accounts/sales-invoice)
7. [Purchase Invoice](/docs/en/accounts/purchase-invoice)




