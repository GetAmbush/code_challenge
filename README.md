# Ambush Code Challenge

## Introduction

This is our programming exercise.

Our goal is to evaluate your programming skills level and learn more about you. You should work on the stories provided here and then we will do a code review and invite you to an interview :)

## Exercise

### Introduction

Keeping track of how much money we have is important for everyone.
Let's say we have two bank accounts and our wallet, it would be good to have a system that kept track of all of them at the same time, monitoring transfers between them and deposits on them.

### Use case

You are a person that really wans to keep track of all of your money in the same place, knowing the current balance of your accounts and being able to create transfers between your accounts (to keep track of your real transfers) for similar events.

As an example, we could have three accounts called `Bank A`, `Bank B` and `Wallet`. Let us say that we started the system having `R$100.00` on each of them as follows:

| Account |  Balance   |
| ------- | :--------: |
| Bank A  | R\$ 100.00 |
| Bank B  | R\$ 100.00 |
| Wallet  | R\$ 100.00 |

If we create a transfer from `Bank A` to `Bank B` of `R$50.00`, we would the final account balances as:

| Account |  Balance   |
| ------- | :--------: |
| Bank A  | R\$ 50.00  |
| Bank B  | R\$ 150.00 |
| Wallet  | R\$ 100.00 |

And if someone externallly deposits `R$ 200.00` on account `Bank A`, we would have:

| Account |  Balance   |
| ------- | :--------: |
| Bank A  | R\$ 250.00 |
| Bank B  | R\$ 150.00 |
| Wallet  | R\$ 100.00 |

### Global Requirements

- Create accounts;
- Create transactions between accounts;
- Create deposits for an account;
- Show accounts and their balance;

### User Stories

#### Story 1: Manage Accounts

```
As an user
I want to set up my accounts with their name and initial balances in the system
So that I can insert information about my accounts initial status
```

Requirements:

- Besides the balance, each account should have a name, so the user can remember them.

#### Story 2: Transactions

```
As an user
I want to be able to create transfers between accounts and deposits
So that I can update and see my accounts with their updated balances
```

Requirements:

- A transaction cannot happen for the same account;
- Deposits do not need any external information.

#### Story 3: List Accounts

```
As an user
I want to be able to see my accounts information
So that I can see how much money I have on each account
```

Requirements:

- Accounts should be shown as a table;
- Accounts should have the balance information.

## Instructions

In order to implement the user stories listed above, please, choose one of the following instructions: back-end, or front-end. If you want to make both, we will consider this an extra point and effort, but it is not mandatory.

### Backend Instructions

- Your REST API should be implemented using JSON;
- You should persist the data received in a Database;
- You can use Docker for setting up external applications such as a database.

## Frontend Instructions

- The design is up to you, we won't be evaluating any kind of designer skills in this task.

## What will be evaluated

- Implementation is working as expected;
- A README file on how to setup the application and run it;
- Automated tests;
- Linter/Static code analysis;
- Code is clean and cohesive.

## How to share your solutions with us

Drop us an email :)

## Important Notes

- If you have any questions, reach out to us and we will gladly help, you are not going to be penalized by this;
- Take as much time as needed and _communicate as much as necessary_;
- The challenge is not only to solve the problem but showcase how much you know about good programming practices;
- You can document your assumptions for this challenge;
- You should build the backend in Elixir and the frontend in React or Elm. :)
