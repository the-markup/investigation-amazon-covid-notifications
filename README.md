# Amazon's COVID Notifications

This contains the data for our story, "[Data Provided by Amazon Workers Offers Rare Glimpse into COVID Cases in California Warehouses](https://themarkup.org/working-for-an-algorithm/2022/02/10/data-provided-by-amazon-workers-offers-rare-glimpse-into-covid-cases-in-california-warehouses)."

The data is based on daily COVID exposure notifications sent to employees through the Amazon A to Z app.

## Data

Each CSV file in the `data` folder is labeled with the warehouse name.

For each CSV, the data dictionary is as follows:

| **Column** | **Description** |
|------------|-----------------|
| **`date`** | When the exposure notice is dated. |
| **`total_cases_in_notice`** | The total number of individuals the notification is about. |
