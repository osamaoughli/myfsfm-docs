
# Fetching Data from a Document



**Question:** We track Customer's PO Number and PO Date field in the Sales Order. To have these values fetched into Sales Invoice as well, we have inserted Custom Field in the Sales Invoice. However, when we create Sales Invoice from the Sales Order, Customer's PO details are not being fetched.


**Answer:** When data is fetched from one transaction to the another, then mapping of the data is done based on the field names. If two transactions have fields with the exact same name, then it's values are mapped.


For example, if you want Customer's PO No. and PO Date to be fetched from Sales Order to Sales Invoice, then you should ensure that Custom Fields added in the Sales Invoice has an exact same field name as in the Sales Order.


Sales Order (standard fields)


![Standard fields in Sales Order](/files/customize-fetch-data-1.png)


Sales Invoice (custom fields)


![Custom Field in Sales Invoice](/files/customize-fetch-data-2.png)


Since names for the Customer's PO related fields are same in the Sales Order and Sales Invoice, when creating Sales Invoice from the Sales Order, values in these fields are auto-fetched.


![Values fetching from Sales Order to Sales Invoice](/files/customize-fetch-data-3.png)
![Values fetching from Sales Order to Sales Invoice](/files/customize-fetching-data.gif)




