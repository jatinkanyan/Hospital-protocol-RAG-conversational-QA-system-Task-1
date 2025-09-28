# Task 1: Chatbot with Memory

## Overview

This project implements an intelligent chatbot designed to answer patient queries in a healthcare setting while retaining conversation context throughout the interaction. Using Google’s Gemini Pro latest model accessed via LangChain, the chatbot maintains memory of previous exchanges to provide coherent multi-turn dialogue, improving user experience and support quality.

---

## Features

- **Conversational Memory:** Uses LangChain's `ConversationBufferMemory` to maintain dialog history.
- **Gemini Pro Integration:** Leverages Google AI Studio's Gemini API for advanced natural language understanding and generation.
- **Patient-Centric Queries:** Supports typical medical-related questions such as upcoming appointments and lab result checks.
- **Easy Deployment:** Hosted via Gradio or Streamlit interfaces for quick testing and demonstration.
- **Synthetic Prompt Testing:** Enables initial testing with simulated financial planning or healthcare prompts ensuring readiness for real data.

---

## Architecture and Flow

1. **LLM Configuration:** Configured LangChain to use Gemini Pro latest as the language model.
2. **Memory Integration:** Added conversational memory for tracking prior messages throughout the chat session.
3. **Conversational Chain:** Built a LangChain `ConversationChain` tying the LLM and memory together.
4. **Web Interface:** Developed a Gradio or Streamlit app to provide a user-friendly front-end to interact with the chatbot.
5. **Testing:** Validated chatbot using synthetic prompt examples resembling patient inquiries.

---

## Folder and File Breakdown

- `chatbot_with_memory.ipynb`: Jupyter notebook demonstrating step-by-step chatbot implementation and usage.
- `requirements.txt`: Specifies Python dependencies used in the project.
- `sample_conversations.json`: Contains example dialogs simulating patient-bot interactions.
- `README.md`: This documentation file.
- `explanation_video.mp4`: Walkthrough video explaining the project goals, design decisions, and demo.

---

## How to Use

1. **Setup:**
   - Ensure Python and necessary packages (`langchain`, `langchain-google-genai`, `gradio` or `streamlit`) are installed.
   - Set your Gemini API key as environment variable `GOOGLE_API_KEY`.

2. **Run Notebook:**
   - Execute `chatbot_with_memory.ipynb` to launch the chatbot interface locally.
   - Interact with the chatbot via the integrated web UI.

3. **Test:**
   - Use entries in `sample_conversations.json` to simulate realistic patient queries or customize your own.

---

## Future Improvements

- Expand chatbot’s knowledge base with real patient medical records (with privacy protections).
- Integrate authentication for secure patient-specific responses.
- Add voice interface for hands-free interactions.
- Improve memory with long-term persistence across sessions.

---

## Contact and Contribution

Feel free to raise issues for bugs or feature requests or create pull requests for enhancements. Contact the maintainer at [Jatinkanyan11@gmail.com/9306980229].

---

## License
No License Required.

---

Thank you for exploring Task 1! Happy Chatbot Building.
