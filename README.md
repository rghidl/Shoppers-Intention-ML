#  Machine Learning Project: Online Shoppers Purchasing Intention

This repository contains the end-to-end Machine Learning pipeline and deliverables , predicting e-commerce consumer purchasing intent.

---

## Project Structure

```text
Shoppers-Intention-ML/
├── .gitignore
├── README.md
├── data/
│   ├── online_shoppers_cleaned.csv
│   ├── stage2_results_summary.csv          # CV / validation / test metrics
│   └── splits/                              # train.csv, val.csv, test.csv (70/15/15, stratified)
├── models/
│   ├── random_forest_tuned.joblib
│   └── svm_tuned.joblib
├── notebooks/
│   ├── stage1_eda_preprocessing.ipynb     
│   ├── stage2_splitting_traditional_ml.ipynb   # splitting, RF & SVM tuning, cross-validation
│   ├── 
│   └──   
├── plots/
│   ├── fig1_target_distribution.png
│   ├── fig2_correlation_matrix.png
│   ├── fig3_web_metrics_vs_revenue.png
│   ├── fig4_visitor_conversion.png
│   ├── fig5_feature_importance.png
│   ├── fig6_svm_gridsearch_heatmap.png
│   ├── fig7_cv_boxplot.png
│   ├── fig8_confusion_matrices.png
│   ├── fig9_roc_curves.png
│   └── fig10_tuned_rf_importance.png
└── report/
    ├── DS471_Project_Report.docx
    └── DS471_Project_Report.pdf
