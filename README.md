# NurseJoy.ai

NurseJoy.ai is an interactive healthcare assistant web application built with Streamlit. It supports patients, clinicians, and analysts with tailored functionalities to improve diagnosis, booking, medicine information, nutritional guidance, report analysis, and geospatial navigation.

---

## Setup Instructions

1. *Python Version*  
   Make sure you are using *Python 3.10* for compatibility.

2. *Install dependencies*  
Download and install all required packages via: pip install -r requirements.txt
Run the app
Launch the Streamlit app with:  streamlit run app.py


Application Features

First-Time Registration
Upon first login, select your role: Patient, Clinician, Analyst

Patient Role
DrOak.ai: Quickly input symptoms for a brief diagnosis. The system assigns a doctor to the patient automatically. enhanced with datasets of diseases and symptoms.

NurseJoy.ai Booking Form: Book appointments with a simple diagnosis to prepare for the visit.

Medicine Identification: Get detailed information on medicine dosage and usage.

Nutritional Menu: Receive recipe suggestions based on available ingredients to aid healing.

Indoor Navigation: Navigate the Seri Botani Hospital using geospatial data integration for easy wayfinding.

Clinician Role
Upload raw patient reports to generate:

Suggested next steps in patient care

Identification of secondary concerns

Detection of data gaps

Highlight critical health issues

Analyst Role
Upload raw social media reports with metadata (date, time, location, author, source) to obtain:
Alert summaries, Threat indicators, Credibility scores, Urgency flags

Geospatial Web Apps

We build interactive geospatial web applications using Leafmap and Streamlit to enhance patient journey experience and hospital navigation.

## Technology Stack

- **Kaggle**  
  Used as a primary source for curated datasets to train and validate our models, especially healthcare and social media data.

- **Jamaibase (LLM)**  
  Integrated large language model (LLM) services via Jamaibase for natural language understanding and generation. This powers features like symptom diagnosis, report summarization, and intelligent recommendations.

- **Streamlit**  
  The entire web application is developed with Streamlit, enabling fast, interactive, and user-friendly front-end interfaces for patients, clinicians, and analysts.

- **Leafmap**  
  Utilized for building interactive geospatial web applications that enhance patient navigation and hospital wayfinding.

These technologies work together to create a seamless healthcare assistance platform that combines AI, data analytics, and intuitive UI.

## Google drive link: 
Disease Database to Enhance LLM
https://drive.google.com/drive/folders/1WCxFV9OD32HPKMgdUz-8OY8w7T99CXRT?usp=drive_link

Contact / Support
For questions or support, please contact the HotSauce

Thank you for using NurseJoy.ai!
