# 🧠 Product Dataset Analysis

## **📌 About**
Dataset of product descriptions for practicing **data analysis** and **NLP tasks**.

---

## **Structure**
- `products_200.json` — dataset  
- `README.md` — project description  

---

## **Dataset**
- 200 records  
- Fields:
  - `id` — product ID  
  - `description` — text description  

---

## **Tech**
- Python 3  
- JSON  
- Pandas (optional)

---

## **Usage**
```python
import json

with open('products_200.json', 'r', encoding='utf-8') as f:
    data = json.load(f)

print(len(data))
