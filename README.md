# 🧭 AI Travel Planner using CrewAI, Gemini & Serper APIs

This project is an *AI-powered Travel Assistant* built using [CrewAI](https://docs.crewai.com/) that uses multi-agent collaboration to plan travel experiences based on user preferences. The assistant leverages the *Gemini API* (for natural language reasoning) and the *Serper API* (for real-time search data).

It features *three autonomous agents* working together to create smart, tailored travel plans.

---

## ✨ Core Features

### 🤖 Multi-Agent Architecture
- *Travel_Agent*: Researches and suggests travel destinations, points of interest, and activities.
- *Budget_Planner*: Provides an estimated budget for the trip, considering location, duration, and preferences.
- *Itinerary_Planner*: Generates a daily travel itinerary based on the destination and budget.

### 🔗 API Integration
- *Gemini API* (by Google): Used for advanced reasoning and natural language generation.
- *Serper API*: Fetches real-time travel-related data via search queries (e.g., hotel costs, places to visit).

---

## 🛠 Tech Stack

| Layer         | Tools Used                             |
|---------------|----------------------------------------|
| AI Agents     | [CrewAI](https://docs.crewai.com/)     |
| Language Model| Google Gemini API                      |
| Search Engine | Serper API                             |
| Language      | Python                                 |

---

## 🧠 How It Works

1. User defines basic trip parameters (destination, budget, duration).
2. The *CrewAI orchestrator* initiates a crew of agents with specific goals.
3. Agents communicate, collaborate, and reason to:
   - Suggest top destinations and things to do.
   - Estimate total budget and categorize costs.
   - Build a practical day-by-day itinerary.
4. The output is returned as a *text-based travel plan*.

---

