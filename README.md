# Predicting gold prices with SARIMAX (time series)

This Jupyter notebook uses data from St. Louis Fed to make predictions about gold prices over the next three years.

![gold-chart](https://github.com/user-attachments/assets/f66c5355-9b42-41ac-8906-d6564cea9962)

At the time this prediction was published, gold closed at $2,756.70.

# Hypothesis testing

I ran a separate hypothesis test with the null hypothesis: "Inflation is not a statistically significant factor in determining gold prices."

The P>|t| was .202, well above the threshold of 0.05 to reject the null hypothesis.
The R-squared is 0.044 meaning only 4.4% of the gold price can be explained by inflation.

This gave me more confidence in the SARIMAX result.
