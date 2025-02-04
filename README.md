# Health Complexity Scoring from Prescription Data

## Overview
This project focuses on developing a scoring system to classify an individual’s health complexity based on their prescription drug data and outpatient visit history. The system leverages Clinical Classification Software (CCS) mapping to create meaningful characterizations of a member's health status and builds a model to infer this status using prescription data alone.

## Requirements
1. **Characterize health status from outpatient data:**
   Using CCS mapping, provide a high-level description of a member’s health conditions, such as “Member XYZ had cancer and a broken leg.”

2. **Infer health complexity from prescription data:**
   Explore how prescription data can serve as a proxy for health status and build a predictive model or framework for future implementation.

## Project Structure
```
.
├── README.md                 # Documentation file
├── Health_Complexity_Scoring_from_Prescription_Data.ipynb  # Main project notebook
├── data/                     # Data used for exploration and modeling
├── results/                  # Outputs such as plots, tables, and reports
└── models/                   # Trained models or scripts for modeling
```

## Key Features
- Characterizes patient health status using outpatient and prescription data.
- Explores the predictive power of prescription drug records in assessing health complexity.
- Includes a plan for extending the analysis to future datasets with additional time and resources.

## How to Use
1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/health-complexity-scoring.git
    ```
2. Install the required dependencies:
    ```bash
    pip install -r requirements.txt
    ```
3. Run the notebook:
    Open the `Health_Complexity_Scoring_from_Prescription_Data.ipynb` file in a Jupyter environment to follow the analysis step by step.

## Results
- A summary of health complexity characterizations and key findings.
- Preliminary insights into the predictive value of prescription data.
- Recommendations for future modeling enhancements.

## License
This project is licensed under the MIT License.

## Contact
For questions or feedback, reach out to:
- **Email:** Adam.RivardWalter@gmail.com  
- **GitHub:** [adamw80](https://github.com/adamw80)
