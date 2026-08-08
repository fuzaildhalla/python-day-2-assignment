# Python Day 2 Assignment

This repository contains the **Session 2 Python assignment**, covering basic variables, printing, conditional statements, indentation, and simple IPL match details.

## Contents

1. [Swiggy/Blinkit Order Script](#1-swiggyblinkit-order-script)
2. [Flipkart Delivery Eligibility](#2-flipkart-delivery-eligibility)
3. [IPL Match Variables](#3-ipl-match-variables)

---

## 1. Swiggy/Blinkit Order Script

The first exercise creates variables for a simple order and prints their values.

> Note: The original notebook labels this exercise as **"sweegy order"**, while the code comment describes it as a **Blinkit order script**. The terminology is preserved from the original notebook.

### Code

```python
'''creating a blinkit
order script'''
football_price = 250
delivery_fees = 30
discount_on_coupon = 20

print("football_price", football_price)
print("delivery_fees", delivery_fees)
print("discount on coupon", discount_on_coupon)
```

### Variables

| Variable | Value | Description |
|---|---:|---|
| `football_price` | `250` | Price of the football |
| `delivery_fees` | `30` | Delivery fee |
| `discount_on_coupon` | `20` | Discount from the coupon |

---

## 2. Flipkart Delivery Eligibility

This exercise demonstrates the use of:

- Variables
- `if` statements
- `else` statements
- Indentation
- Comparison operators

### Example 1: Product price is 1200

```python
# Setting up the product price
product_price = 1200

# Checking the delivery eligibility using else, if
if product_price > 1000:
    print("Eligible for free delivery")
else:
    print("Delivery charges apply")
```

Since `1200 > 1000`, the output is:

```text
Eligible for free delivery
```

### Example 2: Product price is 700

```python
product_price = 700

if product_price > 1000:
    print("Eligible for free delivery")
else:
    print("Delivery charges apply")
```

Since `700` is not greater than `1000`, the output is:

```text
Delivery charges apply
```

### Logic

```text
If product price > 1000
    → Eligible for free delivery
Otherwise
    → Delivery charges apply
```

---

## 3. IPL Match Variables

The third exercise demonstrates how to create variables and print details for an IPL match.

The variables used are:

- `team`
- `runs`
- `over_played`

### Code

```python
\"\"\"
printing the ipl match details and defining the variables.
\"\"\"

# values for match
team = "gujrat titans"
runs = 200
over_played = 20.0

print("team:", team)
print("runs", runs)
print("over_played", over_played)

team = "RCB"
runs = 150
over_played = 20.0

print("team:", team)
print("runs", runs)
print("over_played", over_played)

print("gujrat titans won by 50 runs")
```

### Match Details

| Team | Runs | Overs Played |
|---|---:|---:|
| gujrat titans | 200 | 20.0 |
| RCB | 150 | 20.0 |

The notebook concludes with:

```text
gujrat titans won by 50 runs
```

---

## Concepts Covered

This assignment provides practice with the following Python fundamentals:

- **Variables** — storing values such as prices, runs, and team names.
- **Data types** — strings, integers, and floating-point numbers.
- **`print()`** — displaying values and messages.
- **Conditional statements** — using `if` and `else`.
- **Comparison operators** — checking whether a value is greater than another value.
- **Indentation** — defining the code blocks belonging to conditional statements.
- **Variable reassignment** — assigning new values to existing variables.

## Source

Converted from the original **Python Day 2 Jupyter Notebook assignment**.
