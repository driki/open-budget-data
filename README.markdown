Overview
-------------------
Open Budget Data for cities and towns in the United States in CSV format. Developers can fork the project and provide budgets for new cities and towns. Open Budget Data is the format used by the Budget Vision (http://www.budgetvision.com) presentation tool used by cities and towns to help explain their budgets to the public. Budget Vision allows you to upload your Budget Vision formatted CSV via the website or using the ingest API.

CSV Structure
-------------------

* IS_EXPENSE (boolean)
* CATEGORY_NAME (string)
* CATEGORY_AMOUNT (float)
* CATEGORY_TAGS (string)
* SUB_CATEGORY_NAME (string)
* SUB_CATEGORY_AMOUNT (float)
* SUB_CATEGORY_TAGS (string)
* ITEM_NUMBER (integer, possibly an internal object code or rerefence number)
* ITEM_NAME (string)
* ITEM_DESCRIPTION (text)
* ITEM_AMOUNT (numeric)
* ITEM_TAGS (string)