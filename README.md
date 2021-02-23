# API-Gateway


## How to run?
- Clone the project
  `git clone <REPO_LINK>`

- Ensure **Consul**, **MySql**, and **MongoDB** is installed, configured and run

- Create a new database with 
    `CREATE DATABASE helloworlddb;`
    in **Myql**

- Start Discovery Server(**Consul**) by running 
    `consul agent -data-dir=your-consul-data-file -dev -ui`

- Run UsersService, RequestsService, and OffersService under their folders by running
    `gradlew run` 
    for each service

- Run Gateway with
    `gradlew run`


## Trying Services

You can use any Rest Client application (I used **Postman**) to test the implementation.

#### 1) Register John as user
![Image of Diagram](https://github.com/laceett/API-Gateway/blob/main/images/1.png)

#### 2) Register Mike as Service_provider
![Image of Diagram](https://github.com/laceett/API-Gateway/blob/main/images/2.png)

#### 3) Login with John's credentials
![Image of Diagram](https://github.com/laceett/API-Gateway/blob/main/images/3.png)

#### 4) Login with Mike Credentials
![Image of Diagram](https://github.com/laceett/API-Gateway/blob/main/images/4.png)

#### 5) Submit a Service Request
![Image of Diagram](https://github.com/laceett/API-Gateway/blob/main/images/5.png)

#### 6) Submit Offer
![Image of Diagram](https://github.com/laceett/API-Gateway/blob/main/images/6.png)

#### 7) get the offers of a service request
![Image of Diagram](https://github.com/laceett/API-Gateway/blob/main/images/7.png)

#### 8) Accept Offer
![Image of Diagram](https://github.com/laceett/API-Gateway/blob/main/images/8.png)

#### 9) Reject Offer
![Image of Diagram](https://github.com/laceett/API-Gateway/blob/main/images/9.png)

