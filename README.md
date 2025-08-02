# Nutrition_agent_Nutrinow
AI Nutrition Assistant
<img width="600" height="341" alt="image" src="https://github.com/user-attachments/assets/50872aca-4cea-4400-a851-cd0d3a1ec230" />

A smart AI-powered assistant designed to provide personalized meal plans based on your health goals, dietary preferences, allergies, and lifestyle. Built using IBM Watsonx.ai and IBM Cloud services, this agent helps you make informed nutritional choices with contextual explanations—just like a real dietician.

Problem Statement
In today’s fast-paced world, individuals are more aware of their health but often struggle to access reliable, personalized nutrition advice. Existing tools offer one-size-fits-all diets that overlook personal factors like allergies, fitness goals, culture, or lifestyle. There’s a need for a scalable AI-based solution that delivers adaptable, expert-like nutrition guidance at your fingertips.

Proposed Solution
An AI-powered Nutrition Agent trained using IBM Watsonx.ai that understands user inputs (age, goals, diet, allergies), and generates detailed, customized meal plans. The assistant uses generative AI to explain choices, adapt recommendations, and ensure safety—helping users maintain a healthier lifestyle.

Technologies Used
IBM Watsonx.ai (LLM-based generative AI)

IBM Granite Foundation Model

IBM Cloud Object Storage

Python (Flask)

HTML/CSS + JavaScript (Frontend)

IBM IAM (Authentication)

Natural Language Processing (NLP)

IBM Cloud Services Used
Watsonx.ai Studio

IBM Granite Model

IBM Cloud Object Storage

IBM Cloud Lite Account

IBM IAM for secure access and token generation

End Users
Health-conscious individuals

Students and working professionals

Dieticians needing AI support

Fitness coaches and trainers

Senior citizens with medical needs

People with allergies or dietary restrictions

WOW Factors
Personalized 1500-calorie meal plans in seconds

Considers diet type, allergies, and fitness goals

Built with Watsonx and IBM Granite on IBM Cloud

Provides nutritional explanation with every meal

No installation needed—runs in the browser

Easily integrable with web or mobile apps

Key Features
Easy-to-use HTML form for user inputs

Fast and secure Flask backend

Custom API integration with Watsonx endpoint

JSON-based request and response

Friendly error messages for better UX

How It Works
User submits age, diet, goal, and allergies via form

Flask backend sends data to Watsonx model

Model generates a meal plan using Granite LLM

Result is displayed with nutritional explanations

Screenshots
Agent_Setup:
<img width="1865" height="718" alt="Agent_setup" src="https://github.com/user-attachments/assets/a42e8054-d1f0-41e4-bb62-dcc44dae6bc7" />


Agent_Instrcutions:
<img width="1700" height="775" alt="Agent_Instructions" src="https://github.com/user-attachments/assets/99011531-ad5c-4c9a-8464-2d15a4c2b91f" />


Agent_tools:
<img width="875" height="679" alt="Agent_Tools" src="https://github.com/user-attachments/assets/b70496f5-d4cd-474e-be56-52adf14e6e86" />


Quick_Questions:
<img width="1752" height="709" alt="Quick_questions" src="https://github.com/user-attachments/assets/5e4f91c4-208f-4613-980d-b655dbf73dcf" />


Resource_List:
<img width="1751" height="907" alt="Resource_list" src="https://github.com/user-attachments/assets/8e84410d-c876-44a5-bdf1-d7afd3c95d55" />


Api_References:
<img width="1867" height="880" alt="API_refernces" src="https://github.com/user-attachments/assets/b01b0457-3247-48aa-a5a7-3f566fcf3400" />


Agent_Preview:
<img width="876" height="873" alt="Agent _previe1" src="https://github.com/user-attachments/assets/ca5ed4fd-0f8b-4563-a913-da488bb3e322" />


Agent_Testing:
<img width="1792" height="869" alt="Testing" src="https://github.com/user-attachments/assets/ebb903ea-b4c1-4807-be68-3abe097381d8" />




How to Run Locally
Clone the repository

Create a .env file with your Watsonx API key and endpoint

Run pip install -r requirements.txt

Start server: python app.py

Open localhost:5000 in your browser

Deployment
Deployed on IBM Watsonx.ai Studio (API)

Can be integrated with Render, Replit, Vercel, or IBM Code Engine

Frontend can be hosted with GitHub Pages or Netlify

Future Scope
Multimodal input (photo of meal/grocery)

Voice-based interaction with Speech-to-Text

AI-powered grocery list generation

Daily meal reminders via WhatsApp or SMS

Integration with wearable fitness devices

Useful Links
IBM Watsonx.ai

IBM Cloud Lite Account

Watsonx Documentation

Flask Official Docs



