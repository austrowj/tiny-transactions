# tiny-transactions
Tiny tool for helping manage a budget.

## Feature Roadmap
* Database with all required fields
  * Primary key (autoincrement for now)
  * Datetime of record creation
  * Date of transaction
  * Time of transaction
  * Amount
  * Vendor
  * Category
  * Notes
  * Tags (as a text blob, possibly json?)
* Basic CLI
  * Entering new records
  * List/total transactions in a given timeframe for a given category
