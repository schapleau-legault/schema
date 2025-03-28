# Data mapping Order

https://leanx.eu/en/sap/table/vbrk.html

## schema.org to SAP
|Source field | Target field | Transformation | Reference value mapping | 
|-------------|--------------|----------------|-------------------------|
| _SYSTEM_ID  | "SAP" |
|	_SYSTEM_TABLE_ID  | "VBRK" |
|	_SYSTEM_RECORD_ID | VBRK.Id |
|	_SYSTEM_CREATEDDATE  | VBRK.ERSDA (MARA.DATE_DE_CREATION)|
|	_SYSTEM_MODIFIEDDATE  | VBRK.LAEDA (MARA.DATE_DE_DERNIER_MODIFICATION)|
|@type | "Order" |
|sameAs | VBRK.Id |
| billingAddress | xx | 
| confirmationNumber | xx | 
| customer | xx | 
| discount | xx |
| discountCode | 
| discountCurrency | xx | 
| orderDate |  VBRK.CreationTime | 
| orderNumber | VBRK.BillingDocument | 
| orderStatus | xx | 
| partOfInvoice | xx | 
| paymentDueDate | xx | 
| paymentMethod | xx | 
| paymentMethodId | xx | 
| seller_sameAs | VBRK.SalesOrganization |
| total_value | VBRK.TotalNetAmount | 
| total_currencyCode | VBRK.TransactionCurrency | 
