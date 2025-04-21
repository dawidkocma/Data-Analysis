# LEGO Data Analysis

## 📌 Overview
This project analyzes historical trends in LEGO sets using **Pandas** and **Matplotlib**. It explores:
- Annual growth in LEGO set releases  
- Expansion of unique themes  
- Rising complexity (average parts per set)  
- Top themes by set count  
- Color palette usage (including translucent pieces)  

## 📸 Snapshot
![LEGO Sets per Year](https://i.imgur.com/Sg4lcjx.png)

## 📊 Data Source
All data is stored as CSV files in the `data/` folder.  
- **`colors.csv`** – LEGO color definitions (name, RGB values, `is_trans` flag)  
- **`themes.csv`** – Theme IDs and names  
- **`sets.csv`** – Set metadata: set number, year, number of parts, theme ID  

## 📂 Repository Structure
```
📦 lego-data-analysis
├── 📂 data
│   ├── colors.csv
│   ├── themes.csv
│   └── sets.csv
├── 📂 notebooks
│   └── lego_analysis.ipynb   # Jupyter Notebook for analysis
└── 📜 README.md              # Project documentation
```

## 🛠 Libraries Used
- `pandas`            – data loading & manipulation  
- `matplotlib.pyplot` – static plotting & visualization  

## ⚡ Getting Started

### Prerequisites
- Python 3.8+  
- Jupyter Notebook  

### Running the Notebook
```sh
git clone https://github.com/your-username/lego-data-analysis.git
cd lego-data-analysis
jupyter notebook notebooks/lego_analysis.ipynb
```

## 📜 License
This project is licensed under the **MIT License**. See [LICENSE](LICENSE) for details.
