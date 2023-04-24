# Travel-Management-System
A travel management system for students.

![Screenshot_2023-04-24_21-57-15](https://user-images.githubusercontent.com/73023696/234058733-bc5cbb48-38f4-4a42-81fc-c694f154e7c3.png)



Table: COUNTRIES
Columns:

COUNTRY_ID (primary key)
COUNTRY_NAME
REGION_ID (foreign key to REGIONS table)
CURRENCY_CODE (foreign key to CURRENCIES table)
LOCATION
POPULATION
AIRPORTS
CLIMATE


Table: REGIONS
Columns:

REGION_ID (primary key)
REGION_NAME


Table: CURRENCIES
Columns:

CURRENCY_CODE (primary key)
CURRENCY_NAME


Table: SPOKEN_LANGUAGES
Columns:

LANGUAGE_ID (primary key)
LANGUAGE_NAME


Table: LANGUAGES
Columns:

COUNTRY_ID (foreign key to COUNTRIES table)
LANGUAGE_ID (foreign key to SPOKEN_LANGUAGES table)
OFFICIAL


1st Normal Form (1NF): All columns are atomic and there are no repeating groups.
2nd Normal Form (2NF): The table has a single-column primary key, and all non-key columns are fully dependent on the primary key.
3rd Normal Form (3NF): There are no transitive dependencies, all non-key columns are dependent only on the primary key.


COUNTRIES: COUNTRY_ID, COUNTRY_NAME, REGION_ID, CURRENCY_CODE, LOCATION, POPULATION, AIRPORTS, CLIMATE

REGIONS: REGION_ID, REGION_NAME

CURRENCIES: CURRENCY_CODE, CURRENCY_NAME

SPOKEN_LANGUAGES: LANGUAGE_ID, LANGUAGE_NAME
