# Smart India Hackathon Workshop
# Date:30.09.2025
## Register Number:25012304
## Name:Kamali V
## Problem Title
SIH 25010: Smart Crop Advisory System for Small and Marginal Farmers
## Problem Description
A majority of small and marginal farmers in India rely on traditional knowledge, local shopkeepers, or guesswork for crop selection, pest control, and fertilizer use. They lack access to personalized, real-time advisory services that account for soil type, weather conditions, and crop history. This often leads to poor yield, excessive input costs, and environmental degradation due to overuse of chemicals. Language barriers, low digital literacy, and absence of localized tools further limit their access to modern agri-tech resources.

Impact / Why this problem needs to be solved

Helping small farmers make informed decisions can significantly increase productivity, reduce costs, and improve livelihoods. It also contributes to sustainable farming practices, food security, and environmental conservation. A smart advisory solution can empower farmers with scientific insights in their native language and reduce dependency on unreliable third-party advice.

Expected Outcomes

• A multilingual, AI-based mobile app or chatbot that provides real-time, location-specific crop advisory.
• Soil health recommendations and fertilizer guidance.
• Weather-based alerts and predictive insights.
• Pest/disease detection via image uploads.
• Market price tracking.
• Voice support for low-literate users.
• Feedback and usage data collection for continuous improvement.

Relevant Stakeholders / Beneficiaries

• Small and marginal farmers
• Agricultural extension officers
• Government agriculture departments
• NGOs and cooperatives
• Agri-tech startups

Supporting Data

• 86% of Indian farmers are small or marginal (NABARD Report, 2022).
• Studies show ICT-based advisories can increase crop yield by 20–30%.

## Problem Creater's Organization
Government of Punjab

## Theme
Agriculture, FoodTech & Rural Development

## Proposed Solution
1.Farmer Profile Setup
*Simple mobile app/SMS-based interface (multilingual support).
*Farmers register with land size, soil type, water availability, and location.
2.Soil & Weather Data Integration
*IoT-based soil sensors or manual input for soil health, pH, and moisture.
*Real-time weather forecasts from government APIs.
3.Crop Recommendation Engine
*AI/ML-based model suggests suitable crops based on soil, season, and market demand.
*Provides cost-benefit analysis for each suggested crop.
4.Fertilizer & Irrigation Advisory
*Tailored suggestions on fertilizer usage (NPK ratio, organic alternatives).
*Water scheduling based on soil moisture and weather predictions.
5.Pest & Disease Management
*Image-based pest detection (using smartphone camera).
*Instant advisory on pesticide/organic treatment.
6.Market Linkage & Price Alerts
*Real-time market price updates for crops.
*Connect farmers with nearby mandis, buyers, and FPOs.
7.Multichannel Communication
*Voice-based advisory (IVR) for farmers with low literacy.
*WhatsApp/SMS alerts for quick tips and warnings.
8.Government Schemes & Insurance Guidance
*Information on subsidies, crop insurance, and loan schemes.
*One-click application assistance
9.Data Analytics Dashboard
*For government/NGOs to track crop patterns, productivity, and farmer needs.
10.Scalability & Accessibility
*Works on low-end smartphones and offline mode.
*Regional language support for inclusivity.

## Technical Approach
1.System Architecture
*Frontend: Mobile App (Android, low-data optimized) + Web Dashboard.
*Backend: Cloud-based server (AWS/Azure/GCP) with APIs.
*Database: NoSQL (MongoDB) for farmer profiles & crop data, SQL (PostgreSQL/MySQL) for structured analytics.
2.Data Collection Layer
*Soil Data: IoT sensors / manual input.
*Weather Data: API integration (IMD, OpenWeather).
*Market Data: Government agri-market AIs.
*Pest/Disease Data: Image inputs → processed by ML model.
3.AI/ML Modules
Crop Recommendation Engine:
*Inputs: Soil, climate, water availability, past yield data.
*Model: Decision Tree/Random Forest, trained on agri datasets.
*Pest/Disease Detection:
CNN (Convolutional Neural Network) for image classification.
*Yield Prediction:
Regression models with weather + soil + crop inputs.
4.Advisory Engine
*Rule-based + ML-driven system for fertilizer, irrigation scheduling.
*Multilingual NLP (Natural Language Processing) for advisory in local languages.
*Voice-based IVR integration for non-literate farmers.
5.Communication Layer
Push notifications in app.
*SMS/USSD alerts for feature phone users.
*WhatsApp/Telegram bot for advisory delivery.
6.Security & Privacy
*End-to-end encryption of farmer data.
*Role-based access for government/NGO dashboards.
7.Scalability & Accessibility
*Microservices architecture for modular expansion.
*Offline mode with data sync when connected.
*Lightweight UI optimized for low bandwidth.

<img width="615" height="350" alt="Screenshot 2025-09-30 111023" src="https://github.com/user-attachments/assets/29c189a7-d049-4d23-b2d1-cca7993eb8bd" />


## Feasibility and Viability
1.Feasibility
*Technical: Uses existing tech (IoT sensors, mobile apps, AI/ML models, APIs). Lightweight apps ensure low internet dependency.
*Economic: Low-cost deployment with scalable cloud services; affordable for farmers via government/NGO support.
*Operational: Easy-to-use (voice, SMS, multilingual), fits into current farming practices.
2.Viability
Farmer Impact: Increases yield, reduces crop loss, improves income.
Scalability: Can expand from one region to nationwide with modular design.
Sustainability: Supports organic methods, efficient resource use, and aligns with government digital agriculture initiatives.

## Impact and Benefits

1.Impact
*Empowers small and marginal farmers with data-driven decisions.
*Reduces crop failure risk through timely weather, pest, and irrigation alerts.
*Improves income stability by linking farmers to real-time market prices.
*Promotes sustainable farming with optimized water, fertilizer, and pesticide use.
2.Benefits
*Higher productivity & yield.
*Lower input costs (fertilizer, water, pesticide).
*Better market access & fair prices.
*Inclusive access through multilingual, voice, and SMS support.
*Alignment with government schemes & digital agriculture goals.


## Research and References
1.Research
*Studies show small and marginal farmers (over 85% of Indian farmers) face challenges in crop selection, input usage, and market access.
*AI/ML-based crop advisory models have proven effective in improving yield and reducing losses.
*Government initiatives like Digital Agriculture Mission (DAM) and eNAM provide APIs and datasets for integration.
*Success stories from platforms like Kisan Suvidha, Rythu Bharosa, and Precision Agriculture highlight feasibility.
2.References
*Indian Council of Agricultural Research (ICAR) reports on crop productivity.
*FAO – Smart farming and digital agriculture practices.
*IMD (Indian Meteorological Department) – Weather and climate APIs.
*eNAM – National Agriculture Market portal.
*Research papers on AI/IoT in agriculture (Springer, IEEE, Elsevier).
