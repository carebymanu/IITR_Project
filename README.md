# IITR_Project
IIT Ropar Final Project (iitrprai_24091692)

# “AI-Driven IT Service Management Automation using NLP and Knowledge-Based Systems”¶
AI-Based Incident Categorization and Resolution Recommendation System

ABSTRACT (What, Why, How, Results)
What This project proposes an AI-driven IT Service Management (ITSM) system that automates incident classification, complaint registration, and knowledge resolution using Natural Language Processing (NLP).

Why Traditional service desks rely heavily on manual classification and engineer experience, leading to delays, inconsistency, and high operational costs in large retail IT environments.

How The system uses TF-IDF based NLP models and Logistic Regression to:

Classify incidents into categories

Register complaints using site and inventory validation

Retrieve solutions from a Knowledge Error Database (KEDB)

Results The solution achieved ~74% classification accuracy on real ticket data and successfully automated complaint handling and knowledge resolution workflows.

Problem Definition
Retail IT support teams receive thousands of incident tickets daily. Manual categorization and resolution selection increases response time and errors.

Objective
Predict incident category using NLP and Machine Learning
Recommend possible resolution based on similar past incidents
Real-World Relevance
Faster ticket routing improves store uptime and reduces business losses in retail operations.


# METHODOLOGY (Approach & Architecture)¶
Overall Architecture

User Input ↓ NLP Preprocessing ↓ TF-IDF Vectorization ↓ Logistic Regression Classifier ↓ Category / Issue Prediction ↓ KEDB Knowledge Retrieval

Algorithms Used

TF-IDF Vectorizer

Logistic Regression

Cosine Similarity (Resolution Recommendation)

# DATA UNDERSTANDING & PREPARATION¶
Dataset Source

Collected from a real retail IT support environment

Stored in Excel format

Files Used

File	Purpose
tickets.xlsx	Historical incident data
Sites.xlsx	Site master
Inventory.xlsx	Asset inventory
Complaints.xlsx	Complaint register
KEDB.xlsx	Knowledge base
KEDB_Solution.xlsx	Solutions
Preprocessing Steps

Missing value handling (fillna)

Text concatenation (TITLE + DESCRIPTION)

Column cleaning

Feature engineering (TEXT column)

# CONCLUSION & FUTURE SCOPE¶
Conclusion

The project demonstrates how AI can significantly enhance ITSM efficiency by automating classification, complaint handling, and knowledge resolution.

Future Scope

Deep learning models (BERT)

SLA breach prediction

Web-based UI (Streamlit)

Integration with ServiceNow / Jira
