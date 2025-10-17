# Meal Analysis AI

**Meal Analysis AI** is a smart image-based nutrition analyzer that lets users upload a meal photo and instantly get its **macronutrient breakdown** (calories, protein, carbs, fats).

## 🧩 Tech Stack
- **n8n** – Workflow automation (webhook + OpenAI code node)
- **OpenAI API** – Processes the meal image and returns nutrition data
- **Lovable.dev** – Frontend landing page

## 💡 Workflow
1. User uploads or captures a meal photo.
2. Image is sent to an **n8n webhook**.
3. A **Code Node (OpenAI)** analyzes it and returns nutrition info as JSON.
4. Lovable frontend displays the breakdown.

## 📦 Usage
1. Clone the repository
   ```bash
   git clone https://github.com/Niharika1614/Meal-Analysis-AI.git
