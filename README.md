# Protein Classification Using Sequence and Structure Information

## Overview
This repository includes additional materials not covered in our paper, such as code on Exploratory Data Analysis(EDA), description on processed datasets, and results for protein classification using primary sequence and secondary structure information. We evaluate machine learning (ML) and deep learning (DL) models to assess whether structural features enhance classification accuracy and biological interpretability.

## Features
- Uses TF-IDF and embedding-based feature extraction for protein sequences
- Employs ML and DL models (Random Forest, SVM, XGBoost, LSTM, Bi-LSTM, GRU)
- Compares classification accuracy of primary sequence, secondary structure, and combined features
- Includes SHAP analysis for feature importance and biological insights
- Provides datasets and results for further analysis

## Repository Structure
```
📂 data/         # Processed datasets (not included due to size)
📂 results/      # Accuracy reports, SHAP visualizations, additional tables
📂 src/          # Core scripts for feature extraction, training, and evaluation
📂 docs/         # Additional references and documentation
📄 .gitignore    # Files to be ignored in version control
📄 README.md     # Project documentation
```

## Results Summary
- **Best classifier:** Random Forest with TF-IDF (92% accuracy on primary sequences)
- **Secondary structure contribution:** Marginal improvement but enhances interpretability
- **Top-performing classes:** Oxidoreductase, Ribosome, Virus (99% accuracy)
- **SHAP Insights:** Secondary structure features provide complementary information

## Future Directions
- Extend analysis to more diverse protein classes
- Better representation of structure sequence
- Investigate disease mechanisms by analyzing sequence-structure changes in relation to protein function prediction

## Contributors
- Preveena K V
- Supervisor: Dr. Manu Madhavan

## Contact
For queries, please email: preveenavenugopal@gmail.com
