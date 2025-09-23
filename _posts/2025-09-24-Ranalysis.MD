---
layout: post
title: Data Analysis Template
date: 2025-09-24
description: Rproj template for data analysis
tags: analysis tutoriel
categories: sample-posts
disqus_comments: true
related_posts: false
---

# Data analysis template: A Reproducible R Framework for PsychoPy Behavioral Experiments

I'm excited to share a new open-source project designed to streamline the process of analyzing behavioral data collected with [PsychoPy](https://www.psychopy.org/):

👉 **[Data_analysis_template on GitHub](https://github.com/Merluin/Data_analysis_template)**

This template is ideal for researchers who collect `.csv` files from PsychoPy experiments and want a consistent, reusable R-based analysis workflow.

---

## What It Does

The template provides:

- A structured R project layout (`R/`, `data/`, `original_data/`, etc.)
- some Ready-to-use functions
- Support for saving results in `.RData` and `.xlsx`
- A clean GitHub repository with MIT license and template button

---

## Why Use It

This template was created to address common issues in behavioral science research:

- Poor file organization
- Redundant code copy-pasting between experiments
- Inconsistent use of statistical functions
- Lack of reproducibility

By providing a clear, modular R structure and ready-to-use helper functions, this project improves transparency and makes it easy to replicate your own or others' work.

---

## Getting Started

You can start using the template in two ways:

### 1. Use it directly from GitHub:

Click the green **"Use this template"** button:  
👉 [https://github.com/Merluin/Data_analysis_template](https://github.com/Merluin/Data_analysis_template)

This creates a new copy under your own GitHub account, preserving the folder structure and code.

### 2. Clone manually:

```bash
git clone https://github.com/Merluin/Data_analysis_template.git
```

Then open Data_analysis.Rproj in RStudio and start analyzing.

⸻

📁 Project Structure

```bash
AnalysisRproj/
├── DESCRIPTION             # R package metadata
├── R/                      # All core analysis functions
├── data/                   # Cleaned datasets saved as .RData
├── original_data/          # Raw .csv files from PsychoPy
├── scripts/                # Custom analysis scripts (per experiment)
├── LICENSE                 # MIT License
├── README.md               # Project description
└── Data_analysis.Rproj     # RStudio project file
```

✍️ Author Note

This project is maintained by Thomas Quettier. Feel free to fork, contribute, or get in touch if you’re working on similar projects.
If you'd like to support my work, you can do so here:  
☕ [buymeacoffee.com/thomasquettier](https://www.buymeacoffee.com/thomasquettier)

⸻

🧠 Acknowledgements
• PsychoPy for stimulus presentation
• R and the tidyverse for data analysis infrastructure

⸻

If you use this template in your work or research, feel free to cite it or drop me a message — I’d love to hear how it’s helping others!

---

Let me know if you want:

- A BibTeX citation block for the template
