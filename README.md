
# schema
Schema definition for use within Legault Group

## Overview
Legault Group uses a common schema definition for communication between systems. Thi schema is also used for system agnostic data storage (such as within the data warehouse for example). 

## Standard
The common schema is based on schema.org (https://www.schema.org) with some specific adjustments made to accomodate Legault Group specific requirements. 

## Why schema.org

## Main objects
|Object | Definition | Reference | Example | 
|-------| ----------- | ---------------- | ------------| 
| Person | A person (alive, dead, undead, or fictional). | https://schema.org/Person | John Smith |
| Organization | An organization such as a school, NGO, corporation, club, etc. | https://schema.org/Organization | [Mondou Inc.](https://github.com/schapleau-legault/schema/blob/main/data/organization/mondou_inc.json)| 
| Brand | A brand is a name used by an organization or business person for labeling a product, product group, or similar. | https://schema.org/Brand | [Mondou](https://github.com/schapleau-legault/schema/blob/main/data/brand/renspets.json), [Ren's Pets](https://github.com/schapleau-legault/schema/blob/main/data/brand/renspets.json), [Homes Alive](https://github.com/schapleau-legault/schema/blob/main/data/brand/homes_alive.json)| 
| Product | Any offered product or service. | https://schema.org/Product | [VetDiet Adult all breeds dog food](https://github.com/schapleau-legault/schema/blob/main/data/product/vetdiet_adult_all_breeds.json) |
| Store | A retail good store. | https://schema.org/Store | [Mondou Atwater](https://github.com/schapleau-legault/schema/blob/main/data/store/mondou_atwater.json) |
| Offer | An offer to transfer some rights to an item or to provide a service. | https://schema.org/Offer | [Example]() |
| Order | An order is a confirmation of a transaction (a receipt), which can contain multiple line items, each represented by an Offer that has been accepted by the customer. | https://schema.org/Order | [Example]() |
| Invoice | A statement of the money due for goods or services; a bill. | https://schema.org/Invoice | [Example]() |


## Object mapping
|Object | Salesforce | SAP | Dynamics | 
|-------|------------|-----|----------|
|Person | Contact | xx | xx |
|Organization | Account | xx | xx |
|Product | Product2 | MARA, MAW1 | xx |
|Offer | PriceCatalogItem | xx | xx |
|Order | Order, OrderItem | VBRK, VBRP | xx |
|Invoice | Invoice, InvoiceLineItem | xx | xx |



