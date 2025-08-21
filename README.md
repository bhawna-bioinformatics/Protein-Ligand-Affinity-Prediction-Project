# Protein-Ligand-Affinity-Prediction-Project
📌 Overview

This project uses machine learning to predict protein–ligand binding affinity by extracting features from protein sequences and ligand structures. The workflow integrates bioinformatics feature engineering with statistical modeling for affinity prediction.

⚙️ Workflow

- Data Loading – Import protein–ligand dataset.

- Protein Feature Extraction – Compute amino acid composition.

- Visualization – Heatmap of amino acid distributions.

- Dimensionality Reduction – Apply PCA to protein features.

- Ligand Feature Extraction – Convert SMILES into molecular fingerprints.

- Feature Scaling – Normalize ligand descriptors.

- Feature Combination – Merge protein and ligand features into a single dataset.

- Model Training – Train a Random Forest Regressor to predict binding affinity.

- Evaluation – Calculate MSE, R², and visualize results.

- Residual Analysis – Plot residual scatter and histogram for error distribution.

📊 Results

- Model performance evaluated using Mean Squared Error (MSE) and R² score.

- Scatter plots of Actual vs Predicted Affinity show prediction trends.

- Residual analysis highlights model bias and variance.

🚀 Future Work

- Test additional machine learning models (XGBoost, Neural Networks).

- Incorporate 3D structural features of proteins and ligands.

- Expand dataset size for more robust predictions.

🛠️ Requirements

- Python 3.8+

- RDKit

- NumPy, Pandas

Scikit-learn

Matplotlib, Seaborn
