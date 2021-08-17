# ATM challenge

## Introduction

This challenge is to write a software for an ATM, where a few rules, must be applied in order to
withdraw money.

Source: https://dojopuzzles.com/problems/caixa-eletronico/

> PS the source is in portuguese.

## Exercise

Develop a software that simulates a withdraw where the the user inputs the money amount and the
software outputs is the money bills the user can take from the machine, following the rules:

- The sofware needs to delivery as low money bills as possible.
- Is only possible to withdraw valid amounts according to the available money bills.
- There is no need to check the user's balance.
- There is no need to count the number of available money bills.
- The available money bills as $2, $5, $10, $20, $50.

### Use case

#### Case 1

Given the user which wants to withdraw $30.

The software needs to return one money bill for $20 and one for $10.

#### Case 2

Given the user which wants to withdraw $45.

The software needs to return two money bill for $20 and one for $5.

#### Case 3

Given the user which wants to withdraw $21.

The software needs to return an error since there is not available money bill to deliver $21.

### Global Requirements

- The challenge can be develop using any programming language.
- No external external service and library needs to be used
- The solution must have a way to execute, CLI, file or any other interaction.
- Tests are always welcome
- Create a README file with instructions on how to run the application and the tests.
