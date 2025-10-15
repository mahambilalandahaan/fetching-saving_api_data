# 🌍 Week 8.5 – API Fundamentals  
## 📆 Day 8 – Working with API Data  

---

### 🎯 **Learning Objectives**
- Understand **query parameters** in REST APIs  
- Handle **HTTP status codes** and basic error messages  
- Combine multiple API responses into one dataset  
- Convert JSON data into a **pandas DataFrame**  
- Save results as **CSV** and **JSON** files  
- Present data neatly in tabular format  

---

### 🧩 **Concepts Covered**

| Concept | Description |
|:--------|:-------------|
| 🌐 API Endpoint | The main URL where requests are sent |
| 🔢 Query Parameters | Key-value pairs to filter or modify requests (`?postId=1`) |
| ⚙️ Status Codes | `200 = OK`, `404 = Not Found`, `500 = Server Error` |
| 🧱 JSON Parsing | Convert structured text data into usable Python objects |
| 📊 DataFrame Conversion | Create tabular data for analysis |
| 💾 File Export | Save your results locally for future projects |

---

### 📂 **Generated Files**

| File Name | Type | Description |
|:-----------|:------|:-------------|
| `api_day8_fetch_save.py` | Python Script | Contains the complete code for data fetching & saving |
| `all_comments.csv` | CSV File | Combined comments dataset (for Excel or pandas) |
| `all_comments.json` | JSON File | Machine-readable structured dataset |

---

### 📊 **Sample Output Table**

| postId | id | name | email |
|:--:|:--:|:--|:--|
| 1 | 1 | id labore ex et quam laborum | Eliseo@gardner.biz |
| 1 | 2 | quo vero reiciendis velit similique earum | Jayne_Kuhic@sydney.com |
| 2 | 6 | et fugit eligendi deleniti quidem qui sint nihil autem | Pres.ahmad@domain.com |
| 3 | 11 | vero eaque aliquid doloribus et culpa | Hayden@althea.biz |

---

### 🧠 **Key Takeaways**
- Using `params` allows **dynamic filtering** when calling APIs.  
- Always verify `response.status_code == 200` before processing data.  
- The `.extend()` method helps combine multiple lists of results efficiently.  
- Saving both `.csv` and `.json` ensures **data compatibility** across tools.  
- Proper documentation and summaries make your project **portfolio-ready**.  

---

### 🏁 **Day 8 Completed Successfully!**
✅ Data fetched and combined  
✅ Error handling verified  
✅ Results saved in CSV & JSON  
✅ Output inspected and summarized  

You are now ready to move forward to:

> 🚀 **Day 9 – Calling a Model API (AI Text Generation)**  
> Learn to call text-generation APIs, store responses in JSON, and format them for readability.

---

**👩‍💻 Author:** *Madiha Atif*  
**📘 Project:** API Fundamentals – Day 8  
**🏆 Status:** ✅ Completed Successfully  
