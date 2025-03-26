# 🚑 Medical Diagnosis App

The **Medical Diagnosis App** helps users identify potential diseases based on their symptoms. Users can select the affected part of their body and enter their symptoms, and our trained model will analyze the input to predict the probability of possible diseases.

**🔥 Features**

1. Interactive body part selection for symptom input

2. AI-powered disease prediction model

3. Probability-based diagnosis for better insights



**🛠️ Technologies Used**

1. Google Colab – For training the machine learning model
   
2. Streamlit – For building an interactive web application

3. Python & Machine Learning Libraries – Used for data processing and disease prediction


**🧠 Machine Learning Model**

1. Trained on: Final_Augmented_dataset_Diseases_and_Symptoms (From Kaggle)

2. Algorithms Used:
      - Random Forest Classifier – For robust and accurate disease classification
      - HistGradientBoosting Classifier – For improved performance and efficiency

3. Preprocessing:
      - Used Label Encoding to convert disease names into numerical labels
      - Train-Test Split (80-20%) for model evaluation

4. Evaluation: Measured accuracy and classification performance

**🔗 Link to our full prototype:**

https://www.figma.com/proto/t95yblPqfTazERG8pXE4mv/Vhack-Champion!?node-id=0-1&t=XnaDcbLwL65422Po-1

[![Open in Streamlit](https://static.streamlit.io/badges/streamlit_badge_black_white.svg)](https://blank-app-template.streamlit.app/)

**🚀 How to run it on your own machine**

1. Install the requirements

   ```
   $ pip install -r requirements.txt
   ```

2. Run the app

   ```
   $ streamlit run streamlit_app.py
   ```
