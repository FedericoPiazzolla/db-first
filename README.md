### ESERCIZIO
Modellizzare la struttura di una tabella per memorizzare tutti i dati riguardanti delle auto usate messe in vendita da un concessionario.

---

### TABELLA PER AUTO SALONE DI AUTO USATE

| OBJECT              | TYPE            | MORE |
|  :---:              |:---:            |:---: |
**ID**                | INT             | UNISIGNED - PRIMARY_KEY - NOTNULL - UNIQUE - AUTOINCREMENT |
**MANUFACTURER_NAME** | VARCHAR(255)    | NOTNULL |
**BRAND**             | VARCHAR(255)    | NOTNULL |
**MODEL**             | VARCHAR(255)    | NOTNULLA |
**KM_TRAVELLED**      | DECIMAL(10, 2)  | NOTNULL - DEFAULT(0) |
**PRICE**             | DECIMAL(9, 2)   | NOTNULL |
**DISCOUNT**          | DECIMAL(9, 2)   | NOTNULL - DEFAULT(0) |
**FRAME_NUMBER**      | VARCHAR(17)     | NOTNULL |
**FUEL_TYPE**         | VARCHAR(255)    | NOTNULL |
**CONDITION**         | VARCHAR(255)    | NOTNULL |
**DESCRIPTION**       | TEXT            | NULL |
**POWER(CV)**         | INT             | UNSIGNED - NULL |
**OWNERS_NUMBERS**    | INT             | UNSIGNED - NULL |
**SEATS_NUMBERS**     | INT             | UNSIGNED - NULL |
**COLOR**             | VARCHAR(255)    | NOTNULL |
**EMMISSION_CLASS**   | VARCHAR(255)    | NOTNULL |
**REGISTRATION_YEAR** | YEAR            | NOTNULL |
**FINANCING**         | DECIMAL(10,2)   | NULL - DEFAULT(0) |