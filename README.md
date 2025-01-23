# 📊 Sentiment Analysis Using NLP

## 🚀 Project Overview

This repository contains code and data for performing **Sentiment Analysis** on product reviews. The analysis focuses on extracting and analyzing sentiments from user-written product reviews, using only the "reviewText" column.

The primary goal of this project is to classify the sentiment (positive, negative, or neutral) conveyed in the review text. This can be useful for gaining insights into customer opinions and improving business decision-making. 🛠️ 
 
## 📁 Dataset
 
The dataset includes the following key columns:
- **📝 reviewerName**: Name of the reviewer. 
- **⭐ overall**: Product rating provided by the reviewer (1 to 5).    
- **💬 reviewText**: The text of the review, which will be used for sentiment analysis.     
- **📅 reviewTime**: Date when the review was written.  
- **📉 day_diff**: Difference in days between the review date and the analysis date.   
- **👍 helpful_yes**: Number of helpful votes the review received.  
- **👎 helpful_no**: Number of non-helpful votes the review received. 
- **📊 total_vote**: Total votes (helpful + non-helpful).
- **⚖️ score_pos_neg_diff**: Difference between helpful and non-helpful votes.
- **📈 score_average_rating**: Average rating based on helpful votes.
- **🏅 wilson_lower_bound**: Wilson score lower bound for ranking review helpfulness.

## 🎯 Key Objective

- Perform sentiment analysis on the **reviewText** column. 🧠
- Classify reviews into positive, negative, or neutral sentiment categories. 🔍
- Visualize and interpret results to understand customer opinions better. 📊

## ⚙️ Requirements

To run the project, you will need the following Python libraries: 

- pandas 🐼
- numpy 🔢
- scikit-learn 🧠
- nltk 🌐
- matplotlib 📊

You can install them by running:  

```bash
pip install pandas numpy scikit-learn nltk matplotlib  
```

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.
