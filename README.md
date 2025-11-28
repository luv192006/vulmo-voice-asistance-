# vulmo-voice-asistance-
Vulmo: Your Voice AI Assistant Vulmo is an immersive voice assistant I built for the Murf Voice Agent Hackathon. It provides hands-free, seamless conversations by using browser speech recognition to capture your voice input, and a powerful custom AI engine togenerate intelligent  brief responses.completes the loop with Text-to-Speech functionality,
🎤 Vulmo: Your Next-Gen Voice AI Assistant

Vulmo is a cutting-edge voice assistant application built for the Murf Voice Agent Hackathon. It offers a hands-free, intuitive conversational experience directly in your browser.

 ✨ Key Features

  * **Seamless Voice Interaction:** Utilizes **browser-native Speech Recognition** (`webkitSpeechRecognition`) to accurately capture and transcribe your voice input in real-time.
  * **Custom AI Intelligence:** Employs a powerful **custom AI engine** (backed by the Claude Sonnet 4 model) to process voice commands and generate intelligent, concise, and helpful text responses.
  * **Text-to-Speech Output:** Implements **Text-to-Speech (TTS)** functionality using `SpeechSynthesisUtterance` to speak the AI's response back to the user, creating a full voice-in, voice-out experience.
  * **Real-time Status:** Provides clear visual feedback (Listening, Processing, Speaking) and error handling, ensuring a smooth user experience.
  * **Modern Interface:** Features a sleek, responsive, and visually appealing gradient-themed interface built with **React** and **Tailwind CSS**.

-----

### 🛠️ Technology Stack

  * **Frontend:** HTML5, CSS (Tailwind CSS), React (via Babel/CDN).
  * **Core Logic:** Vanilla JavaScript, utilizing Web Speech API (`SpeechRecognition` / `webkitSpeechRecognition`) and Web Speech API (`SpeechSynthesis`).
  * **AI Backend:** External API calls to the **Anthropic API** (specifically, the `claude-sonnet-4-20250514` model) for conversational intelligence.

-----

### 🚀 Getting Started

To run this project locally, you only need a modern web browser that supports the Web Speech API (like Chrome).

1.  **Clone the repository:**
    ```bash
    git clone [Your-Repo-Link]
    ```
2.  **Open the file:**
    Open the `vulmo.html` file directly in your web browser.
3.  **API Key (Required):**
    The current implementation requires an API key to communicate with the Anthropic service. **Note:** For a live deployment, you would need to proxy the API call through a secure backend server instead of directly exposing the API key in the frontend code.

-----

 🖼️ Preview

-----

### 🔗 Built For

  * **Murf Voice Agent Hackathon**
  * **Techfest IIT Bombay**

-----

### 📝 License

This project is licensed under the MIT License - see the LICENSE.md file for details.

Would you like me to add a section for **Future Enhancements** or a **Contributing** section?
