## Fraud Transaction Analysis

This project analyzes credit card transaction data to identify patterns associated with fraudulent activity.
The goal is to explore how transaction characteristics such as amount and timing differ between normal and fraudulent transactions, and to assess whether these features can support fraud detection.
The analysis is performed using Python (pandas, numpy, matplotlib) and SQL, with a focus on exploratory data analysis, feature engineering, and behavioral pattern recognition.

## Approach

The analysis was conducted in several stages:

- Initial data exploration to understand dataset structure and key variables
- Analysis of transaction distributions based on amount and time patterns
- Feature engineering, including log transformation of transaction amounts and high-value segmentation
- Comparative analysis to identify behavioral differences between genuine and fraudulent transactions

## Key Insights

1. Fraud cannot be reliably identified using a single feature, and instead requires a multi-dimensional approach combining multiple signals.

2. Normal transactions exhibit a clear cyclical pattern with higher activity during daytime hours, while fraudulent transactions show a more dispersed distribution with less pronounced periodic behavior and occasional burst patterns.

3. High-value transactions show a higher concentration of fraud compared to the overall dataset, although transaction amount alone is not a strong standalone indicator.

## Conclusion

The analysis demonstrates that fraudulent behavior cannot be captured by a single variable and requires combining multiple features such as transaction value and temporal patterns. This highlights the importance of multi-dimensional analysis in fraud detection systems.