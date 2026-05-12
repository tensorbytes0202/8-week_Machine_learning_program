# 📁 Phase 1 & 2: Python, Data Handling & Statistics (Day 1–10)

Building the foundation for Machine Learning and Artificial Neural Networks.

---

## 🐍 Phase 1: Python Mastery (Day 1–3)

### Day 1: Python Basics & Logic
**Theory:** Python ek high-level language hai jo readability par focus karti hai. Aaj ka goal hai control flow samajhna.
* **Variables:** Data store karne ke containers.
* **Loops:** `for` loop tab use hota hai jab iterations pata hon, `while` jab condition check karni ho.
* **Logic:** `if-elif-else` conditional decision-making ke liye.

**Practice Code: Prime Number Checker**
```python
num = int(input("Enter a number: "))
if num > 1:
    for i in range(2, int(num**0.5) + 1):
        if (num % i) == 0:
            print(f"{num} is not a Prime Number")
            break
    else:
        print(f"{num} is a Prime Number")
else:
    print(f"{num} is not a Prime Number")
