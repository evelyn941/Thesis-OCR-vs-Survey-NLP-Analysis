# OCR-vs-Survey-NLP-Analysis
My undergraduate thesis: A construct-based framework using a fine-tuned BERT clause-level classifier to quantitatively assess the alignment between online consumer reviews (OCRs) and structured satisfaction surveys through novel coverage and sparsity metrics.

## Project Overview
While OCRs offer spontaneous and timely feedback, their unstructured nature often makes it unclear if they capture the same evaluative domains as standardized surveys. This study develops a construct-based framework and a BERT-based NLP pipeline to map 135,252 review clauses to a five-domain apparel taxonomy: Product Quality, Aesthetic Attributes, Functionality, Size & Fit, and Value Perception.

## Key Contributions
* **Clause-Level Segmentation:** A rule-based procedure to decompose multi-faceted reviews into atomic evaluative statements.
* **Alignment Metrics:** Implementation of three novel metrics:
    * **Construct Coverage Index (CCI):** Measures distributional divergence.
    * **Variance Gap Index (VGI):** Quantifies review-level inconsistency.
    * **Review Sparsity Index (RSI):** Measures the completeness of construct expression.

## Dataset
The dataset involves 42,943 valid reviews of Uniqlo apparel products collected from Tmall.com.
* **Timeframe:** July 29, 2019, to March 5, 2021.
* **Data Size:** 135,252 clauses after cleaning and segmentation.
* **Annotations:** Two manually labeled datasets (Review-based and Clause-based) used for model training and validation.
