# Seattle-House-Sales

## Summary

Identified analyzed and interpreted various trends in housing prices based on the distribution of bedrooms and area. Performed data visualization using Tableau. 

## Applies to

* [Tableau](https://public.tableau.com/app/discover)

## Authors

Solution|Author(s)
--------|---------
Seattle House Sales Dashboard | [Kaavya Varshitha Raman Shantha](https://github.com/KaavyaVarshitha) 
## Version history

Version|Date|Comments
-------|----|--------
1.0|July 2023|Initial release


## Features

This dashboard illustrates the following concepts:

* Creating an appealing dashboard to show housing prices.
* Creating charts to show various trends in housing prices based on the distribution of area.

## Data Sources
 
* [Kaggle Seattle House Sales](https://www.kaggle.com/datasets/sameersmahajan/seattle-house-sales-prices)

## Data cleaning

* [Download](https://www.kaggle.com/datasets/sameersmahajan/seattle-house-sales-prices) the `.csv` from Kaggle.
* Export `.csv` to `.xls`
* Remove duplicates and incomplete cases.
* Fix structural errors.
* Ensure the data is formatted correctly.
* Check for data consistency.
* [Download](https://github.com/pnp/powerapps-samples/blob/main/samples/Timesheet/solution/WeeklyTimesheet.msapp) the `.xls` file from the solutions folder.

## Data Visualization

You can also use the [Power Apps CLI](https://docs.microsoft.com/powerapps/developer/data-platform/powerapps-cli) to pack the source code by following these steps::

* Clone the repository to a local drive
* Pack the source files back into `.msapp` file:
  ```bash
  pac canvas pack --sources pathtosourcefolder --msapp pathtomsapp
  ```
  Making sure to replace `pathtosourcefolder` to point to the path to this sample's `sourcecode` folder, and `pathtomsapp` to point to the path of this solution's `.msapp` file (located under the `solution` folder)
* Use the `.msapp` file using **File** > **Open** > **Browse** in Power Apps Studio.
