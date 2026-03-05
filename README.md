# Wallet Service API

This project is a simple Wallet Service REST API built using **Java, Spring Boot, and PostgreSQL**.  
It allows users to deposit money, withdraw money, and check wallet balance.

## Tech Stack

- Java
- Spring Boot
- PostgreSQL
- Maven
- REST API

## Features

- Deposit money into wallet
- Withdraw money from wallet
- Get wallet balance
- RESTful API endpoints

## API Endpoints

### Deposit / Withdraw

POST `/api/v1/wallet`

Example Request Body:

```json
{
  "walletId": "11111111-1111-1111-1111-111111111111",
  "operationType": "DEPOSIT",
  "amount": 5000
}
