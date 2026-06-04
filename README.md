# 🧳 AI Travel Planner — MVP (prototype)

> **Status**: 🚧 *Under active development* - this is a **minimum viable product (MVP)** demonstrating AI‑powered itinerary generation.

## 📝 Overview
A web application that generates daily travel plans based on **budget**, **destination** and **duration**. The backend uses **Flask** and calls **Groq API** (Llama 3) to produce realistic activities and costs. The UI is built with **Bootstrap 5** and allows manual day‑by‑day editing.

## ✨ Current features (prototype)
- ✅ AI‑generated itineraries (JSON → styled cards)
- ✅ Manual editing of any day (activity / cost)
- ✅ Responsive design with icons (Bootstrap Icons)
- ✅ Fallback logic when API fails
- ✅ No page reload – fetch API

## 🛠️ Tech stack
| Area        | Tools |
|-------------|-------|
| Backend     | Flask (Python), Groq API (Llama 3) |
| Frontend    | HTML5, Bootstrap 5, JavaScript (Fetch) |
| Icons       | Bootstrap Icons |
| Env. vars   | python-dotenv |

## 📁 Project structure
ai-travel-planner/
├── app.py
├── templates/
│ └── index.html
├── requirements.txt
├── .env (not committed)
└── README.md


## 🚀 Running locally (for testing)
1. Clone the repo  
   `git clone https://github.com/YOUR_USERNAME/ai-travel-planner.git`
2. Install dependencies  
   `pip install -r requirements.txt`
3. Add your **Groq API key** in a `.env` file:  
   `GROQ_API_KEY=your_key_here`
4. Run the app  
   `python app.py`
5. Open `http://127.0.0.1:8000`

## 📜 License
This project is licensed under the **MIT License** – you are free to use, modify, and distribute it with attribution.

## 👨‍💻 Author
**Hayhat Tahir** – [GitHub Profile](https://github.com/HayhatDev)

## 🔮 Future plans (beyond MVP)
- Add map visualization (Leaflet / Google Maps)
- Save & share itineraries via unique links
- More intelligent fallback logic
- User authentication (optional)
- Travllers secrets and advice section
