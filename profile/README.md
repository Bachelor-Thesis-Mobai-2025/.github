# Mouse Tracking Deception Detection Research

This organization houses the codebase for our bachelor's thesis research on mouse tracking as a method for deception detection. Our work investigates the relationship between mouse movement patterns and deceptive behavior, providing a complete framework for data collection, analysis, and classification.

## Our Repositories

### [Mouse Tracking Playground](https://github.com/Bachelor-Thesis-Mobai-2025/mouse-tracking-playground)

Our original research implementation exploring mouse tracking as a method for deception detection. This repository contains the experimental codebase developed throughout the thesis project, including data collection tools, feature extraction, and neural network classification models. (Commit history has been reset due to upload error due to upload size limitations)

**Key Components:**
- Flask-based web application for data collection with 5 unique experimental layouts
- Comprehensive mouse movement tracking and feature extraction
- Feature importance analysis with visualization tools
- Neural network classification models (GRU/LSTM variants)
- Multiple preprocessed datasets with various trajectory processing approaches
- Best model achieved 68.57% accuracy on the test dataset

### [Mouse Tracking Optimized](https://github.com/Bachelor-Thesis-Mobai-2025/mouse-tracking-optimized)

A refactored, structured and clean version of the original mouse tracking implementation with only the minimal required files. This repository presents the same research in a more maintainable format suitable for academic review and future extension.

**Improvements:**
- Clear directory structure following software engineering best practices
- Improved code modularity for research reproducibility

## Research Methodology

Our thesis research employed a systematic approach to deception detection:

1. **Data Collection:** Custom-designed web interface with randomized layouts and question sequencing
2. **Feature Extraction:** Comprehensive analysis of mouse movement dynamics (velocity, acceleration, curvature, etc.)
3. **Feature Analysis:** Statistical evaluation of discriminative features between truthful and deceptive responses
4. **Model Development:** GRU and LSTM neural networks with cross-validation and class imbalance handling

## Key Findings

Our research demonstrates the potential of mouse tracking for deception detection:

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
- **Supervisors:** Kiran Raja
- **Academic Year:** 2025

## Contact

For questions regarding this research or repositories:
- Torgrim Thorsen
- torgrim.l.thorsen@stud.ntnu.no
