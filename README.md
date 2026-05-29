# Automated IT Service Desk Ticket Classification

## Project Overview
This project applies Natural Language Processing (NLP) and 
Machine Learning to automatically classify IT service desk 
tickets into categories and route them to appropriate 
assignment groups.

## Dataset
- Total Tickets: 1,56,005
- Features: Short Description, Category, Priority, 
  Subcategory, Assignment Group
- Source: IT Service Management Dataset

## Models Built
| Model | Algorithm | Accuracy |
|-------|-----------|---------|
| Category Prediction | LinearSVC + TF-IDF | 87.44% |
| Assignment Group | LinearSVC + TF-IDF | 88.90% |

## Technologies Used
- Python 3
- Pandas
- Matplotlib & Seaborn
- Scikit-learn
- WordCloud
- Jupyter Notebook

## Project Structure
- IT_Ticket_Classification.ipynb — Main notebook

## How to Run
1. Install Anaconda
2. Open Jupyter Notebook
3. Run cells in order from Cell 1 to Cell 9

## Results
- Category Prediction Accuracy: 87.44%
- Assignment Group Accuracy: 88.90%

## Author
Suraj Kumar
B.Sc. (Honours) Data Science and Artificial Intelligence
IIT Guwahati
