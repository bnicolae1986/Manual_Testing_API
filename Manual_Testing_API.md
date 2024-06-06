# API Testing Project for Simple Books API

The scope of this project is to use all API knowledge gained throught the Software Testing course and apply them in practice, using a live application.

Application under test: Simple Books

Tools used: Postman

Collection link: Inserati aici linkul catre colectia de API

## Tests performed

### 1. Status

- HTTP method for request: GET

- Request description: Returns the status of the API

- Test types / techniques used: Functional Testing, Smoke Testing, Regression Testing

- Response status code: Status 200 "OK"

Below you can find a picture of the API request from Postman:

 ![get status](https://github.com/bnicolae1986/Manual_Testing_API/assets/156198321/9df01ec7-6fea-446e-81bc-54b4b1904559)

 ![variables environment](https://github.com/bnicolae1986/Manual_Testing_API/assets/156198321/7d2ef788-8bc2-4cd4-97a1-6a3069bbf62c)

- JavaScript Tests:


![get status2](https://github.com/bnicolae1986/Manual_Testing_API/assets/156198321/c2eecc20-7efe-48c9-a548-04804fb4ac07)

 
### 2. List of books

HTTP method for request: GET

Request description: Returns a list of books

Test types / techniques used: Functional Testing, Smoke Testing, Regression Testing

Response status code: Status 200 "OK"

Below you can find a picture of the API request from Postman:

![get books](https://github.com/bnicolae1986/Manual_Testing_API/assets/156198321/d422996c-c784-46d6-9c1d-a0deb35e0075)


JavaScript Tests:

![teste books](https://github.com/bnicolae1986/Manual_Testing_API/assets/156198321/9d661281-0243-4632-8ef0-8fe6e9d409f7)

![teste books2](https://github.com/bnicolae1986/Manual_Testing_API/assets/156198321/2c23eb83-6e6a-456a-9b88-707c698d7eda)


### List of books with parameters

HTTP method for request: GET

Request description: Returns a list of books, filtered by parameters 

    Optional query parameters:

    type: fiction or non-fiction
    limit: a number between 1 and 20

Test types / techniques used: Functional Testing, Input Validation Testing, Usability Testing

Response status code: Status 200 "OK"

Below you can find a picture of the API request from Postman:
 

## Execution report for the created API collection

Below you can find the execution report that was generated through the Postman collection runner.

Inserati aici o poza cu raportul de executie din Postman

The collection was also run through newman directly from the terminal, and the results can be found below:

Inserati aici o poza cu raportul de executie din Newman

## Defects found

The following issues were identified while running the postman tests:

**Inserati aici fie un fisier pdf care sa contina raportarea tuturor bug-urilor, fie le descrieti direct in git Bug-urile trebuie sa contina titlu, preconditii, pasi de executie, rezultate asteptate si rezultate actuale. Optional, bug-urile pot fi raportate in jira, si apoi puteti pune poze direct din jira

## Conclusions

Inserati aici concluziile pe care le-ati obtinut in urma executarii testelor si introduceti informatii cum ar fi cate teste au fost create si executate, ce procentaj aproximativ din cerintele in scop au fost acoperite, daca exista vreo functionalitate pe care nu ai apucat sa o testezi, daca bug-urile gasite impacteaza lansarea produsului in productie sau se pot fixa si ulterior, daca ai identificat riscuri de produs care trebuie mitigate, daca e vreo reecomandare pe care vrei sa o faci pentru lansare, daca sunt ceva lessons learned de care trebuie sa se tina cont la proiectele viitoare etc
