# Ledger Challenge

## Introduction

This is our programming exercise.

Our goal is to evaluate your programming skills level and learn more about you. You should work on the stories provided below and then, we will do a code review and invite you to an interview :)

## Exercise

### Introduction

Keeping track of how much money we have is important for everyone.
Let's imagine we have two bank accounts and a wallet. It would be good to have a system that keeps track of all of them at the same time, monitoring deposits and transfers between them.

### Use case

You are someone who really wants to keep track of all of your money in the same place, knowing your current balance and being able to create transfers between your accounts.

Let's imagine that you have two bank accounts, `Bank A`, `Bank B` and you also have your `Wallet`. It would be good to be able to add them to the system to track their balances. Let's create these three accounts with `R$100.00` on each of them, as follows:

| Account |  Balance   |
| ------- | :--------: |
| Bank A  | R\$ 100.00 |
| Bank B  | R\$ 100.00 |
| Wallet  | R\$ 100.00 |

If we make a transfer from `Bank A` to `Bank B` of `R$50.00`, this would be the final account balances:

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
As a user
I want to set up my accounts with their name and initial balances in the system
So I can insert information about my accounts' initial status
```

Requirements:

- Besides the balance, each account should have a name, so the user can remember them.

#### Story 2: Transactions

```
As a user
I want to be able to make deposits and transfers between accounts
So that I can update and see my accounts with their current balances
```

Requirements:

- A transactions must happen between different accounts;
- Deposits do not need any external information.

#### Story 3: List Accounts

```
As a user
I want to be able to see my accounts' information
So that I can see how much money I have on each account
```

Requirements:

- Accounts should be shown in a table;
- Accounts should have the balance information.

## Instructions

In order to implement the user stories listed above, please, choose one of the following instructions: back-end or front-end. If you want to do both, we will consider this an extra point and effort but it is not mandatory.

### Backend Instructions

- Your REST API should be implemented using JSON;
- You should persist the data received in a Database;
- You can use Docker for setting up external applications such as a database.

### Frontend Instructions

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
- You should build the backend in Elixir and the frontend, in React or Elm. :)

## References

- [Elixir School](https://elixirschool.com/pt/)
- [Phoenix Framework](http://www.phoenixframework.org/)
- [Credo](https://github.com/rrrene/credo)
- [Style Guide](https://github.com/christopheradams/elixir_style_guide)
- [Phoenix Ecto Cheatsheet](https://devhints.io/phoenix-ecto)
