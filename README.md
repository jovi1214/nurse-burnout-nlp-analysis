# Nurse Burnout: Natural Language Processing Analysis

**Python | NLP | Sentiment Analysis | Topic Modeling | Healthcare Analytics**

## Project Overview

This project explores how natural language processing (NLP) can be applied to online discussions about nurse burnout to identify recurring themes, analyze sentiment, and examine the limitations of automated text analysis in healthcare research.

Developed as part of graduate coursework at the University of Colorado Boulder, the project combines computational analysis with qualitative interpretation to investigate how healthcare workers describe workplace stress and burnout.

## Research Objectives

- Analyze sentiment in nurse burnout discussions.
- Identify recurring topics and language patterns.
- Explore how workload, staffing, and workplace conditions are represented in online discussions.
- Compare automated NLP outputs with qualitative interpretations.
- Evaluate the reliability and limitations of NLP methods applied to healthcare-related discussions.

## Data Sources

The project draws on three types of sources:

**1. Reddit — Qualitative Text Data**

Discussions from r/NurseBurnout and r/nursing provide examples of firsthand experiences related to workplace stress, emotional exhaustion, and burnout.

**2. Kaggle — Structured Reference Data**

The [Burnout in Nurses dataset](https://www.kaggle.com/datasets/shauryapal/burnout-in-nurses/data) provides structured burnout-related indicators to contextualize patterns identified in textual discussions.

**3. Statista — Healthcare Workforce Context**

Published statistics on nurse burnout provide broader context for interpreting the significance of workplace stress and burnout.

These sources serve different analytical purposes and should not be treated as interchangeable datasets.

## Tools & Technologies

- **Python:** Data processing and analysis
- **Pandas:** Data manipulation and preprocessing
- **NLTK / VADER:** Sentiment analysis
- **Scikit-learn:** Latent Dirichlet Allocation (LDA) topic modeling
- **Jupyter Notebook / Google Colab:** Development, execution, and documentation

## Methodology

**1. Data Preparation**

Prepared structured and unstructured data for analysis, including text cleaning and preprocessing.

**2. Sentiment Analysis**

Applied NLP-based sentiment classification to examine emotional tone in discussions related to nurse burnout.

**3. Topic Modeling**

Used LDA topic modeling to explore recurring language patterns and potential themes within the text.

**4. Qualitative Evaluation**

Examined automated outputs alongside contextual interpretations, paying particular attention to cases where sentiment classification might overlook nuance or emotional complexity.

## Analytical Observations

The project examined the usefulness and limitations of sentiment analysis and topic modeling for understanding nurse burnout.

Important considerations included:

- Sentiment scores alone may not adequately represent complex workplace experiences.
- Topic modeling requires human interpretation to establish meaningful connections between recurring terms and workplace conditions.
- Healthcare-related discussions can contain mixed emotions, contextual language, and experiences that automated methods may misinterpret.
- Small or nonrepresentative samples limit the generalizability of analytical results.

These observations emphasize the importance of combining automated analysis with domain knowledge and qualitative evaluation.

## Limitations

- Online discussions may not represent the broader nursing workforce.
