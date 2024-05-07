# Investment-Decision-Recommendation-System
This project involves a comprehensive analysis and development of a recommendation system for investment decisions using a detailed dataset. The process can be summarized in several key phases:

**Data Exploration:**
1. **Demographic Analysis:** The dataset includes information on gender, marital status, and age. Findings include:
   - Houston has the highest number of investors.
   - Unmarried individuals invest slightly more than married ones.
   - Gender does not significantly impact investment decisions.
   - Prime working and early working populations are more likely to invest, especially prime working married women in all cities and elderly women in San Francisco.
   
2. **Employment Details:**
   - Higher investments are seen among top executives and those with tertiary education.
   - A specific finding notes that advertising and promotion executives earning over US$17500, even with only primary education, tend to invest more.
   
3. **Investment Behavior:**
   - Older age groups and households with fewer members generally show a higher likelihood of investing, except for the early working age group.
   - Sources such as the Internet and advice from financial advisors, coupled with a moderate to advanced knowledge of investment products and the share market, correlate with higher returns.
   - Investment aimed at wealth accumulation typically yields higher returns, particularly with lower risk levels and better investment knowledge.

**Model Development and Recommendation System:**
1. **Data Preprocessing:** Includes loading data, handling missing values, and encoding categorical variables.
2. **Model Training:** Uses RandomForest for risk level and return predictions, splits data for training and testing, and then trains the models.
3. **Feature Importance Analysis:** Identifies critical features affecting risk and return through trained models.
4. **Recommendation System Development:**
   - Based on the importance analysis, the system focuses on 'Knowledge level about different investment products' and 'Knowledge about the share market'.
   - After testing various models, a Decision Tree Classifier was chosen for risk prediction and an SVM model for return prediction.
   - These models take user input on knowledge levels to predict risk and potential returns, offering guidance on how to enhance knowledge to minimize risks and maximize returns.

**Conclusion:**
The recommendation model effectively uses user-input knowledge levels to predict risk and return on investments. The system is designed for ongoing refinement and tuning to improve its accuracy and effectiveness in making investment decisions. This approach allows investors to make informed decisions based on their demographic and employment characteristics as well as their understanding of investment avenues.
