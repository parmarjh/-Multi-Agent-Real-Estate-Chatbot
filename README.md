# 🏠 Multi-Agent Real Estate Chatbot

A modern, intelligent chatbot that solves **property issues** and answers **tenancy law questions** using **image + text input**. Powered by multiple agents that specialize in different domains.

---

## 🚀 Live Demo
**Try it here** → [https://your-vercel-link.vercel.app](https://your-vercel-link.vercel.app)

---

## 🤖 Multi-Agent Architecture
| Agent                            | Specialty       | Input Type            | Description                                                                              |
| -------------------------------- | --------------- | --------------------- | ---------------------------------------------------------------------------------------- |
| 🛠️ Property Inspector (Agent 1) | Issue Detection | Text + Image          | Detects cracks, mold, leaks, damage, lighting problems, and gives actionable solutions.  |
| 📋 Tenancy Expert (Agent 2)      | Rental Law FAQ  | Text only             | Explains rental laws, agreements, deposit issues, eviction rules, and more.              |
| 🔀 Router                        | Dispatcher      | Text/Image Classifier | Automatically routes user queries to the right agent based on content and file presence. |

---

## 💻 Tech Stack
- ⚛️ **React + Vite** – Frontend UI & routing
- 🎨 **Tailwind CSS** – Modern responsive styling
- 🧠 **Claude Sonnet 4 API** – Text + image-based understanding
- 📸 **Base64 Image Uploads** – Efficient image handling
- 🖼️ **Lucide Icons** – Clean and minimal icons

---

## ✨ Features
- Upload property images (e.g., cracked wall, mold)
- Ask legal rental questions (e.g., "Can my landlord increase rent?")
- Smart router decides best agent
- Agent replies are clear, structured, and helpful
- Mobile-friendly responsive UI

---

## 📦 Project Structure
```
real-estate-chatbot/
├── public/
├── src/
│   ├── components/
│   │   └── RealEstateChatbot.jsx
│   ├── App.jsx
│   └── main.jsx
├── .env
├── index.html
├── package.json
└── tailwind.config.js
```

---

## 🔐 Setup Locally
```bash
# 1. Clone the repo
git clone https://github.com/yourusername/real-estate-chatbot.git
cd real-estate-chatbot

# 2. Install dependencies
npm install

# 3. Add API key to .env
VITE_ANTHROPIC_API_KEY=your-api-key-here

# 4. Start the dev server
npm run dev
```

---

## 🧪 Try These Prompts
- **Image + Text:** "What's wrong with this wall?" *(Upload image of mold)*
- **Text Only:** "Can my landlord evict me without notice?"
- **Text + Issue:** "There's water damage near the ceiling. What should I do?"

---

## 📃 Submission Details
**Title:** Multi-Agent Real Estate Assistant Chatbot (Text + Image)

**Submitted To:**
- saksham@data-hat.com
- hiring@data-hat.com

**Author:** Jatinkumar Parmar  
[jhparmar LinkedIn](https://linkedin.com/in/jhparmar)

---

## 📸 Screenshots
| Welcome Interface | Image Upload + Chat | Agent Response |
| ----------------- | ------------------- | -------------- |
|                   |                     |                |

---

## 📚 License
MIT

---
> "AI + Design meets Practical Real Estate Support. Build once, deploy anywhere."
