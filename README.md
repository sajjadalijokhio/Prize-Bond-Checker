# 🏦 Prize Bond Withdraw Checker

A simple **web app** (pure HTML + JS) to check if your prize bonds matched in any draw.  
Runs fully offline — just open `index.html` in your browser.

---

## 📂 Input File Structures

### 1. Draw Bonds File
Must have these columns:

| Prize Bond Number | Draw Year | Draw Quarter | Prize Number |
|--------------------|-----------|--------------|--------------|
| 391209             | 2020      | 4th          | 3rd          |
| 682943             | 2021      | 3rd          | 1st          |
| 445247             | 2016      | 2nd          | 2nd          |
| 033462             | 2021      | 1st          | 3rd          |

---

### 2. My Bonds File
Must have **one column only**:

| Prize Bond Number |
|--------------------|
| P391209           |
| AJ682943          |
| W445247           |
| AT033462          |

👉 Non-digit characters (like `P`, `AJ`, `AT`) are ignored. Example: `AT033462` → `033462`.

---

## 🚀 How to Use
1. Open `index.html` in your browser.  
2. Upload both Excel files.  
3. Click **Check Matches** → results appear in a table.  
4. Download results as Excel.  
