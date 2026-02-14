# Conditional Statements in Python — If | Elif | Else

## Theory — Decision Making in Python

Conditional statements are used to control the flow of execution in a program based on specific conditions.

In Python, conditions evaluate to either:

- True
- False

Depending on the result, different blocks of code execute. This enables programs to make logical decisions similar to real-world scenarios.

## Types of Conditional Statements

### 1) `if`

Executes a block only when the condition is true.

```python
if condition:
    statement
```

### 2) `if–else`

Executes one block if the condition is true and another if false.

```python
if condition:
    statement_1
else:
    statement_2
```

### 3) `if–elif–else` Ladder

Used when multiple conditions need to be checked sequentially.

```python
if condition1:
    statement
elif condition2:
    statement
else:
    statement
```

Only the first true condition executes.

### 4) Nested `if`

An `if` inside another `if` for multi-level validation.

---

##  Logical Operators

| Operator | Function |
|---------|-----------|
| `and` | True if both conditions are true |
| `or` | True if at least one is true |
| `not` | Reverses the result |


##  Comparison Operators

| Operator | Meaning |
|---------|----------|
| `>` | Greater than |
| `<` | Less than |
| `>=` | Greater than or equal |
| `<=` | Less than or equal |
| `==` | Equal to |
| `!=` | Not equal to |

These operators form the foundation of all conditional expressions.


## Program Logic (1–10)


## 1. Positive or Negative Number

**Logic:**

- Input a number  
- If number > 0 → Positive  
- Else → Negative  

## 2. Positive / Negative / Zero

**Logic:**

- Input a number  
- If number > 0 → Positive  
- Else if number < 0 → Negative  
- Else → Zero  

## 3. Odd or Even

**Logic:**

- Input a number  
- If number divisible by 2 → Even  
- Else → Odd  

## 4. Largest of Two Numbers

**Logic:**

- Input two numbers  
- Compare both  
- Greater number is the largest  

## 5. Largest of Three Numbers

**Logic:**

- Input three numbers  
- If first > second AND third → First largest  
- Else if second > first AND third → Second largest  
- Else → Third largest  

## 6. Grade & Average Calculation

**Logic:**

- Input marks of 5 subjects  
- Calculate average  
- Assign grade using ranges:

| Average Range | Grade |
|---------------|--------|
| ≥ 95 | A+ |
| ≥ 90 | A |
| ≥ 80 | B+ |
| ≥ 70 | B |
| ≥ 60 | C+ |
| < 60 | Fail |

## 7. Leap Year Check

**Logic:**

- Input a year  
- If divisible by 4 AND not divisible by 100  
  OR divisible by 400 → Leap Year  
- Else → Not Leap Year  

## 8. Date Validation & Increment

**Logic:**

- Input date (DD, MM, YYYY)  
- Validate month (1–12)  
- Validate day based on month & leap year  
- If valid:

  - If last day of month → Day = 1, Month + 1  
  - If Month > 12 → Month = 1, Year + 1  

- Else → Invalid Date  

## 9. Gross Salary Calculation

**Logic:**

- Input Basic Salary  
- Apply slabs:

| Basic Salary | HRA | DA |
|--------------|-----|----|
| ≤ 10,000 | 20% | 80% |
| ≤ 20,000 | 25% | 90% |
| > 20,000 | 30% | 95% |

- Compute:

```
Gross Salary = Basic + HRA + DA
```

## 10. Income Tax Calculation

**Logic:**

- Input annual income  
- Apply tax slabs:

| Income Range | Tax Rate |
|--------------|-----------|
| ≤ ₹2,50,000 | 0% |
| ≤ ₹5,00,000 | 5% |
| ≤ ₹10,00,000 | 20% |
| > ₹10,00,000 | 30% |

- Calculate total tax payable  

---

## Conclusion :

Conditional statements form the backbone of decision-making in Python programming. Through the use of `if`, `elif`, and `else`, programs can evaluate conditions and execute logic dynamically.

This experiment demonstrates how conditional structures are applied to solve practical problems such as number analysis, grading systems, leap year detection, salary computation, tax calculation, and date validation. Mastery of these constructs builds a strong foundation for advanced programming and real-world software development.
