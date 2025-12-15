# Claude Opus 4.5 Chat - Game Development Assistant

A powerful, cost-effective chat interface for accessing Claude Opus 4.5 through OpenRouter. Optimized for game development, debugging, and iterative coding projects.

![Claude Opus 4.5](https://img.shields.io/badge/Claude-Opus%204.5-764ba2)
![License](https://img.shields.io/badge/license-MIT-green)

## ✨ Features

- 🤖 **Access Claude Opus 4.5** - Anthropic's most advanced reasoning model
- 🧠 **Extended Thinking Mode** - See Claude's reasoning process for better debugging
- 💾 **Automatic Memory** - Conversations saved locally, resume anytime
- 📋 **Project Context** - Give Claude context about your project for better responses
- 🎯 **Temperature Control** - Adjust consistency (0.3 recommended for debugging)
- 💰 **Cost Tracking** - See exactly how much each message costs
- 📥 **Easy File Downloads** - Download code with one click
- 🔒 **100% Private** - Your API key stored only in your browser
- 💵 **Pay-as-you-go** - No subscriptions, only pay for what you use

## 🚀 Quick Start

### Step 1: Get an OpenRouter API Key

1. Go to [OpenRouter.ai](https://openrouter.ai/)
2. Sign up for a free account
3. Add credits to your account (starts at $5)
4. Go to [API Keys](https://openrouter.ai/keys)
5. Click "Create Key"
6. Copy your API key (starts with `sk-or-v1-...`)

### Step 2: Open the App

1. Download `claude-opus-chat.html`
2. Double-click to open in your web browser
3. Paste your OpenRouter API key in the top field
4. Click "🔌 Test Connection" to verify it works
5. Start chatting!

**That's it!** No installation, no setup, no backend required.

## 💰 Pricing

### OpenRouter Costs (Pay-per-use)
- **Claude Opus 4.5:** $5 per million input tokens, $25 per million output tokens
- **Typical message cost:** $0.05 - $0.15 per exchange
- **Monthly usage examples:**
  - 50 messages: ~$4
  - 100 messages: ~$8
  - 500 messages: ~$40

### Compare to Subscriptions
- Lovable/Bolt/Replit: $20-50/month
- **This app:** Pay only for what you use
- **Best for:** Hobbyists, students, occasional development

## 🎯 Best Practices for Game Development

### Initial Setup (One Time)
1. Click "🔌 Test Connection" to verify API key
2. Fill in "Project Context" (left sidebar)
   - Example: *"Building a Pong game with JavaScript. Has collision detection and scoring."*
3. Click "💾 Save Context"
4. Turn ON "Extended Thinking" for debugging
5. Keep Temperature at 0.3 for consistent results

### For Each Session
1. Describe your issue clearly
2. Include error messages if any
3. Mention what version you're on (v1, v2, etc.)
4. Click Send!

### Tips for Better Results
- ✅ Use Extended Thinking for debugging complex issues
- ✅ Keep Temperature at 0.3 for consistency
- ✅ Add project context so Claude understands your game
- ✅ Be specific about errors and what you've tried
- ✅ Ask for complete files, not just code snippets

## 📖 Features Explained

### Project Context (Left Sidebar)
- Describe your game/project once
- Claude remembers it for all future messages
- Saves you from repeating yourself
- Click "Save Context" to persist across sessions

### Extended Thinking
- Shows Claude's internal reasoning
- Highly recommended for debugging
- Uses more tokens but provides better solutions
- Toggle ON/OFF anytime

### Temperature Control
- **0.0 - 0.3:** Focused, consistent (best for debugging)
- **0.4 - 0.7:** Balanced
- **0.8 - 2.0:** Creative, unpredictable (best for brainstorming)

### Automatic Memory
- All conversations saved in your browser
- Close and reopen anytime
- Nothing lost
- Clear chat when you want to start fresh

### Cost Tracking
- See cost per message (green badge)
- Running total in header
- Persists across sessions
- Know exactly what you're spending

## 🔒 Privacy & Security

- ✅ API key stored ONLY in your browser (localStorage)
- ✅ Never sent to any third party
- ✅ No backend server
- ✅ No data collection
- ✅ 100% client-side application
- ✅ Open source - inspect the code yourself

**Your data is yours.** The app runs entirely in your browser.

## 🐛 Troubleshooting

### "Please enter your OpenRouter API key"
- Paste your API key in the top field
- Make sure it starts with `sk-or-v1-`

### "Connection failed: 401"
- API key is invalid or expired
- Get a new key from [OpenRouter](https://openrouter.ai/keys)

### "Connection failed: 402"
- Insufficient credits on your OpenRouter account
- Add credits at [OpenRouter Credits](https://openrouter.ai/credits)

### Chat not remembering context
- Make sure you filled in "Project Context" (left sidebar)
- Click "Save Context" button
- Context is included automatically in all messages

### Costs seem high
- Switch to Claude Sonnet 4.5 (faster, cheaper)
- Reduce max tokens (top settings)
- Turn off Extended Thinking when not debugging
- Use lower temperature

## 🎮 Example Use Cases

### Game Development
- "Create a Pong game HTML file"
- "Fix the collision detection bug where the ball goes through the paddle"
- "Add a score counter to the game"

### Debugging
- "The ball isn't bouncing correctly. Here's the code: [paste code]"
- "Getting error: 'Cannot read property x of undefined' in the collision function"

### Iteration
- "I'm on v6 of my game. The scoring works but I need to add a game over screen"

## 📁 Files

- `claude-opus-chat.html` - Main application (single file, no dependencies)
- `README.md` - This file

## 🤝 Contributing

Feel free to:
- Report bugs by opening an issue
- Suggest features
- Submit pull requests
- Share with other developers

## 📜 License

MIT License - Free to use for any purpose!

## 🙏 Acknowledgments

**Created with [flowpad.ai](https://flowpad.ai)**

Special thanks to:
- [Anthropic](https://www.anthropic.com/) - For creating Claude
- [OpenRouter](https://openrouter.ai/) - For providing unified API access

## 💬 Support

- **Issues with the app:** Open a GitHub issue
- **OpenRouter help:** [OpenRouter Discord](https://discord.gg/openrouter)
- **Claude documentation:** [Anthropic Docs](https://docs.anthropic.com/)

---

**Ready to build your game?** Open `claude-opus-chat.html` and start coding! 🚀
