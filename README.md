# Resume Classifier using Machine Learning and NLP
### Project Overview
This project focuses on classifying resumes based on their skills using natural language processing (NLP) and machine learning techniques. The dataset, downloaded from Kaggle, contains two columns: Category and Resume (Skills) with a shape of (962, 2). The goal is to accurately categorize resumes into predefined categories using text data.

### Key Features
Data Visualization: Used Seaborn and Matplotlib to explore and visualize key patterns in the resume data.
Data Preprocessing: Employed regular expressions and NLP techniques to clean and filter the data, removing special characters, unnecessary spaces, and more.
Vectorization: Converted the textual resume data into numerical vectors using techniques like TF-IDF for input into machine learning models.
Machine Learning Models: Implemented multiple classifiers, with the K-Nearest Neighbors (KNeighbors) Classifier achieving the highest accuracy of 98.444%.
Model Deployment: Created a pickle file for the trained model and used it in a simple Streamlit web app to classify resumes in real-time.
### Dataset
Source: Kaggle Dataset 
Shape: (962, 2)
Columns:
Category: The job category for which the resume is suitable.
Resume (Skills): Text data listing the candidate’s skills and experience.
### Tools & Libraries
Python: For data manipulation, preprocessing, and model building.
Pandas: Data handling and manipulation.
Seaborn & Matplotlib: Data visualization.
Scikit-learn: For model building, vectorization, and evaluation.
NLTK & re: For text preprocessing.
Streamlit: For creating the web application.
Pickle: To save the trained model.
Model Performance
After testing multiple models, the KNeighbors Classifier was the top performer with an accuracy of 98.444%.

### Future Work
Explore other advanced NLP techniques and models like BERT or Transformers.
Integrate a feedback loop in the Streamlit app to improve model performance over time.
Enhance the web interface with better UX design.
