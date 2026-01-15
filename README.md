# CRM Segmentation — RFM + PCA + KMeans

This project groups customers into actionable CRM segments to support prioritisation and activation planning (e.g., retention, reactivation and high-value targeting).

## Business question
How can we group customers into interpretable segments that are easy to activate in CRM campaigns?

## Approach (summary)
- **Features:** customer-level RFM signals + channel/behavioural variables
- **Dimensionality reduction:** PCA to stabilise clustering and improve interpretability
- **Clustering:** KMeans to produce operational segments
- **Output:** segment profiles + key insights + activation-ready recommendations

## Key outputs
- **Notebook:** `notebooks/01_segmentation.ipynb`
- **Full report (HTML):** (link from portfolio site)  
  `https://valescabravo.github.io/reports/Customer_Segmentation.htm`
- **VBDA InsightLab library (used for narrative + styling):**  
  `https://github.com/ValescaBravo/vbda-insightlab`

## How to run (local)

```bash
pip install -r requirements.txt
```
jupyter notebook

Open: notebooks/01_segmentation.ipynb

Notes

The HTML report is the stakeholder-ready deliverable.

This repository provides supporting evidence (notebook + reproducibility).
