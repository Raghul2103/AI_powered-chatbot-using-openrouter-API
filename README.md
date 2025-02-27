# AI_powered-chatbot-using-openrouter-API
# Raghul's ChatBot

## Overview
Raghul's ChatBot is a simple, interactive chatbot built using HTML, CSS, JavaScript, and Bootstrap. It features a modern UI with a blue gradient background and a glassmorphic chat container. The bot sends user inputs to an AI API for generating responses.

## Features
- **Responsive Design**: Works across different screen sizes.
- **Beautiful UI**: Styled with Bootstrap and custom CSS.
- **Interactive Responses**: Uses OpenRouter AI for chatbot responses.
- **Real-Time Response Display**: Shows bot replies in a stylish format.

## Technologies Used
- HTML5
- CSS3 (with Bootstrap 5.3 for styling)
- JavaScript (for handling user input and API requests)
- OpenRouter AI API (for chatbot responses)

## Installation
### Prerequisites
- A web browser (Chrome, Firefox, Edge, etc.)
- Internet connection

### Steps to Run
1. Download or clone the repository.
2. Open the `index.html` file in your preferred web browser.
3. Type a message and click the "Ask!" button to interact with the chatbot.

## Configuration
To integrate with OpenRouter AI API, add your API key inside the `Authorization` header in `sendMessage()` function inside the `<script>` tag.
```javascript
headers: {
    Authorization: 'YOUR_API_KEY_HERE',
    'X-Title': 'SiteName',
    'Content-Type': 'application/json',
}
```

## Customization
- **Changing the Background**: Modify the `body` CSS styles in the `<style>` section.
- **Modifying Button Colors**: Edit the `.btn-ask` styles for different gradient colors.
- **Adjusting Chat Response UI**: Change the `#response` CSS to update text color, font size, or background.

## Troubleshooting
- If the chatbot does not respond:
  - Ensure you have an active internet connection.
  - Check the API key configuration.
  - Open the browser console (`F12` or `Ctrl + Shift + I`) and inspect any errors.

## License
This project is open-source and free to use. Feel free to modify and improve it!

