# Mobile-Price-Analyst

What This Project Is About This notebook uses Python and machine learning to:  Understand which features (like battery power, RAM, camera quality, etc.) influence a mobile phone’s price.  Visualize interesting patterns in the data.  Build a machine learning model that can predict the price range of a phone (Low, premium )  based on its specs.

# What This Project Is About

This notebook uses Python and machine learning to:

Understand which features (like battery power, RAM, camera quality, etc.) influence a mobile phone’s price.

Visualize interesting patterns in the data.

Build a machine learning model that can predict the price range of a phone (Low, Medium, High, or Premium) based on its specs.

### Why It’s Interesting
Smartphones have tons of features, but do they all matter equally when it comes to price?

# For example:

A phone with 4000 mAh battery, 8GB RAM, and a dual SIM is likely to be more expensive than one with 2000 mAh, 2GB RAM, and a single SIM. But what if it has no 4G? 

This project finds which features are most important for pricing using tools like:

Correlation heatmaps 

Feature importance plots 

Random Forest Classifier 

# Tools and Technologies Used

Python 

Pandas, Numpy for data handling

Seaborn, Matplotlib for visualization

Scikit-learn for ML modeling

Jupyter Notebook for analysis

#  Highlights from the Project
 Data Visualization: We created heatmaps and bar charts to understand trends in the mobile features.

Feature Selection: Identified the most important features like battery power, RAM, and 4G capability.

Model Building: Used a Random Forest Classifier with 91% accuracy to predict the price range of unseen phones.

 Testing the Model: Evaluated the model with metrics like accuracy, confusion matrix, and classification report.

### Example Prediction
Let's say we have a mobile phone with:

3000 mAh battery

4GB RAM

8 MP front camera

Supports 4G

The model predicts:

Medium Price Range

Just like that, we can predict the price category of any mobile phone using its features!

# What You Can Learn
How to clean and prepare a dataset

How to perform exploratory data analysis (EDA)

How to train and evaluate a machine learning model

How to interpret model results and feature importance


# Future Improvements
Add a Streamlit web app to make predictions interactively 

Try deep learning or other ML models

Add more real-world mobile data

## 🙌 Let's Connect!
### If you liked this project or want to collaborate on something similar, feel free to reach out or star the repo! ⭐

