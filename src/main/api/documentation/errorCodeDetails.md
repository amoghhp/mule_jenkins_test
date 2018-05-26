**Overview** : Details of error codes defined for the BioConnect Lot Batch API

**Error Code Details** : 

**Lot Batch Validation API :**
| Error Code    |   Status       |   Error Message/Description   |
| ------------- |:--------------:|-------------------------------|
| AMG-1001  |inValid| Batch no is not valid|
| AMG-1002  |partial| Batch no is valid but enterd product is not valid|
| AMG-1003  |partial| Batch no and product detail are valid, but dosage is incorrect|
| AMG-1004  |partial| Batch no and dosage details are valid, but product is not valid|
| AMG-1005  |partial| Batch no is valid but enterd product and dosage details are not valid|

**Retrieve Lot Batch Tree API :**
| Error Code    |   Status       |   Error Message/Description   |
| ------------- |:--------------:|-------------------------------|
| AMG-2001  |inValid| Product is inValid|
| AMG-2002  |partial| Product is valid but Batch no is not valid|