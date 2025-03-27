
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
| Person | ff| ff | John Smith |
| Organization | ff | ff | [Mondou Inc.](https://github.com/schapleau-legault/schema/blob/main/data/organization/mondou_inc.json)| 
| Brand | A brand is a name used by an organization or business person for labeling a product, product group, or similar. | https://schema.org/Brand | [Mondou](https://github.com/schapleau-legault/schema/blob/main/data/brand/renspets.json), [Ren's Pets](https://github.com/schapleau-legault/schema/blob/main/data/brand/renspets.json), [Homes Alive](https://github.com/schapleau-legault/schema/blob/main/data/brand/homes_alive.json)| 
| Product | Any offered product or service. | https://schema.org/Product | [VetDiet Adult all breeds dog food](https://github.com/schapleau-legault/schema/blob/main/data/product/vetdiet_adult_all_breeds.json) |






