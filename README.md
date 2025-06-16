# Emotion-Detection-Text-Based--NLP-project

Milkesa Kumera Jaleta

1. Setup Environment
Install all necessary Python libraries including pandas, numpy, seaborn, neattext, scikit-learn, joblib, streamlit, and altair to ensure smooth execution of the project.

2. Load Dataset
Load your raw emotion-labeled text dataset using a suitable tool for CSV file reading.

3. Data Cleaning
Clean the text data by removing user handles and common stopwords using appropriate text preprocessing techniques.

4. Prepare Features and Labels
Extract the cleaned text as input features and the corresponding emotion labels as target variables.

5. Split Dataset
Divide the dataset into training and testing sets, typically using a 70/30 split, to prepare for model training and evaluation.

6. Build Machine Learning Pipeline
Create a pipeline that first converts text data into numerical vectors using text vectorization methods and then applies a Logistic Regression classifier for emotion prediction.

7. Train the Model
Train the machine learning pipeline using the training data to learn patterns that associate text with emotions.

8. Evaluate the Model
Assess the trained model’s performance by measuring its accuracy on the test dataset.

9. Save the Model
Save the trained machine learning pipeline to a file for later reuse without needing to retrain.

10. Build the Streamlit Web Application
Develop a web application interface using Streamlit that allows users to input text and receive predicted emotion labels along with confidence scores and visual probability distributions.

11. Run the Web Application
Run the Streamlit app locally and open the provided URL in a web browser to interact with the emotion detection system in real-time.

12. Test Questions

Sadness – "I tried so hard, but it still wasn't enough."-----
Joy – "This is the best day of my life!"--------
Joy – "I can’t stop smiling today."------
Joy – "Being with you makes everything better."-----
Fear – "I can’t breathe when I think about it."------
Anger – "That comment was absolutely vile."---
Shame – "I feel horrible about the way I acted."****
Joy – "Everything is finally coming together!"-----
Fear – "I'm afraid they’ll find out the truth."----
