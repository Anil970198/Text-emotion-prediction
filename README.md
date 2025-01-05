# Text Emotions Prediction

This project uses machine learning to predict the emotions conveyed in a given text input. The system classifies text into one or more of the following emotions: joy, fear, anger, sadness, disgust, shame, and guilt.

## Features

*Supports multi-class emotion classification.

*Utilizes n-gram features (1-gram to 4-gram) for text analysis.

*Implements multiple classifiers for training and testing:

*Support Vector Classifier (SVC)

* Linear SVC

* Random Forest Classifier

* Decision Tree Classifier

*Provides a graphical user interface (GUI) using Streamlit for user input and real-time prediction.

*Includes emoji representation for emotions.

# Installation 
1. Clone this reposiroty
   ```
   git clone https://github.com/your-username/text-emotions-prediction.git
   cd text-emotions-prediction```
  2. Install dependencies:```
   git clone https://github.com/your-username/text-emotions-prediction.git
   cd text-emotions-prediction```
  3. Launch the Streamlit app:
     ```
     streamlit run app.py
     ```
# Code Explanation
## Data Preprocessing
* Input File Format: Each line in the dataset should have a label enclosed in square brackets ([label]) followed by the text.
Example: ```
[1 0 0 0 0 0 0] I love programming!```
* `read_data(file)`: Reads the dataset file, extracts labels and text, and stores then in a list
* `convert_label(item,name)`:  Converts the binary label (e.g., `[1 0 0 0 0 0 0]`) into human-readable emotion names (e.g., joy).

# Visualization 
* Uses emojis to make predictions more intutitive and vuslally engaing.
* Emotion to Emoji Mapping:
* `joy`: 😂
* `fear`:😱
* `angeer`: 😠
* `sadness`:😢
* `disgust`: 😒
* `shame`:😳
* `guilt`:😳
