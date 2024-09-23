# Currency Conversion API
## API Documentation
This project was developed using `Java 11`, `Spring Boot v3.3.3` and `Junit 5` for unit testing. Documentation was done using `Swagger`.
## Installation
1. Clone the repository - Make sure you have `Java 11` installed and `Maven`.
   ```bash
   git clone https://github.com/alissonmorais07/java-challenge.git
- After that, download the required dependencies in pom.xml. Then look for the `CurrencyConverterApplication` main class and run it using `CTRL + SHIFT + F10` or click the run button.

2. Open your favorite request tool. Examples: `Postman`, `Insomnia` or other.
- For the `POST` method, choose the currency pair to perform the conversion. One for Base and one for destination.
  Exemple: Example: Euro(EUR) to Japanese Yen(JPY)
- Request body:
  ```bash
  {
  "fromCurrency": "EUR",
  "toCurrency": "JPY",
  "value": 278.59,
  "userdID": 1
  }
![Captura de tela de 2024-09-19 20-12-37](https://github.com/user-attachments/assets/8639c40a-3568-4ca7-854e-125286414150)
- For the GET method, execute the request: `localhost:8080/api/list` to return all transactions or `localhost:8080/api/list?userID=1` to return a transaction for a specific user.

![Captura de tela de 2024-09-19 20-19-10](https://github.com/user-attachments/assets/873e2978-f91e-4813-8d02-7327dff24ae2)
![Captura de tela de 2024-09-19 21-21-52](https://github.com/user-attachments/assets/b9e16035-3eb4-4e55-8ad0-68ccda1f8fbc)

## Using Render

  
