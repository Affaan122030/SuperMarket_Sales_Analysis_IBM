# Supermarket Sales Analysis — IBM SkillsBuild / AICTE Data Analytics Project

## Project Description

This project analyzes supermarket transaction data to identify useful information about products, branches, categories, customers, payment methods, and customer ratings.

The project follows the required workflow:

**Load Data → Check Data Quality → Validate Sales → Summarize → Visualize → Interpret → Business Decisions**

The project dataset contains 500 sales transactions and includes product, branch, city, customer type, quantity, price, payment method, rating, and sales.

## Project Questions

The analysis answers:

1. Which product generates the highest sales?
2. Which branch performs best?
3. Which category sells the most?
4. What is the most popular payment method?
5. Do Members spend more than Normal customers?
6. What is the average customer rating?

## Required Analysis

- Dataset loading
- Missing-value checks
- Duplicate checks
- Data-type validation
- `Sales = Quantity × Unit Price` validation
- Descriptive statistics
- Grouping and aggregation
- Product analysis
- Category analysis
- Branch analysis
- Customer-type analysis
- Payment analysis
- Customer-rating analysis
- Monthly sales analysis
- Correlation analysis
- Visualizations
- Business insights
- Hypotheses
- Recommendations
- Final conclusion

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- OpenPyXL
- Jupyter Notebook / Google Colab

## Dataset

**Dataset source:** The supermarket dataset supplied as part of the IBM SkillsBuild / AICTE Data Analytics internship project materials.

The notebook is designed to accept the supplied CSV/Excel dataset through Google Colab upload.

> Replace this section with the official dataset URL if your internship coordinator provided a public dataset link. The project document available in this submission materials does not contain a public dataset URL.

## Project Files

- `Affaan_SupermarketSalesAnalysis.ipynb` — complete runnable project code
- `requirements.txt` — Python dependencies
- `Affaan_SupermarketSales_ProjectReport.docx` — project documentation
- `README.md` — project overview and setup instructions

## How to Run in Google Colab

1. Open Google Colab.
2. Upload `Affaan_SupermarketSalesAnalysis.ipynb`.
3. Click **Runtime → Run all**.
4. When the upload cell appears, upload the supermarket dataset supplied for the project.
5. The notebook automatically loads the dataset.
6. Continue through the notebook from top to bottom.
7. The final cells export cleaned data and summary CSV files.

## How to Run Locally

Install dependencies:

```bash
pip install -r requirements.txt
```

Then open:

```bash
jupyter notebook Affaan_SupermarketSalesAnalysis.ipynb
```

Place the supermarket dataset in the same folder as the notebook if running outside Google Colab.

## Expected Reference Results

For the supplied project dataset, the project document records:

- Highest-sales product: Cheese — ₹27,906.30
- Best-performing branch: Branch C (Mumbai) — ₹72,469.45
- Highest-sales category: Beverages — ₹56,108.24
- Most-used payment method: UPI — 127 transactions
- Average Member transaction: ₹483.14
- Average Normal transaction: ₹497.07
- Average customer rating: 3.99 / 5

The notebook calculates these values from the uploaded dataset and includes a validation section to compare the calculated results with the project-document reference values.

## Internship Storytelling Deliverables

The notebook also includes:

- 5 visualizations
- 5 observations
- 5 data-supported insights
- 3 clearly labelled hypotheses
- 3 actionable recommendations

## Business Decisions

The analysis supports decisions around:

- Stocking high-selling products and categories
- Comparing branch performance
- Supporting commonly used payment methods
- Monitoring customer ratings
- Using customer spending patterns for membership offers

## Limitations

The analysis describes the supplied transaction dataset and should not automatically be generalized to all supermarket businesses. Correlation does not establish causation, and hypotheses are presented as possible explanations rather than confirmed facts.
