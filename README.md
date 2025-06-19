# statistics
# A/B Test – Impact of In-Store Advertising on Toy Sales 🎯

This project implements an A/B test to evaluate whether displaying an advertisement at the entrance of a toy store significantly increases toy sales.

## 📊 Objective

To determine if in-store screen advertising leads to a statistically significant and economically meaningful increase in toy sales over a 60-day period.

---

## 🧪 Methodology

- **Data Simulation**: Simulated 60 days of toy sales with and without ads.
- **Statistical Test**: One-sided T-test using `pingouin`.
- **Visualizations**: Histograms, boxplots, and 95% confidence interval plots.
- **Economic Analysis**: Revenue calculations based on toy price and ad cost.

---

## 📈 Results Summary

- **Mean Sales Increase**: ~4.92 toys/day
- **P-value**: < 0.05 → Statistically significant
- **95% Confidence Interval**: [1.81, 8.02]
- **Monthly Revenue Gain**: ~$1,476
- **Ad Cost**: $1,500
- **Net Monthly Loss**: -$24

---

## 📌 Conclusion

- Statistically significant increase in sales due to ads.
- Slight short-term financial loss, but potential long-term brand value and market share benefits.

---

## 📂 Files Included

- `ab_test_analysis.py` – Python script with full implementation.
- `ab_test_report.pdf` – PDF report with charts, test results, and business summary.

---

## 🔧 Tools Used

- Python (pandas, numpy, seaborn, matplotlib, scipy, pingouin)
- Jupyter/VS Code for development
