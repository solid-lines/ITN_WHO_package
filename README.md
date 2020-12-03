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

5) Add manually the userGroups involved. Remove the users (use import/export app)


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

4) Add manually the userGroups involved. Remove the users (use import/export app)

- For dataset ITN Mass Campaign - Daily summary form
5) Add manually the dataElementGroups (ITN Mass Campaign (Summary Form))


Steps for merged datasets
----------------------------------------------------------------

1) Make a copy of the biggest dataset (ITN Mass Campaign - Daily summary form)
2) Add from ITN Mass Campaign - Microplanning Information the parts:
- dataElements (merge)
- dataSets (merge)
- optionSets (full)
- options (full)


Steps for each dashboard
----------------------------------------------------------------

1) Export the dashboard using the import/export app
2) Remove organisationUnits (if they are present)
3) Add manually:
- legendSets named as ITN (to obtain them, use the import/export app)
- all indicatorTypes (to obtain them, use the import/export app)
- indicatorGroups named as ITN (to obtain them, use the import/export app)
- indicators named as ITN (to obtain them, use the import/export app. Fast approach, remove the others because ITN indicators are in the middle of the file)

4) Add manually the userGroups involved. Remove the users (use import/export app)



