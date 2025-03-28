# Data mapping Product

https://leanx.eu/en/sap/table/mara.html

## schema.org to SAP
|Source field | Target field | Transformation | Reference value mapping | 
|-------------|--------------|----------------|-------------------------|
| _SYSTEM_ID  | "SAP" |
|	_SYSTEM_TABLE_ID  | "MARA" |
|	_SYSTEM_RECORD_ID | MARA.Id |
|	_SYSTEM_CREATEDDATE  | MARA.ERSDA (MARA.DATE_DE_CREATION)|
|	_SYSTEM_MODIFIEDDATE  | MARA.LAEDA (MARA.DATE_DE_DERNIER_MODIFICATION)|
|@type | "Product" |
|sameAs | MARA.Id |
|brand | MARA.MARQUE (MARA.XXX) | 
|category | MARA.CATEGORIE_DE_PRODUIT2 | 
|color | MARA.ID_COULEUR (MARA.XXX) | 
|countryOfAssembly | xx | 
|countryOfLastProcessing | xx | 
|countryOfOrigin | xx | 
|depth_value | MARA.LONGUEUR (MARA.MEABM) | 
|depth_unitCode |  MARA.UNITE_LONGUER_LARGEUR_HAUTER (MARA.MEABM) | 
|gtin | xx | 
|height_value | MARA.HEIGHT (MARA.HOEHE) () |
|height_unitCode |(MARA.UNITE_LONGUER_LARGEUR_HAUTER (MARA.MEABM)  | 
|isProductGroupWithId | xx | 
|isAccessoryOrSparePartFor | xx | 
|isConsumableFor | xx | 
|isRelatedTo | xx | 
|isSimilarTo | xx | 
|isVariantOf | xx | 
|itemCondition | xx | 
|keywords_en | xx | 
|keywords_fr | xx | 
|logo | xx | 
|manufacturer | xx | 
|material | xx | 
|model | xx | 
|mpn | MARA.MFRPN | 
|material | xx | 
|pattern | xx | 
|productID | MARA.MATNR (ARTICLE)| 
|releaseDate | xx | 
|sku | xx | 
|slogan | xx | 
|weight_value |  MARA.POIDS_BRUT (MARA.XXX) | 
|weight_unitCode |  MARA.UNITE_DE_POIDS (MARA.XXX) | 
|width_value | MARA.LARGEUR (MARA.XXX) | 
|width_unitCode | (MARA.UNITE_LONGUER_LARGEUR_HAUTER (MARA.MEABM) | 
|name_en | xx | 
|name_fr | MARA.DESCRIPTION_ARTICLE (MARA.XXX) | 
|description_en | xx | 
|description_fr | xx | 
|image | xx | 
|url | xx | 






