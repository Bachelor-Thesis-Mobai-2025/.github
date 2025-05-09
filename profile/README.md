# Mouse Tracking Deception Detection Research

This organization contains private repositories related to academic research on mouse tracking as a method for deception detection. The work investigates the relationship between mouse movement patterns and deceptive behavior, providing a framework for data collection, analysis, and classification.

## Repositories

The repositories in this organization contain research implementations exploring mouse tracking as a method for deception detection. These repositories include experimental code developed throughout the thesis project, such as data collection tools, feature extraction, and neural network classification models.

**Note:** All repositories related to this research are private due to copyright agreements with industry partners.

## Research Methodology

The thesis research employed a systematic approach to deception detection:

1. **Data Collection:** Custom-designed web interface with randomized layouts and question sequencing
2. **Feature Extraction:** Comprehensive analysis of mouse movement dynamics (velocity, acceleration, curvature, etc.)
3. **Feature Analysis:** Statistical evaluation of discriminative features between truthful and deceptive responses
4. **Model Development:** GRU and LSTM neural networks with cross-validation and class imbalance handling

## Key Findings

The research demonstrates the potential of mouse tracking for deception detection:

- Movement dynamics (acceleration changes, velocity variability) are highly discriminative features
- Path efficiency and movement smoothness differ significantly between truthful and deceptive responses
- Neural networks can effectively classify deceptive behavior from mouse movement patterns
- Cross-validation with SMOTE oversampling produces more robust classification models

## Technical Implementation

- **Web Application:** Flask, HTML/CSS/JavaScript
- **Data Processing:** Pandas, NumPy, Matplotlib, Seaborn
- **Machine Learning:** PyTorch, Scikit-learn, Imbalanced-learn (SMOTE)
- **Validation:** StratifiedKFold cross-validation (5 folds)

## Thesis Information

- **Title:** Mouse Tracking as Behavioral Biometrics: A Statistical, Machine- and Deep-Learning Approach to Mouse Tracking as Deception Detection
- **Institution:** NTNU Gjøvik
- **Supervisor:** Kiran Raja
- **Academic Year:** 2025

## Contact

For inquiries regarding this research:
- Academic email: torgrim.l.thorsen@stud.ntnu.no
