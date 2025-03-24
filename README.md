
---

# 📊 **Skill Analysis Research**
This project evaluates **user trading skills** through three statistical analyses:  
1. **Skill Gradient Test** - Examines performance variation across different alpha values.  
2. **Skill Persistence Test** - Evaluates skill retention month over month.  
3. **Learning Curve Test** - Analyzes skill improvement over multiple events.  

---

## 📂 **Dataset Overview**
The project requires the following CSV files:  

| 📁 File Name                  | Description |
|------------------------------|------------|
| `skill_gradient_data.csv`     | Dataset for Skill Gradient Test |
| `skill_persistence_data_2024.csv` | Dataset for Skill Persistence Test |
| `Learning_curve_data.csv`     | Dataset for Learning Curve Test |

> **Note:** Ensure that these files are placed in the **project directory** before running the notebooks.

---



## 📝 **Notebooks**  
The research consists of three **Jupyter Notebooks**:  

| 📘 Notebook Name | Description |
|-----------------|------------|
| `skill_gradient_publish.ipynb` | Performs statistical tests on user performance across different **alpha parameters**. |
| `skill_persistence_publish.ipynb` | Analyzes **month-to-month skill persistence** using Spearman correlation. |
| `learning_curve_publish.ipynb` | Examines **long-term learning trends** using Spearman correlation and Mann-Kendall test. |

---

## ⚙️ **Installation Instructions**
To run the notebooks, install the required dependencies using:  

```sh
pip install -r requirements.txt
