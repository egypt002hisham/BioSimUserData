# BioSimUserData

**Store and manage simulation data offline, with quick export to JSON files**

[![Vercel Deployment](https://img.shields.io/badge/Vercel-Deployed-brightgreen)](https://my-biopulse2025version.vercel.app/)
![Last Commit](https://img.shields.io/github/last-commit/egytp002hisham/BioSimUserData)
![Repo Size](https://img.shields.io/github/repo-size/egytp002hisham/BioSimUserData)

---

## 🌐 Live Demo

🔗 [**https://my-biopulse2025version.vercel.app/**](https://my-biopulse2025version.vercel.app/)

---

## 📖 About

**BioSimUserData** is a full-featured biological data management system designed to support **BioPulse** - a strategic biological simulation game that puts players in control of the human immune system.

### 🎮 What is BioPulse?

BioPulse is an educational strategy game that allows players to:
- **Control the immune system** (phagocytes, natural killer cells, T cells, B cells)
- **Manage ATP energy resources** and tissue health
- **Discover a DNA library** with real biological information
- **Fight viruses and bacteria** through realistic chemical interactions

---

## ✨ Features

- 🔬 **Add chemical compounds** with custom effects (InhibitReproduction, SlowMovement, DamageOverTime, etc.)
- 🦠 **Add pathogens** with unique behaviors (Aggressive, Cooperative, Defensive)
- 📊 **Real-time Firebase database** synchronization
- 🌳 **D3.js evolution tree** visualization for pathogens
- 📈 **Pathogen danger comparison charts**
- 🔍 **Automatic PubChem verification** for chemical compounds
- 📱 **Fully responsive design** (works on mobile & desktop)
- 🌐 **Bilingual** (Arabic & English support)

---

## 🗂️ Project Structure

```
BioSimUserData/
├── index.html                 # Main landing page
├── biopulse-data-hub.html     # Data management hub (compounds & pathogens)
├── game-mechanics.html        # Detailed mechanics & code explanations
├── blog.html                  # Scientific educational articles
├── about.html                 # Team & project info
├── download.html              # Game download page
├── privacy-policy.html        # Privacy policy
├── img/                       # Images & video assets
├── robots.txt                 # SEO directives
├── sitemap.xml                # Site structure for search engines
├── vercel.json                # Vercel deployment config
└── README.md                  # This file
```

---

## 🛠️ Technologies Used

| Technology | Purpose |
|------------|---------|
| **HTML5/CSS3** | Structure & styling |
| **JavaScript (ES6)** | Dynamic functionality |
| **Firebase Realtime DB** | Data storage & sync |
| **D3.js** | Evolution tree visualization |
| **Chart.js** | Danger comparison charts |
| **Vercel** | Hosting & deployment |

---

## 🚀 Getting Started

### Prerequisites
- A modern web browser (Chrome, Firefox, Edge)
- (Optional) Firebase account for full functionality

### Run Locally
```bash
git clone https://github.com/egytp002hisham/BioSimUserData.git
cd BioSimUserData
# Simply open index.html in your browser
# Or use a local server:
python -m http.server 8000
```

### Firebase Setup (for full features)
1. Create a Firebase project
2. Enable Realtime Database
3. Replace the `firebaseConfig` in `biopulse-data-hub.html` with your own credentials

---

## 📊 Data Management

The system allows you to:
- **Add chemical compounds** with custom effect types, magnitude, duration, production cost, and carrier
- **Add pathogens** with health, movement speed, reproduction, stealth, and chemical compound production
- **Delete or clear all data** (password protected)
- **Export data to JSON** for offline storage

### Chemical Compound Effects
| Effect Type | Description |
|-------------|-------------|
| `InhibitReproduction` | Stops or reduces reproduction rate |
| `SlowMovement` | Reduces movement speed |
| `DamageOverTime` | Causes continuous damage |
| `ReduceDefense` | Weakens defenses |
| `BoostDefense` | Enhances immunity |
| `BindAntigen` | Tags enemies for immune cells |
| `SignalChemotaxis` | Attracts or repels cells |

---

## 🔬 Scientific Verification

The system automatically verifies chemical compounds against **PubChem**, the world's largest scientific database of chemical compounds:
- ✅ **Verified compounds** – Real, scientifically recognized chemicals with formulas and descriptions
- ⚠️ **Unverified compounds** – May be invented for game purposes only

---

## 📈 Development Status

| Stage | Status | Progress |
|-------|--------|----------|
| Basic immune cell system | ✅ Completed | 100% |
| Chemical particle system | 🚧 In Progress | 75% |
| Advanced chemical interactions | 🚧 In Progress | 60% |
| DNA library | 🚧 In Progress | 50% |
| Full human body simulation | 📅 Planned | 25% |
| Mobile version | 📅 Planned | 0% |

---

## 👥 Contributing

Want to contribute to BioPulse?
1. Visit the [Data Hub](https://my-biopulse2025version.vercel.app/biopulse-data-hub.html)
2. Add new pathogens or chemical compounds
3. Your contributions will help expand the game world!

---

## 📞 Contact & Social

- **Instagram (Personal):** [@mhis_100_th](https://www.instagram.com/mhis_100_th/)
- **Instagram (Studio):** [@niledevhub](https://www.instagram.com/niledevhub/)
- **Email:** aletheiadao85@gmail.com

---

## 📄 License

This project is protected by intellectual property rights. All content, designs, and code are the property of Genome Games / BioPulse.

© 2025 BioPulse. All rights reserved.

---

## ⭐ Show Your Support

If you find this project interesting, please give it a ⭐ on GitHub!

[![GitHub stars](https://img.shields.io/github/stars/egytp002hisham/BioSimUserData?style=social)](https://github.com/egytp002hisham/BioSimUserData)
[![GitHub forks](https://img.shields.io/github/forks/egytp002hisham/BioSimUserData?style=social)](https://github.com/egytp002hisham/BioSimUserData)

---

**Built with 💚 for biology and education**