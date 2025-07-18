# Kelsy - Your Personal AI Assistant

Kelsy is an advanced, interactive AI chat application designed to provide a seamless and visually engaging conversational experience. Built with modern web technologies, Kelsy offers a blend of intelligent responses and dynamic aesthetics.

## Features

* **Dynamic Theming:** The application's interface features an animated, evolving color theme that provides a fresh and vibrant look.
* **Intelligent Conversations:** Powered by the Gemini API, Kelsy delivers helpful and witty responses, formatted beautifully with Markdown for enhanced readability.
* **Voice Interaction:** Utilize the speaker icon to have Kelsy read responses aloud. You can select your preferred voice from a curated list of popular options in the settings.
* **Local Chat History:** Your conversations are automatically saved locally in your browser's storage. You can easily switch between different chat sessions, and the application intelligently names them based on your first message.
* **Automatic Chat Pruning:** To keep your browser storage efficient, older, unused conversations are automatically deleted if the total number exceeds a set limit (defaulting to 10).
* **File Uploads:** Attach images, audio, or video files to your messages for richer interactions with the AI.
* **Export Chat:** Export your entire conversation history as a Markdown file for easy sharing or archiving.
* **Clean UI:** A minimalist design with hidden scrollbars ensures an uncluttered and immersive chat experience.

## Setup and Usage

To run Kelsy locally or deploy it:

1.  **Obtain a Gemini API Key:**
    * Go to the [Google Cloud Console](https://console.cloud.google.com/).
    * Create a new project (e.g., "Kelsy AI").
    * Navigate to "APIs & Services" > "Library".
    * Search for and **enable** the "Generative Language API".
    * Go to "APIs & Services" > "Credentials".
    * Click "Create credentials" and select "API key".
    * **Copy the generated API key.**
    * **(Highly Recommended for Security):** Edit the newly created API key. Under "Application restrictions," select "HTTP referrers (web sites)" and add your website's domain (e.g., `*.yourdomain.com/*`). Under "API restrictions," select "Restrict key" and choose "Generative Language API" from the dropdown. Save your changes.

2.  **Insert API Key:**
    * Open the `index.html` file.
    * Locate the line `const GEMINI_API_KEY = "YOUR_API_KEY_HERE";`
    * Replace `"YOUR_API_KEY_HERE"` with the API key you obtained from the Google Cloud Console.

3.  **Run the Application:**
    * You can open the `index.html` file directly in your web browser, or deploy it to a web server (like Netlify, Vercel, GitHub Pages, etc.).

## Credits

Kelsy was created by ApexUrke.
Portfolio: [https://urke.netlify.app/](https://urke.netlify.app/)
