# 🤹‍♂️ Combining Conditions in Python `if` Statements

Sometimes one condition isn’t enough. Python lets you combine multiple checks using `and`, `or`, and `not` inside your `if` statements.

---

## 💡 What You'll Learn

* How to combine conditions with `and`, `or`, and `not`
* How to group logic using parentheses
* How to build smarter decision-making in Python

---

## 🧠 When to Use

* `and` — if **both** conditions must be True
* `or` — if **at least one** condition should be True
* `not` — to **reverse** a condition (True ↔ False)

---

## 💻 Example with Explanation

```python
age = 20
logged_in = False

if age >= 18 and not logged_in:
    print("Create an account")
```

### 🔈 Output

```
Create an account
```

✅ This checks **two conditions**:

1. Age is at least 18 ✅
2. User is not logged in ✅

Both must be True for the code to run.

---

## 📌 Key Notes

* Use parentheses `()` to group logic when needed
* Don’t forget: `not` flips a condition
* Always define variables **before** your `if`
* These combine well with `elif` for multiple layers of logic

---

## 🧪 Try It Yourself

```python
points = 120
is_premium = True

if points > 100 or is_premium:
    print("You get a reward!")
```

### 🔈 Expected Output

```
You get a reward!
```

---

🐍 This is part of the **Pythonly** beginner series.
Learn Python one line at a time. Follow **@Pythonly** for more.

---


