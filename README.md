# Introduction
The goal of this project is to analyze biodiversity data from the National Park Service, focusing on the various species observed across different national parks. The analysis aims to understand the distribution of species, identify those that are at risk, and examine the relationships between species and their conservation statuses.
# Methodology
The analysis was conducted using two datasets: 'species_info.csv' containing information about species, and 'observations.csv' containing species observations across different parks. The data was loaded into pandas DataFrames for analysis. Several techniques were used, including data cleaning, descriptive statistics, and visualization. Additionally, statistical tests, such as the Chi-squared test, were applied to assess the significance of relationships between variables.
## Findings
# Distribution of Conservation Status
The distribution of conservation statuses across species revealed that a significant number of species are classified as 'Species of Concern', with a smaller number being endangered or threatened. This distribution highlights the need for targeted conservation efforts.
Statistical Significance of Species Conservation
A Chi-squared test was conducted to assess whether certain species categories (e.g., mammals, birds) are more likely to be protected compared to others. The results showed that the differences were not statistically significant (p-value > 0.05), suggesting that protection efforts are not biased towards any particular species category.
# Conclusion
The analysis provides valuable insights into the biodiversity present in national parks. While certain species are more at risk, the overall distribution suggests that conservation efforts are balanced across species categories. However, continued monitoring and targeted conservation strategies are necessary to maintain biodiversity in these protected areas.
