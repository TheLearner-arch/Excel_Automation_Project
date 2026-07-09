# ⚡ Data Cleaning & Reporting Automation (E‑commerce Dataset)

✨ Internship Task — Automated workflow across 12 months of sales data using **Excel, Python, and Power Query**, with a final dashboard for reporting.

---

## 𝄜 Final Dashboard Excel File
This is my excel file containting the dashboard [Ecommerce DashBoard.xlsx](https://github.com/user-attachments/files/29235151/Ecommerce.DashBoard.xlsx)

---

## Steps of reaching the final dashboard

---

## 🌀 Step 1: Messy Dataset
**BLANK ROWS**
<img width="1030" height="470" alt="Gish" src="https://github.com/user-attachments/assets/3d34f097-a31d-4ed5-9f5a-40e6ca6bcf67" />

---

**DUPLICATE ROWS WITH STRING VALUES**

<img width="1034" height="132" alt="Blank1" src="https://github.com/user-attachments/assets/9a034aa4-4b99-4a2f-911d-2714199a9d26" />

---

<img width="1032" height="132" alt="Blank2" src="https://github.com/user-attachments/assets/211cb0c0-2b4e-402b-a77d-a4ffe351924e" />

---

**INCONSISTENT DATE/TIME FORMAT(STRING+DATE/TIME MIXED)**
<img width="706" height="420" alt="DateTime" src="https://github.com/user-attachments/assets/3104e026-7858-4c5d-8ffc-e9a1d61068fb" />

Raw monthly sales files contained **duplicates, blanks, and inconsistent date/time formats**.  
This was the starting point of the project.

---

## 🐍 Step 2: Python Automation
![Python Kaggle GIF](link-to-your-gif)

The `Order Date` column had mixed formats:  
- Some stored as strings  
- Some in US date format (MM‑DD‑YYYY)  
- Needed conversion to **Indian Date/Time (DD‑MM‑YYYY HH:MM:SS)**  

Python scripts standardized all values automatically, ensuring consistency across months.

---

## 🔄 Step 3: Power Query Automation
![Power Query GIF](link-to-your-gif)

Initially, the dataset was missing December → fewer rows in the combined table.  
By simply **adding December’s file into the source folder** and refreshing, Power Query automatically updated the dataset with new rows.  
No manual linking required.

---

## 📊 Step 4: Dashboard Before & After
**Before December added:**  
![Dashboard Before GIF](link-to-your-gif)

**After December added:**  
![Dashboard After GIF](link-to-your-gif)

The dashboard updated seamlessly with new totals, KPIs, and charts — proving the workflow was fully automated.

---

## 🧠 Learning Outcomes
- Handling messy datasets with blanks & duplicates  
- Automating date/time conversion using Python  
- Power Query folder connection for monthly file automation  
- Building dashboards as the final reporting layer  

---

## 🔗 Links
- [Final Dataset Excel File](link-to-your-file)  
- [GitHub Repository](link-to-your-repo)  
