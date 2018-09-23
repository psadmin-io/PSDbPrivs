# PeopleSoft Database Privileges
Store and handle database privileges for PeopleSoft tables and views
* Built on PeopleTools 8.56

1. Import the project into a target database.
2. Build the table.
3. Build the views.
4. Run the insert statement to import the existing privileges.

Note that if you want to make use of the Lookup Exclusion table, it may be better to populate this table before running step number 4. Otherwise you will need to manually remove the permissions from the table.
