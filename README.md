# API-Gateway


## How to run?
- `git clone <repo_name>` to clone the project
- Ensure **Consul**, **MySql**, and **MongoDB** is installed, configured and run
- Create a new database with `CREATE DATABASE helloworlddb;` in **Myql**
- Start Discovery Server(**Consul**) by running `consul agent -data-dir=your-consul-data-file -dev -ui`
- Run UsersService, RequestsService, and OffersService under their folders by running `gradlew run` for each service
- Run Gateway with `gradlew run`

## Trying Services


#### 1) Register John as user.
![Image of Diagram](https://github.com/laceett/API-Gateway/blob/main/images/1.png)

#### 2) Register Mike as Service_provider.

#### 3) Login with John's credentials 

#### 4) Login with Mike Credentials. 

#### 5) Submit a Service Request. 

#### 6) Submit Offer

#### 7) get the offers of a service request 

#### 8) Accept Offer

#### 9) Reject Offer

