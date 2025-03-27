# PostalAddress

## Schema.org to Salesforce
|Source field | Target field | Transformation | Reference value mapping | 
|-------------|--------------|----------------|-------------------------|
|addressCountry | MailingCountry|
|addressLocality | MailingCity|
|addressRegion | MailingState|
|postOfficeBoxNumber | MailingStreet (if PO box is part of the street address)|
|postalCode | MailingPostalCode|
|streetAddress | MailingStreet|

