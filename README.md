# AI Customer Review Intelligence Dashboard

This Google Colab notebook provides an interactive dashboard for advanced NLP sentiment analysis of customer reviews. It leverages multiple BERT models to analyze sentiment and emotions, offering a comprehensive suite of visualizations to explore insights from review data.

## Features

- **Multi-model BERT Analysis**: Utilizes DistilBERT, RoBERTa, Emotion Detector, and 5-Star Rating Predictor models for diverse sentiment and emotion classification.
- **Interactive Dashboard**: A dynamic widget-based UI allows users to select models, sample sizes, and instantly generate various charts.
- **13+ Interactive Chart Types**: Includes sentiment distribution donuts, rating bars, sentiment trends, confidence histograms, category-grouped sentiment bars, rating-sentiment heatmaps, top keywords, word clouds (overall, positive, negative), sentiment gauges, confidence box plots, rating vs. confidence scatters, sunburst category-sentiment charts, and word count violin plots.
- **Data Loading**: Capable of loading Amazon Beauty Products dataset from Hugging Face or falling back to a rich synthetic dataset.
- **Export Capabilities**: Exports analyzed data, summary statistics, and static summary charts to CSV and PNG formats.

## Getting Started

### 1. Open in Google Colab

Click the button below to open and run the notebook directly in Google Colab:


### 2. Run All Cells

Execute all cells in the notebook. The initial cells will install necessary packages, load imports, and set up styling. The data loading cell (`CELL 3`) will load a dataset for analysis.

### 3. Interact with the Dashboard

Navigate to `CELL 6 — INTERACTIVE DASHBOARD`. Here you will find the main interactive UI:

- **Select an AI Model**: Choose from the available BERT models for analysis.
- **Select Sample Size**: Adjust the number of reviews to analyze.
- **Run Analysis**: Click the `🚀 Run Analysis` button to process the data with the selected model.
- **Explore Charts**: Once analysis is complete, select a chart from the dropdown and click `👁️ View Chart`, or `📋 All Charts` to generate all visualizations.

### 4. Export Results (Optional)

In `CELL 7 — EXPORT RESULTS`, you can export the analyzed data, summary statistics, and static summary charts (PNG) to your local machine.
