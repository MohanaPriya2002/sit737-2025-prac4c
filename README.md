# sit737-2025-prac4c
 
This a simple calculator microservice that built using Express and Winston Libraries. It consits of basic arithematic operations to a bit advanced operations like addition, subtraction, multiplication, division, exponentiation, square root and modulo. Logging is handled by using Winston library.

# Installation

**Prerequisites**

Install Node.js on your system
Install Express and Winston libraries using npm

**Steps to Install**

- Clone the Repository
  ```bash
  git clone git@github.com:MohanaPriya2002/sit737-2025-prac4c.git
  ```
- Navigate to the project folder
  ```bash
  cd project-folder-name
  ```
- Install dependencies
  ```
  npm install
  ```
- Install Winston and Express
  ```bash
  npm install express
  ```
  And
  ```bash
  npm install winston
  ```
**Run the Project**
- Start the server
  ```bash
  node advcalcimicroservice.js
  ```
  By default the server runs on the PORt 3040

- API endpoints
  Run the URL in the browser
  ```bash
  http://localhost:3040/calculator?n1=value&n2=value&operation=operation
  ```
  For example
  ```bash
  http://localhost:3040/calculator?n1=12&n2=9&operation=exp
  ```
