"# ITN_WHO_package" 

Steps for Tracker Program ITN Mass Campaign - Household Register
----------------------------------------------------------------

1) Export the tracker program using the import/export app
2) Remove organisationUnits in programs section
3) Update from PSI defaults to DHIS2 defaults
	category (SQL dataelementcategory)
	  - PSI default "evIUQOgObj3"
	  - DHIS2 default "GLevLNI9wkl"

	categoryOption (SQL dataelementcategoryoption)
	  - PSI default "gnS5549wCkG"
	  - DHIS2 default "xYerKDKCefk"

	categoryCombo (SQL categorycombo)
	  - PSI default "vBNfvFQQ0q3"
	  - DHIS2 default "bjDvmb4bfuf"

	categoryOptionCombo (SQL categoryoptioncombo)
	  - PSI default "XfXL6fEveof"
	  - DHIS2 default "HllvX50cXC0"

4) Add manually the dataElementGroups (ITN Mass Campaign (Household Tracker))

PENDING) Add the userGroups involved?


Steps for each dataset
----------------------------------------------------------------

1) Export the dataset using the import/export app
2) Remove organisationUnits in dataSets section
3) Update from PSI defaults to DHIS2 defaults
	category (SQL dataelementcategory)
	  - PSI default "evIUQOgObj3"
	  - DHIS2 default "GLevLNI9wkl"

	categoryOption (SQL dataelementcategoryoption)
	  - PSI default "gnS5549wCkG"
	  - DHIS2 default "xYerKDKCefk"

	categoryCombo (SQL categorycombo)
	  - PSI default "vBNfvFQQ0q3"
	  - DHIS2 default "bjDvmb4bfuf"

	categoryOptionCombo (SQL categoryoptioncombo)
	  - PSI default "XfXL6fEveof"
	  - DHIS2 default "HllvX50cXC0"

PENDING) Add the userGroups involved?

For dataset ITN Mass Campaign - Daily summary form
4) Add manually the dataElementGroups (ITN Mass Campaign (Summary Form))

Steps for merged datasets
----------------------------------------------------------------

1) Create one file with:
