# Portfolio Image Curation & Curation Log

This document lists the required visual assets for my Machine Learning portfolio, detailing the choices made between real captures and AI generation, along with a log of rejected AI imagery.

---

## 📸 1. The Portfolio Image Set (Keepers)

| Asset Name | Page & Section | Type | Details / Source |
| :--- | :--- | :--- | :--- |
| **`personal_headshot.jpg`** | Home: Hero Section | **Real Photo** | A clear, professional, well-lit headshot of myself. No AI stand-ins or cartoon avatar styling. |
| **`raw_data_sample.png`** | Case Study: The Problem | **Real Capture** | A high-contrast, clean crop of the raw GSC dataframe in Pandas (`df.head()`), showing the uncleaned, raw traffic logs and columns. |
| **`precision_at_50_comparison.svg`** | Case Study: What Came of It | **Real Capture** | A clear bar chart comparing the Precision@50 metrics of our baseline rule (0.240) vs the trained Random Forest model (0.780). |
| **`hero_background_pattern.svg`** | Home: Hero Background | **AI Generated** | An abstract, minimalist geometric pattern of vector nodes and connection lines in slate and emerald green. |
| **`decision_tree_split.svg`** | Case Study: What I Did | **Real Capture** | An exported visualization of the trained depth-2 decision tree (`export_text` output or diagram) showing the exact split rules. |

---

## 🔍 2. Real Captures vs. AI Stand-ins

*   **Rule Applied**: I chose **Real Captures** for all data outputs, results, and code. 
*   **Reasoning**: An engineering lead looking at an ML portfolio is skeptical of generic, flashy graphics. Using a real screenshot of the code (`df.head()` or the terminal pipeline run outputs) shows proof of work. AI-generated data dashboards look fake, have scrambled text, and immediately destroy trust.
*   **Real Headshot vs. AI Headshot**: I used a **Real Photo** for my personal bio. AI-generated professional headshots have a distinct plastic sheen and unnatural eyes that feel disingenuous to hiring managers.

---

## 🚫 3. AI Curation & Rejection Note

*   **Rejected Concept**: *An AI-generated, high-gloss 3D render of a glowing neural network brain floating in an futuristic cyber-laboratory, surrounded by binary code and neon green lighting.*
*   **Why I Rejected It**: It represents typical AI "slop"—overly flashy, saturated, and metaphorically generic. It screams "amateur template" and buries the actual work under sci-fi decoration. A dashboard-based Random Forest model runs on tabbed search volume numbers, not neural brains. 
*   **The Replacement**: I generated a flat, abstract 2D vector graphic of node connections using our specific color palette (`#0F172A` and `#10B981`). It is clean, quiet, frames the page, and lets the actual data screenshots be the most visually interesting things on the screen.
