🎓 College Event Feedback Analysis

Future Interns – Data Science & Analytics (Task 3)

📌 Project Overview

This project focuses on analyzing student feedback from a college event to understand overall satisfaction, identify improvement areas, and extract sentiment from textual responses using Natural Language Processing (NLP).

The goal is to help event organizers make data-driven improvements for future events.

🎯 Objectives

Analyze student feedback survey data

Perform data cleaning and preprocessing

Conduct sentiment analysis on textual feedback

Visualize satisfaction and sentiment trends

Provide actionable insights and recommendations

🧰 Tools & Technologies Used

Python

Google Colab

pandas – data manipulation

TextBlob – sentiment analysis

matplotlib & seaborn – data visualization

Google Forms – data collection

📂 Dataset Description

The dataset was collected using a Google Form and exported as a CSV file.

Columns:

event_name

overall_rating_(1-5)

which_session_did_you_like_the_most?

what_did_you_dislike?

suggestions_for_improvement

🧹 Data Cleaning Steps

Removed missing values from text feedback

Standardized column names

Prepared text data for sentiment analysis

🧠 Sentiment Analysis

Sentiment analysis was performed on the “Suggestions for improvement” column using TextBlob.

Sentiment Labels:

Positive → score > 0

Neutral → score = 0

Negative → score < 0

Each feedback entry was assigned:

sentiment_score

sentiment_label

📊 Visualizations

Distribution of overall ratings

Sentiment distribution (Positive / Neutral / Negative)

These visualizations help understand:

Student satisfaction level

General emotional tone of feedback

🔍 Key Insights

Majority of students provided Positive and Neutral feedback

Hands-on sessions and workshops were highly appreciated

Common improvement areas:

Event scheduling

Seating capacity

Communication and planning

Overall event rating indicates above-average satisfaction

✅ Recommendations

Improve time management and scheduling

Increase seating and crowd management

Extend duration of popular sessions

Enhance communication before and during events# FUTURE_DS_03

Conclusion

This project demonstrates how survey data and NLP techniques can be combined to extract meaningful insights from qualitative feedback.
Such analysis helps institutions improve event quality and student satisfaction using data-driven decisions.
