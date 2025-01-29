# 🧠 shawns-nice-llmao 

> Because running AIs locally is funny business! 🏠

## 🎭 What the heck is this?!

`"Yo check it - is you tired of dem cloud AIs acting well expensive n' dat? We's running local LLMs innit, keepin' it real in your yard! Local Llama is proper peng, respect! BOOYAKASHA! snap 🧠✌️"` --Ali G.

## 🚀 Why?

- 🏃‍♂️ Runs faster than my coffee-induced coding sprints
- 🏠 Keeps all the hallucinations where they belong - in my house
- 🧊 Cooler than the other side of the pillow
- 🎮 Web UI that doesn't look like it's from 1995
- 🐳 Docker-ized because we're fancy like that

## 🛠 Prerequisites (The stuff you need)

- A beast of a machine 💪
- Docker (and Colima, because we're too cool for Docker Desktop)
- Docker Compose (install or upgrade using Homebrew)
- Configure Docker Compose as a CLI plugin:
  ```json
  {
    "cliPluginsExtraDirs": [
      "/opt/homebrew/lib/docker/cli-plugins"
    ]
  }
  ```
- Coffee (optional but highly recommended)

## 🏃‍♂️ Getting this party started

```bash
# Fire up Colima with MAXIMUM POWER! 
colima start --cpu 8 --memory 24 --disk 50

# Clone this bad boy
git clone https://github.com/s-h-a-w-n/shawns-nice-llmao.git
cd shawns-nice-llmao

# Launch the mothership
docker-compose up -d  # For older versions of Docker
# or
docker compose up -d  # For newer versions of Docker

# Celebrate with a victory dance 🕺
```

## 🎮 How to use this magnificent beast

1. Point your favorite browser to http://localhost:3000
2. Download some models (I recommend starting with Mistral because it's 🔥)
3. Chat with your new local AI friend
4. Question your life choices

## 🚨 Troubleshooting (When stuff hits the fan)

- **AI acting weird?** - That's normal, they're supposed to do that
- **Everything's on fire?** - Try turning it off and on again
- **Still on fire?** - Maybe actual fire? Stop, drop, and roll!
- **Getting existential AI responses?** - Time for a coffee break

## 🤝 Contributing

Found a way to make this even more ridiculous? Pull requests welcome! Just keep it:

- 🧊 Clean
- 🎭 Fun
- 🚀 Fast
- 🦄 Magical

## 📜 License

MIT License (Because sharing is caring! ❤️)

## 🙏 Acknowledgments

- The rubber duck on my desk for emotional support
- open source, FTW
- You, for reading this far! You're awesome! 🌟

---
