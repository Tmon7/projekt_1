# Projekt
Testovací scenár

## Prehľad nástrojov
#### MySQL Workbench 
prístup do databáze
#### Postman 
zasielanie požiadaviek na REST API


## Zadanie 
Cieľom prvého projektu je otestovať REST rozhranie bežiace na adrese  https://students-api.engeto.com/api/v1/students.
Rozhranie slúži na manipuláciu dát študentov. Otestujte metódy GET, POST a DELETE.

#### Metóda GET 
GET https://students-api.engeto.com/api/v1/students/ má vrátiť záznam študenta s daným id

#### Metóda POST 
POST https://students-api.engeto.com/api/v1/students/ vytvorí študenta s týmito parametrami:
{
    "firstName":"jmeno",
    "lastName": "primeni",
    "email": "emailova_adresa",
    "age": 25
}

#### Metóda DELETE
DELETE https://students-api.engeto.com/api/v1/students/<id-studenta> zmaže študenta s daným id
