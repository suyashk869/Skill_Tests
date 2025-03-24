
---

# 📊 **Skill Analysis Research**
This project evaluates **user trading skills** through three statistical analyses:  
1. **Gradient Test** - Examines performance variation across different alpha values.  
2. **Dilution Test** - Evaluates skill retention month over month.  
3. **Learning Test** - Analyzes skill improvement over multiple events.  

---

## 📂 **Dataset Overview**
The project requires the following CSV files:  

| 📁 File Name                  | Description |
|------------------------------|------------|
| `probo_1.csv`     | Dataset for Dilution Test |
| `probo_2.csv` | Dataset for Persistence Test |
| `probo_3.csv`     | Dataset for Learning Test |

> **Note:** Ensure that these files are placed in the **project directory** before running the notebooks.

---



## 📝 **Notebooks**  
The research consists of three **Jupyter Notebooks**:  

| 📘 Notebook Name | Description |
|-----------------|------------|
| `dilution.ipynb` | Performs statistical tests on user performance across different **alpha parameters**. |
| `persistence.ipynb` | Analyzes **month-to-month skill persistence** using Spearman correlation. |
| `learning.ipynb` | Examines **long-term learning trends** using Spearman correlation and Mann-Kendall test. |

---

## ⚙️ **Installation Instructions**
To run the notebooks, install the required dependencies using:  

```sh
pip install -r requirements.txt
