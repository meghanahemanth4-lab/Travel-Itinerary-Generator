# ✈️ AI Travel Planner

An AI-powered travel planning assistant that generates personalized, day-wise travel itineraries based on user preferences, budget, and destination.

## 🌍 Overview

AI Travel Planner is a smart assistant that helps users create customized travel itineraries using natural language input. It generates day-wise plans, suggests hotels and activities, and supports question-and-answer interactions about the itinerary.

The project combines large language models with real-time travel data to make trip planning more convenient and interactive.

## ✨ Features

- **Personalized Itineraries:** Generate travel plans based on destination, travel dates, interests, and budget.
- **AI-Powered Planning:** Use the Groq LLaMA 3 model through an API to generate customized itineraries.
- **Hotel Suggestions:** Fetch hotel and travel information using SerpAPI.
- **Travel Q&A:** Ask travel-related questions about the generated plan.
- **Interactive UI:** Explore the application through a Streamlit interface.
- **Day-Wise Planning:** Organize travel activities into a structured itinerary.

## 🛠️ Technology Stack

| Technology | Purpose |
|---|---|
| Python | Application logic |
| Streamlit | Frontend and interactive UI |
| Groq LLaMA 3 | AI-powered itinerary generation |
| SerpAPI | Hotel and travel data retrieval |

## ⚙️ How to Run

### 1. Clone the repository

```bash
git clone https://github.com/meghanahemanth4-lab/Travel-Itinerary-Generator.git
cd Travel-Itinerary-Generator
```

### 2. Create a virtual environment

```bash
python -m venv venv
```

Activate it on Windows PowerShell:

```powershell
.\venv\Scripts\Activate.ps1
```

### 3. Install dependencies

```bash
pip install -r requirements.txt
```

### 4. Configure API keys

The application requires API credentials for Groq and SerpAPI. Set them using the environment variable names expected by your code. Keep credentials private and never commit them to GitHub.

### 5. Run the application

```bash
streamlit run app.py
```

If your main Python file has a different name, replace `app.py` with the correct filename.

## 🔐 Security

- Store API keys in environment variables or a local `.env` file.
- Add `.env` to `.gitignore`.
- Never publish API keys, passwords, or other sensitive credentials.

## 🚀 Future Enhancements

- Travel expense estimation and budget breakdowns
- Interactive maps and route planning
- More detailed activity recommendations
- Itinerary export and sharing
- Additional personalization options

## 👩‍💻 Author

**Meghana Hemanth**

[GitHub Profile](https://github.com/meghanahemanth4-lab)

## ⚠️ Disclaimer

Hotel availability, prices, and travel information may change. Verify important details with the relevant providers before booking.
