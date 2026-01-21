# 🐸 DataForge

DataForge is a Python library for generating **structured, realistic synthetic datasets** from predefined templates.  
It is designed for analytics learning, data engineering workflows, testing, and demonstrations where access to real-world data is limited or unavailable.

---

## Table of Contents
- [Overview](#overview)
- [Key Features](#key-features)
- [Available Datasets](#available-datasets)
- [Installation](#installation)
- [Quick Start](#quick-start)
- [Use Cases](#use-cases)
- [Design Philosophy](#design-philosophy)
- [Limitations & Data Bias](#limitations--data-bias)
- [Roadmap](#roadmap)
- [Contributing](#contributing)
- [License](#license)
- [Author](#author)
- [Contact](#contact)

---

## Overview

Access to realistic data is one of the biggest barriers in analytics and data engineering practice.  
Most data generators produce random values that lack structure, relationships, or analytical relevance.

**DataForge focuses on generating usable data — not just fake data.**

It provides predefined dataset templates that resemble real-world schemas and can scale from small samples to large datasets.

---

## Key Features

- Predefined, analytics-ready dataset templates
- Generate any number of records on demand
- Consistent schemas and logical relationships
- Python-native API (Pandas-friendly)
- Suitable for learning, testing, and demos

---

## Available Datasets

DataForge currently supports **five dataset templates**:

| S.No | Dataset |Description |
|------------|-------|-----|
| Medium     | 137   ||
| Hard       | 61    ||
| Total  | 310   ||

Additional datasets will be introduced in future releases.

---

## Installation

Install the latest stable version from PyPI:

```bash
pip install dataforge

from dataforge import generate_dataset

# Generate 1,000 sales records
df = generate_dataset(
    dataset_type="sales",
    records=1000
)

print(df.head())

```

## Use Cases

DataForge is well-suited for:

- Power BI dashboard development and DAX practice
- SQL querying, joins, and aggregation exercises
- Data modeling and star schema practice
- Data engineering pipeline testing
- Tutorials, demos, and educational content

---

## Design Philosophy

DataForge is built around three core principles:

1. ### Structure over randomness
    Data follows logical schemas and relationships.

2. ### Practical realism
    Data resembles what analysts and engineers encounter in real projects.

3. ### Simplicity
    Minimal setup, predictable outputs, and easy integration into Python workflows.

---

## Limitations & Data Bias

DataForge generates **synthetic data**, which comes with inherent limitations:

- Data distributions are template-driven
- Patterns may be simplified
- Bias may exist based on design assumptions

⚠️ **Important:**  
Synthetic data produced by DataForge must undergo proper validation before use in production decision-making or machine learning model evaluation.

DataForge is intended for **learning, testing, and demonstration purposes**.

---

## License

This project is licensed under the MIT License.

---

## Author

Developed for the analytics and data engineering community.

---

## Contact

For questions, feedback, or collaboration opportunities:

- **GitHub Issues:** Use the repository issue tracker for bugs and feature requests
- **YouTube:** https://www.youtube.com/@bilearner
- **Professional Inquiries:** Reach out via LinkedIn or the contact details shared on the YouTube channel
