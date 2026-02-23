# 🐾 PawSense — AI Dog Emotion Detector

PawSense uses Claude AI to analyse photos of your dog and detect their emotional state. Upload a photo and instantly get a detailed emotion report including detected signals, a friendly message, and a recommended action.

## ✨ Features

- 📷 Upload any photo of your dog
- 🧠 AI analyses posture, ears, tail, and facial expressions
- 💬 Get a friendly, detailed emotion report
- ⚠️ Alerts when your dog may need attention
- 🌐 Runs entirely in the browser — no server needed

## 🚀 How to Use

1. Open `index.html` in any browser
2. Enter your [Anthropic API key](https://console.anthropic.com) (free to get started)
3. Upload a photo of your dog
4. Click **Analyse Emotion**

## 🛠️ How to Publish on GitHub Pages

1. Create a new repository on [github.com](https://github.com)
2. Upload `index.html` to the repository
3. Go to **Settings → Pages**
4. Under **Source**, select **main branch**
5. Click **Save** — your app will be live at `https://yourusername.github.io/your-repo-name`

## 🔑 API Key

You'll need a free Anthropic API key:
1. Go to [console.anthropic.com](https://console.anthropic.com)
2. Click **API Keys → Create Key**
3. Copy the key (starts with `sk-ant-...`)
4. Paste it into the app when prompted

Your key is stored only in your browser and is never shared.

## 🐕 Emotions Detected

| Emotion | Description |
|---------|-------------|
| 😄 Happy | Relaxed, tail wagging, open mouth |
| 😌 Calm | Settled, slow movements, soft eyes |
| 😰 Anxious | Tense posture, ears back, tail low |
| 😢 Lonely | Low energy, minimal movement |
| 🎉 Playful | Play bow, bouncy, excited |
| 👀 Alert | Ears forward, focused gaze |
| 😴 Tired | Lying down, slow blinking |

## 🤖 Built With

- [Claude AI by Anthropic](https://anthropic.com) — emotion analysis
- Vanilla HTML, CSS, JavaScript — no frameworks needed

## 📄 License

MIT — free to use and modify!
