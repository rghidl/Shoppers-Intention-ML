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
│   ├── stage3_nn_results_summary.csv       # neural network CV / validation metrics
│   ├── stage3_nn_search_results.csv        # neural network tuning log (random search)
│   ├── stage3_nn_refine_results.csv        # top configurations re-run with new seeds
│   ├── stage3_nn_history.csv               # per-epoch training / validation curves (tuned)
│   ├── stage3_nn_baseline_history.csv      # per-epoch curves (untuned baseline)
│   └── splits/                              # train.csv, val.csv, test.csv (70/15/15, stratified)
├── models/
│   ├── random_forest_tuned.joblib
│   ├── svm_tuned.joblib
│   └── neural_network_tuned.joblib
├── notebooks/
│   ├── stage1_eda_preprocessing.ipynb     
│   ├── stage2_splitting_traditional_ml.ipynb   # splitting, RF & SVM tuning, cross-validation
│   ├── stage3_neural_network.ipynb             # neural network, tuning, training vs validation curves
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
│   ├── fig10_tuned_rf_importance.png
│   ├── fig11_nn_baseline_curves.png
│   ├── fig12_nn_tuned_curves.png
│   ├── fig13_nn_hyperparameter_effects.png
│   └── fig14_nn_capacity_regularisation.png
└── report/
    ├── DS471_Project_Report.docx
    └── DS471_Project_Report.pdf
