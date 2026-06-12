# g66_pca_assignment
# Formative Assignment: Advanced Linear Algebra (PCA)

Implementation of Principal Component Analysis (PCA) from scratch using NumPy,
applied to an Africanized dataset on malaria and population indicators across
54 African countries (2007–2017).

## Group Members

Kethia Kayigire Ngabire, Elyse Ishimwe

## Dataset

**Source:** [Malaria in Africa — Kaggle](https://www.kaggle.com/datasets/lydia70/malaria-in-africa)
(World Bank data)

**File:** `DatasetAfricaMalaria.csv`

- 594 rows (54 African countries x 11 years, 2007–2017)
- 27 columns total
- Non-numeric columns: `Country Name`, `Country Code`, `geometry` (identified,
  explained, and excluded before PCA)
- Contains real missing values (NaN) originating from the World Bank source,
  handled via mean imputation

## Repository Structure

```
.
├── README.md
├── DatasetAfricaMalaria.csv          # dataset (must be in same folder as notebook)
├── PCA_Formative_1[66].ipynb         # main PCA implementation notebook
├── Group_Contribution_Tracker.xlsx   # task allocation & meeting log
└── combined_submission.pdf           # notebook PDF + contribution sheet PDF
```

## How to Run

### Option 1: Google Colab
1. Open `PCA_Formative_1[66].ipynb` in Colab
2. Click the folder icon in the left sidebar and upload `DatasetAfricaMalaria.csv`
3. Run all cells (**Runtime → Run all**)

### Option 2: Locally / Jupyter
1. Place `PCA_Formative_1[66].ipynb` and `DatasetAfricaMalaria.csv` in the same folder
2. Install dependencies: `pip install numpy pandas matplotlib jupyter`
3. Run: `jupyter notebook Filled_PCA_Notebook.ipynb`
4. Run all cells

## Requirements

- Python 3.x
- `numpy`
- `pandas`
- `matplotlib`
