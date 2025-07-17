# Kelsy Chatbot

Kelsy is a sleek, modern AI chatbot designed to provide helpful and concise responses. Built with a focus on user experience and responsiveness, Kelsy leverages the Gemini API to offer a conversational interface that adapts seamlessly across various devices.

## Features

* **AI-Powered Responses:** Utilizes the Gemini API for intelligent and context-aware conversations.
* **Real-time Typing Effect:** Bot responses are displayed with a dynamic typing animation for a more engaging interaction.
* **Code Highlighting:** Automatically highlights code snippets in bot responses for improved readability.
* **Copy to Clipboard:** Easily copy bot responses, especially code blocks, with a dedicated copy button.
* **Responsive Design:** Optimized for a consistent and pleasant user experience on desktops, laptops, tablets, and mobile phones.
* **Interactive Background:** Features a subtle, animated 3D background powered by Three.js.
* **Stop Generation:** Ability to halt ongoing AI response generation.

## Setup and Usage

To run Kelsy locally, follow these simple steps:

1.  **Clone the repository (or download the `index.html` file):**
    If you've pushed your project to GitHub, you can clone it:
    ```bash
    git clone [https://github.com/ApexUrke/Kelsy.git](https://github.com/ApexUrke/Kelsy.git)
    cd Kelsy
    ```
    Alternatively, if you only have the `index.html` file, ensure it's in a dedicated folder.

2.  **Open `index.html`:**
    Simply open the `index.html` file in your preferred web browser. You can do this by double-clicking the file, or by right-clicking and selecting "Open with" and choosing your browser.

    The chatbot interface will load, and you can start interacting with Kelsy immediately.

### Gemini API Key

This project uses the Gemini API. Your personal API key is embedded directly in the `index.html` file for convenience. If you ever need to update or replace it, locate the `GEMINI_API_KEY` constant in the JavaScript section of `index.html`.

**Note:** While convenient for local development and personal use, for public deployments or collaborative projects, it's generally recommended to use more secure methods for handling API keys (e.g., server-side proxies or environment variables).

## Technologies Used

* **HTML5:** Structure of the web page.
* **CSS3:** Styling and responsive design.
* **JavaScript (ES6+):** Core logic, API integration, and DOM manipulation.
* **Google Gemini API:** For AI conversational capabilities.
* **Three.js:** For the interactive 3D background animation.
* **Marked.js:** For parsing Markdown content in bot responses.
* **Highlight.js:** For syntax highlighting of code blocks.
* **Font Awesome:** For icons.
* **Google Fonts (Poppins):** For typography.

## Credits

* **Urke (ApexUrke):** Original developer and creator of Kelsy.
* **Google Gemini API:** Powering the AI intelligence.
* **Three.js, Marked.js, Highlight.js, Font Awesome:** Open-source libraries that enhance the project.

## License

This project is open-source and available under the [MIT License](LICENSE).
