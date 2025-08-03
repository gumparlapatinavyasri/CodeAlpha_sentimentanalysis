#  Amazon Sales Sentiment Analysis – 2025 Edition

This project analyzes sentiment and emotional trends based on transactional patterns in Amazon's 2025 sales data. While the dataset doesn't include customer reviews, sentiment is inferred from order status, product category, location, and purchase behaviors to uncover meaningful business and public insights.

---

##  Objectives

-  Classify each order as Positive, Negative, or Neutral using status flags (`Completed`, `Cancelled`, `Pending`)
-  Detect underlying emotions (Joy, Anger, Sadness, Uncertainty) by combining category and sentiment logic
-  Apply sentiment mapping on Amazon’s transactional sales data from across U.S. cities
-  Understand trends across products, regions, and consumer mood
-  Inform business strategies in marketing, customer targeting, and product development

---

##  Tools & Techniques

- **Python** – pandas, matplotlib, seaborn for analysis and visualization
- **Rule-based sentiment & emotion mapping** – custom logic for transactional inference
- **Exploratory Data Analysis (EDA)** – uncover trends across categories and locations
- **Business insight mapping** – link consumer mood with strategic recommendations

---

##  Core Insights

-  **Sentiment Distribution:** `Completed` orders dominate electronics and fashion segments, while `Cancelled` orders spike in high-cost categories like Home Appliances
-  **Emotion Mapping:** Products like smartphones and books evoke joy; repeat cancellations suggest anger or buyer hesitation
-  **Regional Patterns:** Cities like Miami and Boston show high cancellation sentiment; Seattle and Denver lean more positive
-  **Strategic Implications:** Focus marketing on products and regions with joyful/positive sentiment signals

---

##  Visualizations

- Sentiment and emotion distributions
- Regional sentiment trends across customer locations
- Product category sentiment breakdown
- Business-focused interpretation charts



---

##  Next Steps

- Enrich dataset with scraped customer reviews (Twitter, Amazon, or App Store)
- Integrate NLP models (VADER, TextBlob, NRC) for richer emotion detection
- Deploy as interactive dashboard using **Streamlit**

---

##  Repository Contents

- `amazon_sales_analysis.ipynb` – Main analysis notebook
- `amazon_sales_data 2025.csv` – Source dataset
- `README.md` – Project summary and objectives


---

##  Conclusion

This project showcases how meaningful insights can be extracted from structured transaction data—even without textual reviews—using smart inference techniques. By mapping sentiment through order status and product behavior, and layering emotion logic via category signals, we revealed trends in consumer mood and public perception across regions and products.

