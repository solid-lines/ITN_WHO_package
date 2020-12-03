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
