# Missing Numbers Report - Google Colab Instructions

This program processes an Excel file to identify missing and duplicate numbers with prefixes (if any) from a specified column. Follow the steps below to run this script on **Google Colab**.

## 🚀 How to Run the Program

### 1️⃣ **Copy-Paste Method:**

1. Open [Google Colab](https://colab.research.google.com/).
2. Click on **`New Notebook`**.
3. Copy the entire Python code from the provided script.
4. Paste the code into the first code cell in the notebook.
5. Click **`Run`** (press `Shift + Enter` or click the Play button).
6. Proceed with the **file upload** as instructed below.

### 2️⃣ **Upload Script Method:**

1. Open [Google Colab](https://colab.research.google.com/).
2. Click on **`File` > `Upload Notebook`** if you have saved the script as a `.ipynb` file.
3. Select the notebook file containing the script.
4. Click **`Run All`** to execute all code cells.
5. Proceed with the **file upload** as instructed below.

---

## 📥 Uploading an Excel File

1. After running the script, you'll see a prompt:
   
   `📂 Please upload an Excel file (.xlsx) to check for missing numbers in 'Sheet1'.`

2. Click the **`Browse`** button to upload your `.xlsx` file.
3. Make sure the file has data in **Sheet1** and the relevant numbers are in the **first column (Column A)**.

---

## 📊 Output Report

- The script processes the uploaded file and:
  - Detects **missing numbers** and **duplicates**.
  - Maintains prefixes where present (e.g., `BK101`, `ID202`).
  - Displays a detailed report in the output console.

- It generates an Excel report named:

   **`missing_numbers_report.xlsx`**

- The file will be automatically downloaded after processing.

---

## ⚠️ Troubleshooting

- **Error: `Error processing file`**
  - Ensure the uploaded file is in `.xlsx` format.
  - Check that **Sheet1** exists and contains numeric data in Column A.

- **Missing Data in Output**
  - Verify that prefixes are consistent.
  - Make sure there are no empty rows in the dataset.

---

## 📩 Contact

For issues or questions regarding this script, feel free to reach out to the author or raise an issue in your project repository.
