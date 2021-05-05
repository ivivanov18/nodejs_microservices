# TICKETING APP

## Introduction

Ticketing app that allow a user to list tickets that are for sale for a given event and purchase them. When added the tickets will be locked for a period of 15 minutes for the current user and no one else will be able to purchase this same ticket.

## Functionalities offered

- auth related: signin, signup, and signout
- list tickets for a given event
- choose tickets to buy
- enter payment information

## Technologies

- Express framework
- React
- Typescript
- Docker
- Kubernetes

## Details

### Entities

- User
- Order
- Ticket
- Charge

### Services

- auth: related to user signin/ signup and signout
- tickets: related to tickets creation and editing. The tickets will be editable only when they are not locked by a given user for purchase
- orders: related to orders management
- expiration: related to checking whether an order is locked and cannot be edited or purchased by another user
- payments: related to credit card payments
