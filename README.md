## Data Science Portfolio  
**Johannes Van Cauwenberghe**  
London, UK — MSc Data Science (University of London)

This portfolio presents a selection of applied data science projects across domains including natural language processing, causal inference, urban analytics, and ethical AI. Each project folder contains the codebase (`.ipynb` or `.qmd`), dependencies (`requirements.txt`), and a corresponding PDF or HTML report. The goal is not only to demonstrate technical proficiency, but to highlight *how data can inform public-interest questions*---from sustainability and urban policy to media bias and ethics.

---

## Featured Projects

### Optimising News Recommenders Beyond Accuracy (final project)
**[Optimising Beyond Accuracy: Tuning for Diversity and Novelty in Attention-based News Recommenders](https://github.com/JohannesVC/OptimisingBeyondAccuracy)** 
A deep learning–based recommender system for news articles that balances accuracy with diversity and novelty, using the MIND dataset and attention-based neural architectures. Regularisation terms for Intra-List Diversity and Surprisal are embedded directly in the model’s loss function.
📄 [Read report (ResearchGate)](https://www.researchgate.net/publication/391382172_Optimising_Beyond_Accuracy_Tuning_for_Diversity_and_Novelty_in_Attention-based_News_Recommenders)

---

### Visualising Urban Change  
**[Visualising Urban Change: The Impact of Traffic Calming Measures on Symbolic Capital and Socio-Economic Dynamics in London](./visualising-symbolic-capital-London)**  
A spatial analysis of London’s Low-Traffic Neighbourhoods (LTNs) and their relationship to "symbolic capital" retail (boutiques, bakeries, etc.), using Companies House, OpenStreetMap, income/demographic data from statistical agencies, and Voronoi diagrams.
📄 [Read report (PDF)](./visualising-symbolic-capital-London/report-no-code.pdf)

---

### Sustainable Finance under Uncertainty  
**[Bayesian Investment Analysis](./bayesian-investment-analysis)**  
A decision-support system for green investors using a custom Bayesian Network in `pgmpy`, predicting environmental and financial viability from policy and market factors.  
📄 [Read report (PDF)](./bayesian-investment-analysis/report.pdf)

---

### Political Bias Detection in News Media  
**[Political Bias in News: A Feature-Weighted Classifier](./nlp-political-bias-in-news)**  
Classified news articles as left- or right-leaning using the Log-Odds Ratio with Informative Dirichlet Prior (LOR-IDP). Combined AllSides and NewsCatcher data for a bias-aware pipeline.  
📄 [Read report (PDF)](./nlp-political-bias-in-news/report.pdf)

---

### NLP at Scale with Common Crawl  
**[Mapping Corporate Ethics: Clustering UK Companies’ Values Using NLP](./nlp-common-crawl-corporate-ethics)**  
Clustered mission statements from UK firms scraped from the Common Crawl using PySpark, TF-IDF, and topic modelling.  
📄 [Read report (PDF)](./nlp-common-crawl-corporate-ethics/report.pdf)

---

### Systematic Deep Learning for News Classification  
**[A Systematic Exploration of News Classification Using Neural Networks](./deep-learning-for-news-classification)**  
Benchmarked various deep learning models across different news categories. Emphasised reproducibility and interpretability, with structured hyperparameter tuning and model comparison using Keras 3.8.  
🌐 [Read report (HTML)](https://storage.googleapis.com/data-science-portfolio/deep-learning-for-news-classification/report.html)

---

### Multimodal Bias Classification  
**[Multimodal Architectures for Bias Classification in News](./deep-learning-for-multimodal-bias-classification)**  
Integrated textual and metadata features (e.g. source, region, headline) using hybrid deep learning models. Demonstrated that combining non-textual features improves political bias prediction, especially for under-represented classes.  
🌐 [Read report (HTML)](https://storage.googleapis.com/data-science-portfolio/deep-learning-for-multimodal-bias-classification/report.html)

---

### Quantifying Indifference in UK Media  
**[Quantifying Indifference Towards Palestinian Suffering Across UK News Sources](./quantifying-indifference-towards-palestinian-suffering)**  
Analysed over 4,000 articles from UK news outlets (including 744 scraped from BBC News) using NER, sentiment scoring, and date-level casualty records to uncover disparities in how Palestinian vs. Israeli suffering is reported. Offers an interactive data-driven critique of media framing and moral distance, particularly of the BBC.  
🌐 [Read report (HTML)](https://storage.cloud.google.com/data-science-portfolio/quantifying-indifference-towards-palestinian-suffering/report.html)

---

## Navigation and Reproducibility

- Each folder contains its own `README.md` for full context.
- Environments are reproducible via `requirements.txt`.
- Reports are provided as PDFs or self-contained HTMLs.
- Please note that some datasets are not uploaded due to size or licensing.

---

## 📬 Contact  

Feel free to reach out via [LinkedIn](https://www.linkedin.com/in/johannesvc/) or email (johannes.vc@hotmail.com) for collaborations, freelance data work, or research inquiries.
