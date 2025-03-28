# Data mapping Product

https://leanx.eu/en/sap/table/WAKP.html

## schema.org to SAP
|Source field | Target field | Transformation | Reference value mapping | 
|-------------|--------------|----------------|-------------------------|
| _SYSTEM_ID  | "SAP" |
|	_SYSTEM_TABLE_ID  | "WAKP" |
|	_SYSTEM_RECORD_ID | WAKP.Id |
|	_SYSTEM_CREATEDDATE  | WAKP.ERSDA (MARA.DATE_DE_CREATION)|
|	_SYSTEM_MODIFIEDDATE  | WAKP.LAEDA (MARA.LastChanged_Date)|
|@type | "Product" |
|sameAs | MARA.Id |
|brand | MARA.MARQUE (MARA.XXX) | 
| price | WAKP.WAKP_NVKP_Standard_sales_price | 
| priceCurrency | WAKP.WAKP_WAEEK_Purr_curr | 
| offeredBy | xx | 
| priceValidUntil | xx | 
| seller | xx | 
| validFrom | xx | 
| validThrough | xx | 
| validForMemberTier | xx | 
| shippingDetails | xx | 
| itemOffered_sameAs | WAKP.WAKP_ARTNR_Material | 
| mpn | xx | 
| category | xx | 
| name_en | xx | 
| name_fr | xx | 
| description_fr | xx | 
| description_en | xx | 

