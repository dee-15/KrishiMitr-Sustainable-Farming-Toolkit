# KrishiMitr-Sustainable-Farming-Toolkit

**KrishiMitr** is an AI-powered platform that guides **new and existing farmers** through the **complete farming lifecycle** — from initial planning to sustainable maintenance.  
Tailored for the **Indian agricultural landscape**, KrishiMitr integrates real-time soil data, predictive analytics, and market intelligence to help farmers increase income, adopt sustainable practices, and simplify decision-making.

# Features

- **End-to-End Farming Roadmap** – From "Plan" to "Maintain" with AI-powered guidance.
- **Soil & Land Assessment** – Integrates **SISIndia API**, Soil Health Card Scheme, and CropIn data.
- **Direct-to-Consumer Marketplace** – e-NAM and DeHaat integration for better retail reach.
- **Funding Assistance** – Matches farmers to government schemes like PM-KISAN, PMFBY, AIF.
- **Step-by-Step Interactive Wizards** – Simplifies complex decisions with visuals and local-language support.
- **Sustainability Tracking** – Monitors adoption of eco-friendly and profitable farming practices.

---

# Tech Stack

- **Frontend:** React + Tailwind CSS  
- **Backend:** Python (Django)  
- **Database:** PostgreSQL  
- **AI/ML:** scikit-learn, pandas (predictive modeling & data analysis)  
- **Hosting:** Google Cloud Platform (GCP) with Docker for deployment  
- **APIs & Data Sources:**
  - SISIndia API – India-specific soil nutrients & pH data
  - e-NAM API – National Agriculture Market data
  - Soil Health Card Scheme data
  - CropIn – Remote sensing & farm monitoring

---

# Decision Rationale

- **React + Tailwind CSS** – Interactive, mobile-first UI for rural adoption.
- **Python + Django** – Stable, rapid development for data-heavy applications.
- **PostgreSQL** – Reliable relational DB for complex datasets like market transactions.
- **API Integrations** – Overcomes data collection barriers, delivers hyper-localized insights.
- **GCP + Docker** – Scalable deployment with minimal downtime.

---

# Innovation Highlights

- **Holistic approach**: Covers the full farming journey, unlike tools focusing on one stage.  
- **AI-powered Farm Toolkit**: Personalized guidance with location and soil-based recommendations.  
- **Integrated retail reach**: Direct market access through e-NAM & DeHaat.  
- **Smart funding suggestions**: Automated scheme-matching and simplified application flow.  

---

# Feasibility & User-Friendliness

- Built on **proven, mature technologies** and **open-source libraries**.
- Modular design for rapid prototyping and scaling.
- Clear visuals, interactive steps, and local-language support.
- Works for farmers with varying levels of tech literacy.

---

# Success Metrics

- **User Engagement**: Target 500 active farmers in Year 1, scalable to 10,000+.
- **Economic Impact**: Aim for a 15% increase in farmer income.
- **Sustainability Adoption**: Track eco-friendly practice adoption rate.
- **Customer Satisfaction**: In-app surveys and ratings.
- **Scalability**: Performance benchmarks under growing user base.

---

# Roadmap

1. **Plan** – Crop selection & business planning.
2. **Survey** – Land & soil assessment.
3. **Retail Reach** – Marketplace connections.
4. **Build** – Infrastructure & operational setup.
5. **Fund** – Loans, grants, and subsidies.
6. **Sell** – Pricing and market access.
7. **Maintain** – Continuous improvement and sustainability.

---

# Architecture Diagram

[Insert link or image here]

---

# Installation

```bash
# Clone the repo
git clone https://github.com/yourusername/krishi-mitr-ai.git

# Install dependencies
cd krishi-mitr-ai
pip install -r requirements.txt

# Start backend server
python manage.py runserver
