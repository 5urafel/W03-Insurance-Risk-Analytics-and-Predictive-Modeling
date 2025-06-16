# 10 Academy: End-to-End Insurance Risk Analytics & Predictive Modeling

## Overview

This project analyzes historical car insurance data (Feb 2014–Aug 2015) for AlphaCare Insurance Solutions to optimize marketing strategies and identify low-risk segments for premium reduction. Tasks include EDA, A/B testing, data versioning, and predictive modeling.

## Setup

```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
pip install -r requirements.txt
```

## Task 2: Data Version Control

- Initialized DVC for data versioning.
- Configured local remote storage at `/Documents/dvc_storage`.
- Tracked dataset `data/MachineLearningRating_v3.txt` with DVC.

### Dataset Versions

- `MachineLearningRating_v3.txt`: Original dataset.
- `MachineLearningRating_v3_cleaned.txt`: Cleaned version with missing values removed.

## Task 3: A/B Hypothesis Testing

- Objective: Validate hypotheses on risk drivers using statistical tests.
- In progress: Data segmentation and testing.

## Task 4: Predictive Modeling

- Objective: Build models for claim severity, probability, and premium optimization.
- In progress: Data preparation and model building.
