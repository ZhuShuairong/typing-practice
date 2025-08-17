# AI-Powered Typing Practice

This is a web app for practicing typing with AI-generated text prompts. You can enter a topic, and the app will generate a passage for you to type, using Together AI's text generation models.

## Features
- Enter any topic to generate a typing passage
- Animated loading indicator and elapsed time while generating
- Works with any Together AI text-to-text model (including free ones)
- Upload your own text files for practice

## Getting Started
1. Clone this repository:
   ```sh
   git clone https://github.com/ZhuShuairong/typing-practice.git
   ```
2. Open `index.html` in your browser.
3. **Important:**
   - In the code, find the line:
     ```js
     'Authorization': 'Bearer enter your api key here',
     ```
   - Replace `enter your api key here` with your Together AI API key. You can get a free API key at [Together AI](https://www.together.ai/).
   - You may use any Together AI text-to-text model. The default is a free model, but you can change it in the code if you wish.

## Example API Key Usage
```js
'Authorization': 'Bearer YOUR_TOGETHER_AI_API_KEY',
```

## License
MIT
