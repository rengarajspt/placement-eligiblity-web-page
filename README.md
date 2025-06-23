# placement eligiblity web-page
## 🎯 Description
               ● Design and implement a Streamlit application where users can input eligibility 
          criteria for placement.Based on these criteria, the application should query a dataset 
          of student information to display eligible candidates' details.
---
## 📑 Features

✅ SQL connection implemented in Python OOP  
✅ Automatic creation and population of 4 tables using `Faker`:
- `students_table`
- `programming_table`
- `soft_skills_table`
- `placements_table`  
✅ Streamlit web app with multiple pages:
1️⃣ **Home Page** — Title and welcome image  
2️⃣ **Filter Page** — Filter data by scores and save a filtered table  
3️⃣ **Filtered Table Insights** — Show 5 SQL insights on filtered data  
4️⃣ **Overall Data Insights** — Show 5 SQL insights on all data

---

## ⚙️ How to Use in Colab

1️⃣ **Open the Colab Notebook**

[Open in Colab](https://colab.research.google.com/drive/1gLJIgXotmfhibBoveSI7qTUPH4HeX_VM)

2️⃣ **Run All Cells**

The notebook:
- Connects to SQLite using OOP
- Creates tables with fake data
- Runs Streamlit from Colab

3️⃣ **Run Streamlit in Colab**

At the end of the notebook, use:
```python
!streamlit run app.py & npx localtunnel --port 8501

