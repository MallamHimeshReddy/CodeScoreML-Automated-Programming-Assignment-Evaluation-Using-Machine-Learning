# CodeScoreML

## Effective Structured Code Representation Through Intelligent Chunking for Automated Programming Assessment

CodeScoreML is a machine learning framework designed to improve automated programming assignment evaluation through effective structured code representation. Instead of processing entire source code files as a single input, the framework intelligently divides programs into meaningful code chunks, extracts semantic embeddings using transformer-based models, and predicts programming assignment scores using regression algorithms.

The project investigates how different code representation strategies affect prediction performance and demonstrates that structured representations generated through intelligent chunking can significantly improve automated code assessment.

---

## Project Objectives

- Develop an automated programming assignment evaluation framework.
- Transform source code into effective structured representations.
- Generate semantic embeddings from code chunks.
- Compare different code representation strategies.
- Train and evaluate multiple machine learning regression models.
- Analyze the impact of structured code representation on prediction accuracy.

---

## Project Architecture

```
Source Code
     │
     ▼
Code Preprocessing
     │
     ▼
Intelligent Code Chunking
     │
     ▼
Structured Code Representation
     │
     ▼
CodeBERT Tokenization & Embeddings
     │
     ▼
Feature Processing (PCA)
     │
     ▼
Regression Models
     │
     ▼
Programming Score Prediction
     │
     ▼
Performance Evaluation
```

---

## Repository Structure

```
CodeScoreML/

├── 3testcase_trial.ipynb
│   ├── CatBoost regression experiments
│   ├── Score prediction
│   └── Model evaluation
│
├── Token_Comparison_3testcases.ipynb
│   ├── Code tokenization
│   ├── Chunk comparison
│   └── Token analysis
│
├── Rregressio_on_both.ipynb
│   ├── Multiple regression models
│   ├── PCA experiments
│   └── Performance comparison
│
├── ML_END(Y_Pred(actual,1,2,3).ipynb
│   ├── Final prediction pipeline
│   ├── Model evaluation
│   └── Prediction visualization
│
├── Partial_Output (2).ipynb
│   ├── Initial experiments
│   └── Baseline implementation
│
└── README.md
```

---

## Key Features

- Intelligent source code chunking
- Structured code representation
- Semantic feature extraction
- CodeBERT-based embeddings
- Token-level comparison
- Feature dimensionality reduction using PCA
- Multiple regression algorithms
- Programming assignment score prediction
- Comparative performance evaluation

---

## Technologies Used

### Programming Language

- Python 3.x

### Machine Learning

- Scikit-learn
- CatBoost
- XGBoost

### Deep Learning

- Hugging Face Transformers
- CodeBERT

### Data Processing

- Pandas
- NumPy
- OpenPyXL

### Visualization

- Matplotlib
- Seaborn

### Development Environment

- Google Colab
- Jupyter Notebook

---

## Methodology

### 1. Source Code Collection

Programming assignments are collected and organized into datasets containing source code and corresponding evaluation scores.

---

### 2. Code Preprocessing

The source code is cleaned and normalized to remove unnecessary formatting while preserving program semantics.

---

### 3. Intelligent Code Chunking

Instead of treating the entire program as a single input, the framework divides the source code into meaningful logical chunks. This structured representation captures semantic relationships more effectively than conventional whole-code representations.

---

### 4. Structured Code Representation

Each code chunk forms part of a structured representation of the complete program, enabling the model to better understand programming logic and contextual relationships.

---

### 5. Semantic Embedding Generation

Each structured code chunk is processed using CodeBERT to generate dense semantic embeddings representing programming constructs.

---

### 6. Feature Engineering

The extracted embeddings are processed using Principal Component Analysis (PCA) to reduce dimensionality while preserving important semantic information.

---

### 7. Machine Learning

Several regression algorithms are trained on the generated feature vectors to predict programming assignment scores.

The implemented models include:

- CatBoost Regressor
- XGBoost Regressor
- Random Forest Regressor
- Linear Regression
- Ridge Regression
- Support Vector Regression (SVR)

---

### 8. Performance Evaluation

The models are evaluated using standard regression metrics and compared across different code representation strategies.

---

## Workflow

1. Load programming assignment source code.
2. Preprocess the source code.
3. Perform intelligent code chunking.
4. Generate structured code representations.
5. Extract semantic embeddings using CodeBERT.
6. Apply PCA for dimensionality reduction.
7. Train regression models.
8. Predict programming assignment scores.
9. Evaluate model performance.
10. Compare different code representation approaches.

---

## Evaluation Metrics

The project uses the following regression metrics:

- R² Score
- Mean Squared Error (MSE)
- Mean Absolute Error (MAE)
- Root Mean Squared Error (RMSE)

These metrics help evaluate the effectiveness of different structured code representation strategies.

---

## Installation

Clone the repository.

```bash
git clone https://github.com/yourusername/CodeScoreML.git
```

Move into the project directory.

```bash
cd CodeScoreML
```

Install the required dependencies.

```bash
pip install pandas numpy matplotlib seaborn scikit-learn catboost xgboost transformers openpyxl
```

---

## Running the Project

Open the notebooks using Jupyter Notebook or Google Colab.

Run the notebooks sequentially:

1. Data preprocessing
2. Token comparison
3. Embedding generation
4. PCA processing
5. Model training
6. Prediction
7. Performance evaluation

---

## Dataset

The project expects datasets containing:

- Programming assignment source code
- Code embeddings
- Chunked code embeddings
- Target programming scores

Update the dataset paths inside each notebook before execution.

---

## Experimental Analysis

The project compares multiple code representation techniques, including:

- Whole source code representation
- Structured code representation
- Intelligent code chunking
- Token-level representations

Their effectiveness is analyzed using multiple regression models to determine the most suitable representation for automated programming assessment.

---

## Future Work

- AST-based semantic chunking
- Control Flow Graph (CFG) representations
- Program Dependency Graph (PDG) integration
- Graph Neural Networks
- Fine-tuned CodeBERT embeddings
- Large Language Model-based code representations
- Explainable AI for programming assessment
- Multi-language programming support
- Large-scale benchmark evaluation

---

## Applications

- Automated programming assignment grading
- Educational technology platforms
- Intelligent tutoring systems
- Online coding assessment platforms
- Programming skill evaluation
- Academic performance prediction

---

## Author

**Mallam Himesh Reddy**

Bachelor of Technology  
Computer Science and Engineering (Artificial Intelligence)

---

## License

This project is developed for academic and research purposes.

---

## Acknowledgements

This work utilizes transformer-based code representations, machine learning regression models, and semantic code analysis techniques to investigate effective structured code representation for automated programming assessment.
