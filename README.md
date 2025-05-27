Task 2: Exploratory Data Analysis (EDA) – Named Entity Recognition Dataset

This project is part of an AI & ML internship focused on performing Exploratory Data Analysis (EDA) using the ner_dataset.csv dataset. The dataset contains words from various sentences along with their Part of Speech (POS) tags and Named Entity Recognition (NER) labels.

Dataset Overview

- Columns:
  - Sentence : Sentence identifier
  - Word: Individual word in the sentence
  - POS: Part-of-Speech tag
  - Tag: NER tag

  Source:provided dataset (can also be substituted with similar NLP datasets)

Tools & Libraries Used

- Python
- Pandas
- Matplotlib
- Seaborn

Key Steps in EDA

1. Data Loading:
   - Loaded the dataset using proper encoding (latin1) to handle special characters.
   - Filled missing values using forward fill (ffill).

2. Summary Statistics:
   - Checked basic dataset info and value distributions.
   - Created a Word_Length feature for further analysis.

3. Visualizations:
   - Bar plot of tag distribution.
   - Boxplot of word lengths grouped by tags.
   - Heatmap of correlation (e.g., capitalization vs. word length).
   - Pairplot (for selected features).

4. Insights:
   - Identified imbalance in tag distribution.
   - Observed that NER tags have varied word lengths.
   - Analyzed basic text-based features like capitalizatio
   
Sample Visuals

- Tag Distribution (Bar Chart)
- Word Length by NER Tag (Boxplot)
- Correlation Heatmap

Skewness Analysis

Calculated skewness for Word_Length to assess feature distribution.
