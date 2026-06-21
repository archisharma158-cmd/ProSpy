# ProSpy

ProSpy is an AI-powered fake profile detection system.

## Team
-Archi Sharma : Project Lead & Repository

-Parth Goyal : Research Lead

## Goal
Detect fake social media profiles using machine learning and cybersecurity indicators.

## Features
-Followers Count
-Following Count
-Post Count
-Account Age
-Profile Pictures Presence
-Bio Analysis
## Results and Future Work

### Key Observation
The initial model achieved high accuracy due to a severe class imbalance in the dataset.

### Error Analysis
Further analysis using the confusion matrix revealed that the model predominantly predicted the majority class, indicating poor performance on minority classes despite the high overall accuracy.

### Future Improvements
- Collect a more balanced dataset.
- Apply advanced class-balancing techniques, such as:
  - Oversampling (e.g., SMOTE)
  - Undersampling
  - Class weighting
  - Ensemble-based balancing methods
- Evaluate the model using additional metrics such as:
  - Precision
  - Recall
  - F1-score
  - ROC-AUC
