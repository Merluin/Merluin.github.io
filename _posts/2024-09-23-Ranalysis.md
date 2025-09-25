---
layout: distill
title: Data Analysis Template
date: 2024-09-23
description: Rproj template for data analysis
tags: analysis template open_science
categories: sample-posts
giscus_comments: true
related_posts: true
featured: true
thumbnail: assets/img/R.png
---

# Data analysis template: A Reproducible R Framework for PsychoPy Behavioral Experiments

I'm excited to share a new open-source project designed to streamline the process of analyzing behavioral data collected with [PsychoPy](https://www.psychopy.org/):

👉 **[Data_analysis_template on GitHub](https://github.com/Merluin/Data_analysis_template)**

This template is ideal for researchers who collect `.csv` files from PsychoPy experiments and want a consistent, reusable R-based analysis workflow.

## What It Does

The template provides:

- A structured R project layout (`R/`, `data/`, `original_data/`, etc.)
- Ready-to-use functions for common preprocessing steps
- Support for saving results in `.RData` and `.xlsx`
- A clean GitHub repository with MIT license and template button

## Why Use It

This template was created to address common issues in behavioral science research:

- Poor file organization
- Redundant code copy-pasting between experiments
- Inconsistent use of statistical functions
- Lack of reproducibility

By providing a clear, modular R structure and helper functions, this project promotes transparency and makes it easy to replicate your own or others' work.

## What is an R Project (`.Rproj`)?

An R project file (`.Rproj`) defines a **self-contained environment** in RStudio. Think of it as a sandbox:

- All your scripts, data, and outputs stay in one place
- You don't need to manage complex file paths — `here::here()` or relative paths work out of the box
- It's easy to **share**, **version**, and **reproduce** the analysis on another computer

In short: **open the `.Rproj` file, and you’re ready to go.**

## Getting Started

You can start using the template in **three easy ways**:

### 1. Use it directly from GitHub

Click the green **"Use this template"** button:  
👉 [https://github.com/Merluin/Data_analysis_template](https://github.com/Merluin/Data_analysis_template)

This creates a new copy under your own GitHub account, preserving the folder structure and code.  
✨ Don’t forget to leave a ⭐ on the repository if you find it helpful!

### 2. Clone manually

```bash
git clone https://github.com/Merluin/Data_analysis_template.git
```

Then open Data_analysis.Rproj in RStudio and start analyzing.

### 3. Just download the ZIP

Click the “Code” button and select “Download ZIP”.
Unzip it anywhere, open the .Rproj file, and you’re ready to go — no Git required.

## 📁 Project Structure

```bash
Data_analysis_template/
├── DESCRIPTION             # R package metadata
├── R/                      # All core analysis functions
├── data/                   # Cleaned datasets saved as .RData
├── original_data/          # Raw .csv files from PsychoPy
├── scripts/                # Custom analysis scripts (per experiment)
├── LICENSE                 # MIT License
├── README.md               # Project description
└── Data_analysis.Rproj     # RStudio project file
```

## ☕ The Coffee Machine Corner

This blog — The Coffee Machine — is where ideas percolate.
If you found this project useful, consider supporting the time and caffeine behind it.

You’re also warmly invited to fork the repo, contribute, or reach out if you’re working on similar tools. Collaboration brews innovation!

👉 Scroll down and leave a comment below! I’d love to hear from you.
