# freecodecamp-Periodic_Table

This project was made in psql and bash scripting for freecodecamp DB Relational certification.


HINT:
use this queries for removing trailing zeroes:

update properties set atomic_mass=trim(trailing '0' from cast(atomic_mass as text))::decimal;
