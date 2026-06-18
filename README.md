# customer-churn-rfm-segmentation

## Overview

Customer Churn RFM Segmentation Project is the Customer Segmentation Analysis project which analysis the customer behaviors and identify there value to the business allowing business to take right action at right time
The project contains Dataset and notebooks used in the analysis and retention strategy Document suggesting actions to take to increase customer retention

---

## Table of Contents

- [Overview](#overview)
- [Project Structure](#project-structure)
- [Requirements](#requirements)
- [Setup Instructions](#setup-instructions)

---

## Project Structure

```text
project-root/
│
├── data/
│   ├── customers.csv
│   ├── orders.csv
│   ├── support_ticket.csv
│   └── web_event_snapshot.csv
│
├── notebooks/
│   └── rfm_segmentation.ipynb
│
├── requirements.txt
├── retention_strategy.md
├── .gitignore
└── README.md
```

### Directory Description

| Directory/File | Description |
|---------------|-------------|
| `data/` | Stores project datasets |
| `notebooks/` | Experimental notebooks |

---

## Requirements

### Software

- Language Version: `Python 3.13.5`
- Package Manager: `pip`

---

## Setup Instructions

### 1. Clone Repository

```bash
git clone https://github.com/0-Deepak/customer-churn-rfm-segmentation.git
cd customer-churn-rfm-segmentation
```

### 2. Create Environment

```bash
# Example
python -m venv venv
source venv/bin/activate
```

### 3. Install Dependencies

```bash
pip install -r requirements.txt
```
---

## Reproducibility

### Reproduction Steps

1. Clone repository.
2. Create environment.
3. Install dependencies.
4. Run the notebook

---