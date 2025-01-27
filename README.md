# Brain Tumor Detector and Classifier
# Overview
This web application is designed to assist neurologists, neuro-oncologists, and neurosurgeons in detecting brain tumors and classifying them into categories such as No Tumor, Glioma, Meningioma, and Pituitary. It provides explanatory insights and detailed reports to support early diagnosis, helping medical professionals make informed decisions.
Want to see the detailed demo and dive deeper into the project’s future improvements? Check it out here: [link]

## Key Features:
* Tumor Detection & Classification: Detects and classifies brain tumors in MRI scans into four categories: No Tumor, Glioma, Meningioma, Pituitary.
* Deep Learning Models:
    * Xception model (using transfer learning)
    * Custom CNN (built with a custom deep learning architecture)
    * Achieved 99% accuracy in tumor detection and classification.
* AI-Powered Insights: Integrates Gemini 1.5 Flash, a large language model, to interpret CNN findings and highlight areas of the MRI scan contributing to the predictions.
* Interactive Interface: Built with Streamlit, providing a simple UI to upload MRI scans and view predictions.
* Visualization: Includes bar charts, radar charts, and saliency maps to aid interpretation of model predictions.



# Running Locally
Install the requirements, add your API key to your .env file and run the program

Install Requirements: Install the required dependencies by running:
```
pip install -r requirements.txt
```
Add Your API Key: Create a .env file in the project root and add your Gemini API key:
```
GOOGLE_API_KEY = your-api-key-here
```
Run the Application: Launch the app with the following command
```
streamlit run app.py
```
