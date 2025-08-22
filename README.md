import pypandoc

# README content
readme_text = """# Electricity Bill Splitter for Shared Rooms  

This is a simple Python script that helps split an **electricity bill** among roommates who stayed in the room for different numbers of days. Instead of dividing the bill equally, each roommate pays **based on their stay duration**.  

---

## 📌 Features  
- Accepts roommate details (name and days stayed).  
- Calculates each person’s fair share of the bill.  
- Works for any number of roommates.  
- Outputs a clear breakdown of the cost distribution.  

---

## 🛠️ Example Usage  

### Input:
```python
roommates = [
    {"name": "Alice", "days": 30},
    {"name": "Bob", "days": 20},
    {"name": "Charlie", "days": 10}
]

total_bill = 1800
