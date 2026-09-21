# AI Based Farmer Guidance and Agricultural Support System

An AI-assisted web platform that helps farmers make better decisions around soil health, crop selection, and day-to-day farming activities. Built as a final year engineering project, with a focus on making agricultural guidance more accessible through a simple, multilingual interface.

## Project Overview

Farmers often rely on scattered sources of information and guesswork for decisions that directly affect their yield. This project brings soil analysis, crop recommendations, a farming calendar, and an AI chatbot together in one platform, so farmers can get relevant guidance without needing to consult multiple sources.

The system also includes a disease detection feature based on image analysis, and supports English, Hindi, and Marathi to make it usable by a wider set of farmers.

## Key Features

- Soil analysis and crop recommendations based on user input
- Farming calendar to help plan seasonal activities
- AI chatbot ("Patil") for answering farming-related queries
- Basic plant disease detection using colour thresholding and contour analysis
- Multilingual support — English, Hindi, and Marathi
- Retrieval-based responses so chatbot answers stay grounded in relevant agricultural data

## Tech Stack

**Frontend:** React, TypeScript, Vite

**Backend:** Supabase, PostgreSQL

**AI/ML:** Google Gemini AI

## How It Works

1. A farmer enters details such as soil parameters or uploads a plant image.
2. For soil-based queries, the system analyzes the input and suggests suitable crops along with relevant farming schedule guidance.
3. For disease-related queries, the uploaded image is processed using colour thresholding and contour analysis to flag potential issues.
4. Integrated the Gemini API to develop an AI chatbot that provides agriculture-related guidance and answers user queries based on the provided context and prompts.
5. All of this is available in the farmer's preferred language.

## Installation & Setup

```bash
# Clone the repository
git clone https://github.com/SwarajBhaganagare13/AI-Based-Farmer-Guidance.git
cd AI-Based-Farmer-Guidance

# Install dependencies
npm install

# Set up environment variables
# Add your Supabase and Gemini API keys in a .env file

# Run the development server
npm run dev
```

You'll need a Supabase project set up with the required tables/edge functions, and a Google Gemini API key for the chatbot to work.

## Screenshots

### Sign Up / Login
<img width="1877" height="918" alt="SignUp" src="https://github.com/user-attachments/assets/763999c5-c107-4843-b567-1c40211615f4" />


### Dashboard
<img width="1897" height="962" alt="Dashboard" src="https://github.com/user-attachments/assets/8dddbf6f-fff7-495f-bb9d-5171727be6a7" />


### Soil Report
<img width="1891" height="949" alt="SoilReport" src="https://github.com/user-attachments/assets/b1550c16-9306-4d62-abd7-bdbac8b23dbd" />


### Smart Crop Calendar
<img width="1896" height="958" alt="Calendar" src="https://github.com/user-attachments/assets/c2059695-1baf-4012-89c6-33720e592490" />


### Patil AI Chatbot
<img width="577" height="746" alt="PatilAI" src="https://github.com/user-attachments/assets/695abe3d-ff93-4afc-8ad9-2d9c148f5c02" />


### Farmer Community
<img width="1896" height="957" alt="Community" src="https://github.com/user-attachments/assets/949ad806-0017-4800-bdf3-cd5d68905a96" />


### Agricultural News
<img width="1897" height="959" alt="News" src="https://github.com/user-attachments/assets/e93e9863-d6c3-443e-9005-bc75d7f9b962" />


## Future Scope

- Replace the rule-based disease detection with a trained CNN model for better accuracy
- Add weather-based alerts and recommendations
- Expand language support beyond English, Hindi, and Marathi
- Mobile app version for easier field access

## Author

**Swaraj Bhaganagare**
GitHub: [SwarajBhaganagare13](https://github.com/SwarajBhaganagare13)
LinkedIn: [Swaraj Bhaganagare](https://www.linkedin.com/in/swaraj-bhaganagare-95510a2b7/)
