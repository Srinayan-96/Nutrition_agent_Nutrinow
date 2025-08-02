# Nutrition Agent – NutriNow


<img width="879" height="696" alt="image" src="https://github.com/user-attachments/assets/474f46e2-7110-4ff3-81c6-d392ec9447eb" />


A smart AI-powered assistant that offers personalized meal plans based on your dietary habits, lifestyle, allergies, and health goals. Using the power of IBM Watsonx.ai and Granite models, NutriNow acts as a 24/7 intelligent dietician—helping users make informed, healthy food choices with detailed reasoning.

### Problem Statement  
In today’s fast-paced world, individuals are more health-conscious than ever. However, most nutrition apps provide generic advice and fail to address personal needs like food allergies, cultural preferences, or specific health goals. There's a gap between available tools and real human-like nutrition guidance. This project aims to bridge that gap using Generative AI.

### Proposed Solution  
NutriNow is an AI Nutrition Assistant trained using IBM Watsonx.ai that takes in your age, diet, health goal, and allergies to create tailored meal plans. It explains its choices and adapts with feedback. It behaves like a real dietician—scalable, intelligent, and always available.

### Technologies Used  
- IBM Watsonx.ai (Generative AI)  
- IBM Granite Foundation Model  
- IBM Cloud Object Storage  
- Flask (Python backend)  
- HTML, CSS & JavaScript (Frontend)  
- IBM IAM for secure authentication  
- Natural Language Processing (NLP)

### IBM Cloud Services Used  
- Watsonx.ai Studio  
- IBM Granite Model  
- IBM Cloud Object Storage  
- IBM IAM for token-based access  
- IBM Cloud Lite account  

### End Users  
- Health-conscious individuals  
- Fitness enthusiasts and trainers  
- Dieticians seeking AI support  
- Students and working professionals  
- Senior citizens with dietary needs  
- Individuals with allergies or chronic health conditions  

### WOW Factors  
- Personalized 1500-calorie meal plans generated instantly  
- Considers dietary type, allergies, and fitness goals  
- Built entirely on IBM Watsonx and Granite models  
- Offers nutritional explanations with every recommendation  
- No app installation—runs in any modern browser  
- Easy to embed in websites, apps, or health platforms  

### Key Features  
- Simple HTML form for entering inputs  
- Flask-based backend that communicates with Watsonx API  
- JSON input/output for clean integration  
- Customizable .env configuration  
- Friendly UX and clear error feedback  

### How It Works  
1. The user fills out a short form with age, diet, goal, and allergies  
2. The Flask server reads input and sends it to the Watsonx model  
3. The AI model returns a detailed and contextual meal plan  
4. The plan is displayed directly on the webpage  

### Screenshots  
Agent Setup

![Agent Setup](https://github.com/user-attachments/assets/a42e8054-d1f0-41e4-bb62-dcc44dae6bc7)

Agent Instructions

![Agent Instructions](https://github.com/user-attachments/assets/99011531-ad5c-4c9a-8464-2d15a4c2b91f)

Agent Tools

![Agent Tools](https://github.com/user-attachments/assets/b70496f5-d4cd-474e-be56-52adf14e6e86)

Quick Questions

![Quick Questions](https://github.com/user-attachments/assets/5e4f91c4-208f-4613-980d-b655dbf73dcf)

Resource List

![Resource List](https://github.com/user-attachments/assets/8e84410d-c876-44a5-bdf1-d7afd3c95d55)

API References  
![API References](https://github.com/user-attachments/assets/b01b0457-3247-48aa-a5a7-3f566fcf3400)

Agent Preview

![Agent Preview](https://github.com/user-attachments/assets/ca5ed4fd-0f8b-4563-a913-da488bb3e322)

Agent Testing 

![Agent Testing](https://github.com/user-attachments/assets/ebb903ea-b4c1-4807-be68-3abe097381d8)


### How to Run Locally  
1. Clone this repository  
2. Create a `.env` file and add your IBM Watsonx API key and endpoint  
3. Run `pip install -r requirements.txt`  
4. Launch the server: `python app.py`  
5. Open your browser and go to `http://localhost:5000`

### Deployment  
- Watsonx.ai Studio is used for model deployment  
- Frontend and backend can be hosted on services like Render, Replit, or IBM Code Engine  
- Static HTML can be deployed using GitHub Pages or Netlify  

### Future Scope  
- Add voice interaction using Watson Speech-to-Text  
- Upload grocery photos to suggest smart food swaps  
- Generate shopping lists based on meal plans  
- Daily reminders and WhatsApp integration  
- Integration with fitness trackers and wearables  

### Useful Links  
- [IBM Watsonx.ai](https://www.ibm.com/products/watsonx-ai)  
- [IBM Cloud Lite Account](https://cloud.ibm.com/registration)  
- [Watsonx Documentation](https://cloud.ibm.com/docs/watsonx)  
- [Flask Docs](https://flask.palletsprojects.com)
