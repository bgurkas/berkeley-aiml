# Part 3
The prompt for Part 3 was "Comparing Classifiers" for a bank-related prediction task.

Details of the investigation can be found <a href="prompt_III.ipynb">here</a>.

# Non-technical Report of Findings
Four different types of prediction models were considered to predict whether a customer will subscribe to a term deposit based on their demographic and financial information. These models were tested with different parameters to fine-tune their accuracy and cross-validated at least 3 times across the data available.

Upon fine-tuning, all four models reached similar levels of accuracy. (88.8%) <mark>From here, there are 2 options:</mark>

1) Accept the accuracy as-is and use any of the models to predict the business question
2) Look to improve the accuracy of the models by considering more information about the data.

Frequency of contact information, and other bank-side information were excluded from the study due to resource limitations. However, the additional information gained from these features would shed more light on the true correlations between the data and a customer's decision of subscription.