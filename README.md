# EvolvingHTMLWithAI

**EvolvingHTMLWithAI** is a fun and dynamic project where an HTML file evolves over time, updated regularly by a Python script using the ChatGPT API. Each update adds creative and quirky content, making the page an ever-changing experience for visitors. The evolving HTML file is hosted live on Firebase, allowing everyone to witness the weirdness unfold in real time!

## How It Works

1. **Python Script**: A Python script generates content daily using the ChatGPT API.
2. **HTML Evolution**: The script updates an HTML file by appending new, creative, and often bizarre content.
3. **Automation**: A cron job runs the script regularly to keep the content fresh.
4. **Live Hosting**: The updated HTML file is deployed to Firebase Hosting for everyone to enjoy.

## Features

- **Dynamic Content**: From surreal stories to quirky CSS animations, the page evolves in unexpected ways.
- **AI-Powered Creativity**: Leveraging ChatGPT to generate unique and entertaining updates.
- **Live Access**: Visit the hosted page on Firebase to scroll through the evolving chaos.
- **Open Source Fun**: Clone the repo and contribute your own ideas for even more weirdness!

## Inspiration

This project is inspired by the idea of combining automation, AI, and creativity to make something truly unique. It's a playful take on evolving web content and a showcase of the possibilities of AI-powered automation.

## How to Run Locally

### Note, this doesn't work yet

1. Clone the repository:
```bash
git clone https://github.com/edvinpontuslarsson/EvolvingHTMLWithAI.git
cd EvolvingHTMLWithAI
```

2. Install dependencies:
```bash
pip install -r requirements.txt
```

3. Add your OpenAI API key to the environment:
```bash
export OPENAI_API_KEY=your-api-key
```

4. Run the Python script to update the HTML file:
```bash
python update_html.py
```

5. Serve the HTML file locally (e.g., using Python's built-in HTTP server):
```bash
python -m http.server
```

6. Visit this url in your browser to view the page.
```txt
http://localhost:8000
```

## Deployment
The project is hosted live using Firebase Hosting. You can deploy your version by running:
```bash
firebase deploy
```

## Contributing
Feel free to fork this repository, experiment with new ideas, and submit a pull request! Let’s make this page even weirder together.

<hr>

Have fun exploring the ever-changing world of EvolvingHTMLWithAI!
