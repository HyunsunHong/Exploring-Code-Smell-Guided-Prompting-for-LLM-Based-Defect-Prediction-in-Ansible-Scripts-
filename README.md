# Code Smell-Guided Prompting for LLM-Based Defect Prediction in Ansible Scripts

## Overview
This repository contains the code and datasets used for the experiments presented in our paper titled "Exploring Code Smell-Guided Prompting for LLM-Based Defect Prediction in Ansible Scripts". The purpose of this repository is to ensure the reproducibility of our experiments and provide transparency for our research methods.

## Repository Structure
├── data
│ ├── ansible_scripts
│ ├── code_smells
│ └── README.md
├── experiments
│ ├── baseline
│ ├── cot_csp
│ └── README.md
├── src
│ ├── preprocessing
│ ├── prompting
│ ├── evaluation
│ └── README.md
├── results
│ └── README.md
├── requirements.txt
└── README.md

- **data/**: Contains the datasets used for the experiments, including Ansible scripts and code smell indicators.
- **experiments/**: Contains scripts for running the different experiments, including baseline models and our proposed CoT-CSP method.
- **src/**: Contains the source code for preprocessing data, generating prompts, and evaluating results.
- **results/**: Contains the results of the experiments, including performance metrics and evaluation reports.
- **requirements.txt**: Lists the dependencies and libraries required to run the experiments.

## Getting Started

### Prerequisites
- Python 3.8 or higher
- Virtual environment (recommended)

### Installation
1. Clone the repository:
git clone https://github.com/HyunsunHong/CSP_for_LLM-based-SDP-in-Ansible.git

2. Create and activate a virtual environment:
python -m venv venv
source venv/bin/activate # On Windows: venv\Scripts\activate

3. Install the required packages:
pip install -r requirements.txt

4. Run the experiment:
