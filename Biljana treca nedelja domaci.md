`                                                 `Biljana treca nedelja domaci

Verify  that user can have only name

1. Click on “Osnovni podaci”
1. Enter name in field name
1. Leave field “prezime” empty
1. Click on Done

Uraditi kao tabelu Steps - Test Data-Expected result

Expected: The user can not save with only a name. Both fields are mandatory.

ovo su premale kejseve, uzmi kejs gde CELA jedna forma ne moze biti poslata jer je prazna
Verify that user can have only last name

1. Click on “Osnovni podaci”
1. Leave field “ime” empty 
1. Enter last name in field last name
1. Click on Done

Ovo je jedna od najcescij gresaka,

za razliku od bug reporta , u test kejsu SVAKI step ima SVOJ expected result :)  Pregledacu kad budes uradila tabelu

Expected: The user can not save with only last name. Both fields are mandatory.

Verify that user can not enter a single field

1. Click on “Osnovni podaci”
1. Leave the name field empty
1. Leave the last name field empty
1. Click on Done

Expected: It is not possible for both fields to be empty

Verify that user can enter only “Naziv univerziteta”

1. Click on “Edukacija”
1. Click on “Dodaj edukaciju”
1. Enter name “Naziv univerziteta”
1. Field “Smer” is empty
1. Field “Od” is empty
1. Field “Do” is empty
1. Click on “Sacuvaj”

Expected: It is not possible to save without all mandatory fields.

Verify that user can enter only one letter in field name

1. Click on “Osnovni podaci”
1. Enter one letter in field name
1. Enter last name in field last name
1. Cick on Done

Expected drugaciji ako pricamo o nazivu kejsa. 

Expected treba da bude pored toga sto user ne moze da doda da, user odtaje na istoj stranici, ime se nije promenilo, da li bila neka greska?

Expected: The user can not save with only a name.

Verify that user can enter across 40 letters in field name

1. Click on “Osnovni podaci”
1. Enter across 40 letters in field name
1. Enter last name in field last name
1. Click on Done

oo je max limit ili?

Expected: The user can not save with only a name.







