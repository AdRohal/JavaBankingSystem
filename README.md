# Java Banking System

This Java project implements a basic banking system with different account types, including Basic Account (`CompteB`), Paying Account (`CompteP`), and Interest-bearing Account (`CompteE`). The `TestCompte` class serves as a demonstration of key account functionalities.

## Account Types

### 1. Basic Account (`CompteB`)

- Simple account with deposit and withdrawal capabilities.
- Tracks account code, balance, and total number of accounts.

### 2. Paying Account (`CompteP`)

- Inherits from `CompteB` with additional fee deduction on deposits.
- Ideal for accounts with payment features. 

### 3. Interest-bearing Account (`CompteE`)

- Inherits from `CompteB` with an added interest calculation feature.
- Suitable for accounts that earn interest over time.

## Usage

To test the functionality of the banking system, run the `TestCompte` class. It demonstrates the usage of different account types, showcasing deposit, withdrawal, and interest calculation operations.

```java
public class TestCompte {
    public static void main(String[] args) throws Exception {
        // Test account operations here
        // ...
    }
}
