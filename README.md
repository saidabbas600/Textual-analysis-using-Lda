### Textual Analysis of Monetary Policy Trends using LDAThis repository contains the framework and codebase for performing advanced textual analysis on the State Bank of Pakistan’s Monetary Policy Statements (2005–2024). 
By leveraging Natural Language Processing (NLP) and Latent Dirichlet Allocation (LDA), this project identifies thematic shifts and sentiment trends in central bank communications over nearly two decades.

## Project Overview
The core objective of this research is to quantify qualitative policy documents. The model extracts hidden thematic structures (topics) from policy text to visualize how the State Bank's priorities—such as inflation control, exchange rate stability, or economic growth—have evolved in response to global and domestic shocks.
## Technical StackLanguage:
R / Python Methodology: 
* LDA (Latent Dirichlet Allocation): For unsupervised topic modeling and thematic discovery.NLP Pipeline: Tokenization, stop-word removal, lemmatization, and N-gram construction.Sentiment Analysis: Quantifying the "tone" of policy statements to correlate with macroeconomic indicators.Tools: topicmodels, tm, tidytext, and ggplot2 for high-level visualizations.
## Key FeaturesAutomated Text Scraping: 
Scripts designed to collect and clean PDF/text statements from official repositories.Dynamic Topic Modeling: Analysis of 19 years of policy data to detect structural breaks in economic discourse.Thematic Visualization: Interactive plots showing the prevalence of specific economic themes over time.
