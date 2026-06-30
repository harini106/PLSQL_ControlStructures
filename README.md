# PL/SQL Control Structures

## Overview

This project demonstrates the use of **PL/SQL Control Structures** through three banking scenarios:

1. Applying a 1% discount to loan interest rates for customers above 60 years of age.
2. Promoting customers to VIP status based on their account balance.
3. Sending reminders to customers whose loans are due within the next 30 days.

These examples use **CURSOR**, **FOR LOOP**, **IF-THEN**, **UPDATE**, and **DBMS_OUTPUT.PUT_LINE** statements.

---

## Project Structure

```
PLSQL_ControlStructures/
│── Scenario1_DiscountInterest.sql
│── Scenario2_VIPPromotion.sql
│── Scenario3_LoanReminder.sql
└── README.md
```

---

## Scenario 1: Loan Interest Discount

### Objective

Apply a **1% discount** to the loan interest rate for customers whose age is greater than **60 years**.

### Concepts Used

- CURSOR
- FOR LOOP
- IF Statement
- UPDATE
- COMMIT

---

## Scenario 2: VIP Customer Promotion

### Objective

Update the **IsVIP** flag to **TRUE** for customers whose account balance exceeds **$10,000**.

### Concepts Used

- CURSOR
- IF Statement
- UPDATE
- COMMIT

---

## Scenario 3: Loan Due Reminder

### Objective

Fetch all loans due within the next **30 days** and display reminder messages using `DBMS_OUTPUT.PUT_LINE`.

### Concepts Used

- CURSOR
- Date Functions
- FOR LOOP
- DBMS_OUTPUT

---

## Prerequisites

- Oracle Database
- Oracle SQL Developer
- Customers table
- Loans table

---

## How to Execute

Open each `.sql` file in Oracle SQL Developer and run it.

Example:

```sql
@Scenario1_DiscountInterest.sql
```

Repeat for:

```sql
@Scenario2_VIPPromotion.sql
```

```sql
@Scenario3_LoanReminder.sql
```

---

## SQL Concepts Covered

- PL/SQL Blocks
- Variables
- CURSOR
- FOR LOOP
- IF-THEN Condition
- UPDATE Statement
- COMMIT
- DBMS_OUTPUT.PUT_LINE
- Date Operations

---

## Learning Outcome

After completing this project, you will be able to:

- Write PL/SQL blocks.
- Use loops and conditional statements.
- Work with cursors.
- Update records in database tables.
- Display output using `DBMS_OUTPUT`.
- Apply PL/SQL concepts to real-world banking scenarios.

---

## Author

**Harini**
