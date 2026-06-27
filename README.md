# 📞 Customer Support Ticket Analysis (Python)

## 📌 Project Overview

This project analyzes customer support ticket data using **Python** to identify common customer issues, classify tickets by priority, and extract meaningful insights from issue descriptions. The analysis involves cleaning and preprocessing text data before performing descriptive analysis on ticket priorities, issue descriptions, and frequently occurring words.

The objective is to understand recurring customer concerns and provide actionable insights that can help improve customer support services.

---

## 📂 Dataset Summary

The dataset contains **16 customer support tickets**, with each record including:

* Ticket Number
* Customer Name
* Issue Description
* Priority Level

---

## 🎯 Project Objectives

* Clean and preprocess customer issue descriptions.
* Standardize text for accurate analysis.
* Analyze ticket distribution based on priority.
* Identify the longest issue descriptions.
* Extract unique words from customer issues.
* Discover common themes and recurring customer complaints.

---

## 🛠️ Technologies Used

* Python
* Pandas
* String Operations
* Regular Expressions (re)
* Collections (Counter)

---

## 🧹 Data Preprocessing

The issue descriptions were cleaned by:

* Removing punctuation
* Converting text to lowercase
* Standardizing text formatting
* Tokenizing words for analysis

These preprocessing steps improved the consistency and accuracy of the text analysis.

---

## 📊 Analysis Performed

### Priority Analysis

The customer support tickets were classified into three priority levels:

| Priority | Number of Tickets |
| -------- | ----------------: |
| High     |                 6 |
| Medium   |                 4 |
| Low      |                 6 |

**Observation:**

* High-priority and low-priority tickets occurred equally often.
* Medium-priority tickets were less frequent.

---

### Longest Issue Descriptions

The maximum issue description length was **5 words**.

The following tickets contained the longest descriptions:

| Ticket | Customer | Issue Description                |
| ------ | -------- | -------------------------------- |
| 2      | Meera    | slow response very poor service  |
| 7      | Arjun    | good support and good behavior   |
| 8      | Kiran    | poor handling of technical issue |
| 16     | Sukanya  | website is not loading properly  |

These descriptions primarily highlight customer service quality, technical support, and website-related issues.

---

### Unique Word Analysis

A total of **46 unique words** were identified from the issue descriptions.

Frequently occurring words included:

* support
* service
* slow
* poor
* response
* issue
* technical
* website
* good
* excellent

This analysis helped identify recurring customer concerns and frequently mentioned topics.

---

## 🔍 Key Findings

* Slow response and service-related issues were among the most common customer complaints.
* Technical issues such as website loading problems, mobile application freezing, and report download failures appeared multiple times.
* Positive customer feedback was also observed, including appreciation for good support, helpful guidance, and excellent service.
* Cleaning and standardizing the text significantly improved the quality of the analysis.

---

## 📈 Conclusion

The analysis revealed that customer concerns primarily revolve around response time, service quality, and technical issues. At the same time, several customers expressed satisfaction with the support they received.

These insights can help customer support teams:

* Improve response times.
* Resolve technical issues more efficiently.
* Maintain high-quality customer service.
* Monitor recurring customer concerns for continuous improvement.

---

## 📁 Project Structure

```
Customer-Support-Ticket-Analysis/
│
├── Customer_Support_Ticket_Analysis.ipynb
├── customer_support_tickets.csv
├── README.md
```

---

## 🚀 Future Improvements

* Perform sentiment analysis on customer feedback.
* Generate word clouds for issue descriptions.
* Visualize ticket priorities using charts.
* Apply Natural Language Processing (NLP) techniques.
* Build a ticket classification model using machine learning.
