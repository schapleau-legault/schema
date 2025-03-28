# Data mapping OrderItem

https://leanx.eu/en/sap/table/vbrp.html

## schema.org to SAP
|Source field | Target field | Transformation | Reference value mapping | 
|-------------|--------------|----------------|-------------------------|
| _SYSTEM_ID  | "SAP" |
|	_SYSTEM_TABLE_ID  | "VBRP" |
|	_SYSTEM_RECORD_ID | VBRP.Id |
|	_SYSTEM_CREATEDDATE  | VBRP.ERSDA (MARA.DATE_DE_CREATION)|
|	_SYSTEM_MODIFIEDDATE  | VBRP.LAEDA (MARA.DATE_DE_DERNIER_MODIFICATION)|
| @type | "OrderItem" |
| sameAs | VBRP.Id |
| name | VBRP.BillingDocumentItemText | 
| order_orderNo | VBRP.BillingDocument | 
| orderItemNumber | VBRP.BillingDocumentItem | 
| orderQuantity_value | VBRP.BillingQuantity | 
| orderQuantity_unitCode | VBRP.BaseUnit | 
| price | VBRP.CreditRelatedPrice | 
| priceCurrency | VBRP.DEVISE_DOCUMENT | 
| orderedItem_sameAs | VBRP.Material | 
| orderDelivery | xx | 
| discount | VBRP.Subtotal2Amount | 
| discountCode | VBRP.RetailPromotion | 
| total | VBRP.Subtotal6Amount | 
| totalCurrency | VBRP.DEVISE_DOCUMENT | 
