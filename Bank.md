# Bank
Low level design for a simple banking system.

## Problem Statement
Create a simple banking system that allows users to perform the following operations:
1. **Credit**: Add money to their account.
2. **Debit**: Withdraw money from their account.
3. **Check Balance**: View the current balance in their account.
4. **Exit**: End their session or transaction.

### Requirements
- **Transaction Format**: The amount entered by the user will be in the `xD yC` format, where `x` and `y` are amounts and `D` and `C` signify "Dollars" and "Cents" respectively. Examples include `10D 20C`, `10D`, or `20C`. Displayed amounts should also use this format.

### Problem Extension
1. **Multiple Users**: Support transactions for multiple users.
2. **Multiple Currencies**: Handle multiple currencies beyond just dollars and cents.

## Appendix
### Clarification Questions
1. What are the typical transaction limits for credit and debit operations?
2. How should the system handle currency conversion if multiple currencies are involved?
3. What security features are required to protect user accounts and transactions?
4. How will the system ensure data consistency across multiple sessions?
5. Is there a need for real-time transaction processing?

## Solutions
1. Go implementation example: [Simple Banking System in Go](https://github.com/LLDCollection/Go/tree/main/bank)
