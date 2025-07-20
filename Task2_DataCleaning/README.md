# 🧹 Task 2 - Data Cleaning

## 📁 Folder: Task2_DataCleaning

### 📌 Objective:
The goal of this task is to clean and preprocess a raw product dataset (`products_raw.csv`) by identifying and handling missing values, removing duplicates, and making the data consistent and ready for analysis.

---

### 📊 Raw Dataset Overview:
**Filename:** `products_raw.csv`  
**Columns:**
- `ProductID`
- `ProductName`
- `Category`
- `Price`
- `Stock`

**Issues in the Raw Dataset:**
- Missing values in `ProductName`, `Category`, `Price`, and `Stock`
- Duplicate rows

---

### 🔧 Cleaning Steps Performed:
- Removed duplicate entries
- Replaced missing `ProductName` with **"Unknown Product"**
- Replaced missing `Category` with **"Misc"**
- Replaced missing `Price` with **mean value of Price**
- Replaced missing `Stock` with **0**

---

### ✅ Cleaned Dataset:
**Filename:** `products_cleaned.csv`  
The cleaned dataset is now free of duplicates and missing values, and is ready for analysis.

---

### 💻 Notebook Used:
**Filename:** `Task2_DataCleaning.ipynb`  
This notebook includes all code for:
- Uploading and loading the raw CSV
- Cleaning operations
- Exporting the cleaned CSV

---

### 📎 Files Included:
- `products_raw.csv`
- `products_cleaned.csv`
- `Task2_DataCleaning.ipynb`
- `README.md`

---

### 👩‍💻 Submitted by:
**Srishti Aggarwal**  
SkillCraft Technology – Data Science Internship  
Task 2 of `SCT_DS_Internship2025`
