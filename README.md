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
- Configured local remote storage at `/path/to/local/storage`.
- Tracked dataset `data/insurance_data.csv` with DVC.
