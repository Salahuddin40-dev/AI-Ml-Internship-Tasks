# Task 4: General Health Query Chatbot

## Objective:
The purpose of this task was to build a simple chatbot using a Large Language Model (LLM) that can answer general health-related questions. The responses were made friendly and clear using prompt engineering, and safety filters were added so that the chatbot doesn't give harmful or emergency medical advice.

---

## Model Used:
- **GPT-3.5 Turbo** (from OpenAI)
- Used through the `openai` Python API
- Prompt was designed to make it behave like a helpful medical assistant

---

## Dataset:
No dataset was used in this project. Since this is a prompt-based chatbot, it doesn’t require training data. However, a list of unsafe keywords (like "suicide", "emergency", etc.) was used to filter unsafe questions.

---

## What I Did:
- Used Python to interact with the OpenAI API
- Created a simple chatbot loop that takes input and returns an LLM-generated response
- Added checks so the chatbot doesn’t respond to risky or emergency-related queries
- Used prompt engineering to improve the clarity and friendliness of the replies

---

## Results:
- The chatbot can answer general health questions like:
  - "What causes a sore throat?"
  - "Is paracetamol safe for children?"
- It does not answer dangerous or critical questions and instead advises the user to consult a real doctor
- The use of a well-written prompt helped make the answers more natural and safe

---

## Note:
This chatbot is only for general health information. It should **not be used for emergency or life-threatening situations**. For any serious health issue, it's always best to talk to a real doctor.

---
