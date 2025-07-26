
# 🎮 PS4 Game Analysis Tool (Python Project)

This Python project is an interactive data analysis tool built to explore and visualize a dataset of **famous PS4 games**. Using a CSV file containing game titles, prices, lifetime sales, and more, the program allows users to view statistics, manipulate data, search records, and generate visualizations.

---

## 📁 Features

- 📊 **View the full dataset** in a clean tabular format  
- 📈 **Statistical summaries**: shape, size, columns, data types, and more  
- 🔍 **Search specific games or details** by row or column  
- ➕ Add new columns or 🗑️ temporarily remove existing ones  
- 🧮 Display top/bottom `n` records  
- 📉 **Data visualizations** including:
  - Line charts for prices & sales  
  - Vertical and horizontal bar charts

---

## 📂 Dataset

Make sure you have a CSV file named `GameData.csv` which includes details of PS4 games. Example columns expected:
- `Games`
- `Price`
- `Lifetime Sales`

---

## 🚀 How to Run

1. Clone this repo or download the Python file.
2. Ensure the CSV file `GameData.csv` is in the correct path or directory.
3. Run the script:
   ```bash
   python "Ps4 game analysis project.py"
   ```
4. Follow the interactive menu in the terminal.

---

## 📸 Sample Visuals

- Line chart of price trends  
- Lifetime sales bar charts  
- Interactive data inspection from console

---

## 🛠️ Requirements

- Python 3.x  
- `pandas`  
- `matplotlib`

Install required libraries:
```bash
pip install pandas matplotlib
```

---

## 💡 Notes

- The script uses a **menu-driven approach** for user interaction in the terminal.
- Data manipulations like column deletions are temporary during runtime.

---

## 🧑‍💻 Author

**Darsh**  
A simple Python data analysis project to explore the gaming world of PS4 titles.
