
# Item Valuation Setup and Transactions



In ERPNext, Item's stock valuation is updated on the creation of one of the following transaction.


1. Purchase Receipt
2. Stock Entry of type Material Receipt
3. Stock Reconciliation made for updating stock opening balance


You can select valuation method based on which item's value will be calculated. Valuation Method can be set globally for all the items from the Stock Settings.


![Download Backup](/files/item-valuation-1.png)


You can also set Valuation Method in the item master, especially when a valuation method for an item is different from the default Method as seen in the following screenshot.


![Download Backup](/files/item-valuation-2.png)


Note that once ledger entries are made for an item, this option will no longer be visible in the Item form.


[Click here to learn about the valuation methods available in the ERPNext, and how it works.](https://frappe.io/blog/erpnext-features/inventory-valuation-method-fifo-vs-moving-average)




