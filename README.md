# News Article Categorization and Movie Ratings Analysis

A BBC News article categorization project

Created by Lucas Little.

## Project Structure

```
project/
├── notebooks/
│   ├── 1_data_exploration.ipynb
│   ├── 2_matrix_factorization.ipynb
│   ├── 3_supervised_learning.ipynb
├── data/
│   ├── BBC News Sample Solution.csv
│   ├── BBC News Test.csv
│   ├── BBC News Train.csv
│   ├── submission_best_single.csv
│   ├── submission_ensemble.csv
│   └── submission.csv
├── requirements.txt
└── README.md
```

## Movie Ratings Analysis (4_movie_ratings.ipynb)

### Implementation [10 points]
- Loads and analyzes movie ratings data from HW3
- Applies sklearn's NMF for prediction
- Calculates and visualizes RMSE across different components
- Documents performance results with clear visualizations

### Analysis & Discussion [10 points]
- Compares results with baseline methods (global mean, user mean, item mean)
- Compares with similarity-based approaches (user-user, item-item)
- Explains performance limitations:
  - Data sparsity issues
  - Linear assumptions
  - Cold start problem
  - Implementation limitations
- Proposes specific improvements:
  - Data preprocessing enhancements
  - Advanced techniques
  - Hybrid approaches
  - Alternative implementations

## Required Packages
See requirements.txt for complete list of dependencies.

Core packages include:
```
numpy
pandas
scikit-learn
matplotlib
seaborn
jupyter
```

## How to Run This Project

1. Clone the repository:
```bash
git clone https://github.com/lukelittle/csca5632-news-article-categorization.git
cd csca5632-news-article-categorization
```

2. Install dependencies:
```bash
pip install -r requirements.txt
```

3. Run the notebooks:
- Open Jupyter and navigate to the notebooks directory
- Run notebooks in numerical order (1-4)

## Deliverable Requirements
1. Well-organized Jupyter notebooks with clear sections
2. Comprehensive code comments
3. Thorough analysis and findings
4. Properly labeled visualizations
5. References included where appropriate

## Project Author
Lucas Little
