# Resume_Categorization_Application

Key Insights for [Project 36 : Resume Categorization Using Machine Learning](https://www.youtube.com/watch?v=JKlX_o0iDSA) by [Merlin AI](https://merlin.foyer.work/)

**Overview of Resume Categorization Project**  
- The project focuses on categorizing resumes using Python and machine learning techniques.  
- The application allows users to upload resumes in PDF format and categorize them based on job roles such as Java Developer, Data Scientist, and Business Analyst.  
- The results can be downloaded in CSV format for further analysis or record-keeping.

**Application Features**  
- Users can select and upload multiple resumes, which the application processes to categorize them automatically.  
- The application organizes categorized resumes into specific folders like "Data Science," "Java Developer," and "Business Analyst."  
- It also provides an option to delete resumes from the selected list, ensuring a user-friendly experience.

**Machine Learning Implementation**  
- The project utilizes various libraries including pandas, NumPy, and scikit-learn for data handling and machine learning model training.  
- The categorization is based on supervised learning, where the model is trained on a dataset containing resumes and their corresponding job categories.  
- Techniques such as TF-IDF (Term Frequency-Inverse Document Frequency) are used for feature extraction from text data.

**Data Processing Pipeline**  
- Resumes are uploaded in PDF format, with a requirement for text extraction to feed into the machine learning model.  
- The application includes functions for cleaning the text data by removing URLs, special characters, and stop words to enhance the quality of the input for model training.  
- A level encoder is used to convert categorical job titles into numerical values to facilitate model training.

**Model Training and Evaluation**  
- The project employs various machine learning algorithms including K-Nearest Neighbors (KNN), Logistic Regression, and Random Forest for classification tasks.  
- The accuracy of models is evaluated using a test dataset, with notable accuracy rates reaching up to 99% for some classifiers.  
- The best-performing model is selected for categorization tasks and can be saved for future use.

**Web Application Development**  
- The application is built using Streamlit, allowing for a simple web interface that facilitates user interaction.  
- It includes features for file uploads, displaying results, and categorizing resumes directly from the browser.  
- The interface is designed for ease of use, enabling users to navigate through options for uploading and categorizing resumes seamlessly.
