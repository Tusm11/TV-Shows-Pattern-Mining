# TV-Shows-Pattern-Mining
Association rule mining project on a TV shows dataset. Uses Apriori algorithm and mlxtend in Python to discover frequent itemsets, analyze viewing clusters, and interpret popular combinations of shows for recommendations and trend analysis. Includes all preprocessing, analysis code, and dataset.


This project applies association rule mining and market basket analysis to a TV shows viewing dataset. Using the Apriori algorithm (via `mlxtend`), it discovers frequent combinations of shows, analyzes viewing trends, and interprets cluster patterns to provide insights and recommendations.

## Features

- Cleans and preprocesses a real-world TV show transaction dataset
- Encodes transactional data for machine learning analysis
- Finds frequent itemsets and most popular show combinations
- Analyzes cluster patterns in TV viewership
- Provides code templates for recommendations and trend analysis

## Project Structure

- `TV-Shows-Association-Rule-Learning.csv` — Raw dataset of TV show transactions
- `tv_show_association_rule_mining.ipynb` (or `.py`) — Main analysis notebook/script
- `README.md` — Project documentation

## Getting Started

**Dependencies:**
- Python 3.x
- pandas
- mlxtend

Install required packages using:
```bash
pip install pandas mlxtend
```

**How to Run:**
- Place the CSV file and notebook/script in the same folder.
- Open the notebook/script and run the cells/commands step by step.
- Adjust minimum support/confidence thresholds as needed for your dataset.

## Key Steps Implemented

- Data loading and cleaning
- Transaction to one-hot encoding
- Frequent itemset mining with Apriori
- Cluster/combination analysis
- (Optional) Recommendations based on association rules

## Example Output

- List of most popular individual shows
- Top combinations of shows frequently watched together

## Interpretation

The project reveals hidden patterns in TV viewing, groups commonly watched shows, and provides the basis for intelligent recommendation systems using association rules.

## License

This project is open for educational and non-commercial use.

***

Feel free to edit to match your style, add author names, or include example screenshots!
