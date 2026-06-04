# 🌿 FocusGrow — Productivity Website

> Stay focused. Grow daily. One session at a time.

FocusGrow is a beautiful productivity web app that helps you stay on task with a real-time clock, a virtual growing tree that rewards your focus sessions, calming plant companions, and daily streaks to keep you motivated every day.

---

## ✨ Features

### 🕐 Live Clock
- Displays the current time in real-time (HH:MM:SS)
- Shows the current date and day of the week
- Clean, minimal design that stays visible without being distracting

### 🌳 Virtual Focus Tree
- A tree grows on your screen as you complete focus sessions
- The longer and more consistently you focus, the bigger and fuller your tree becomes
- Abandon a session early and your tree withers — stay committed to keep it thriving!
- Visual growth stages: Seed → Sprout → Sapling → Young Tree → Full Tree → Ancient Tree

### 🪴 Virtual Plants
- Earn decorative plants by hitting daily focus goals
- Each plant species is unlocked through different achievements (e.g., 5 sessions in a day, 7-day streak)
- Build your own cozy plant collection over time
- Plants are displayed in a personal garden view

### 🔥 Daily Streaks
- Track how many consecutive days you've completed at least one focus session
- Streak counter resets if you miss a day — don't break the chain!
- Milestone rewards at 3, 7, 14, 30, and 100-day streaks
- Streak history calendar to visualize your consistency

### ⏱️ Focus Timer (Pomodoro-style)
- Customizable focus session durations (default: 25 min focus / 5 min break)
- Long break mode after every 4 sessions
- Session log to review your daily productivity history

---

## 🚀 Getting Started

### Prerequisites

- Node.js v18 or higher
- npm or yarn

### Installation

```bash
# Clone the repository
git clone https://github.com/your-username/focusgrow.git

# Navigate into the project folder
cd focusgrow

# Install dependencies
npm install

# Start the development server
npm run dev
```

Open your browser and visit `http://localhost:3000`

### Build for Production

```bash
npm run build
npm run start
```

---

## 🗂️ Project Structure

```
focusgrow/
├── public/
│   ├── assets/
│   │   ├── trees/          # Tree growth stage illustrations
│   │   └── plants/         # Unlockable plant images
├── src/
│   ├── components/
│   │   ├── Clock.jsx        # Live clock component
│   │   ├── FocusTree.jsx    # Virtual tree with growth logic
│   │   ├── PlantGarden.jsx  # Plant collection display
│   │   ├── StreakTracker.jsx # Daily streak counter & calendar
│   │   └── FocusTimer.jsx   # Pomodoro-style timer
│   ├── pages/
│   │   ├── index.jsx        # Main focus screen
│   │   ├── garden.jsx       # Plant collection page
│   │   └── stats.jsx        # Productivity stats & streak history
│   ├── hooks/
│   │   ├── useTimer.js      # Timer logic
│   │   ├── useStreak.js     # Streak tracking logic
│   │   └── useTree.js       # Tree growth state management
│   ├── store/
│   │   └── userStore.js     # Global state (Zustand/Redux)
│   └── styles/
│       └── globals.css
├── README.md
└── package.json
```

---

## 🎮 How It Works

1. **Start a focus session** — Set your timer and hit Start. A seed is planted.
2. **Stay focused** — Don't close or navigate away. Your tree grows as time passes.
3. **Complete the session** — Your tree fully grows and is saved to your forest.
4. **Check your streak** — Did you focus yesterday too? Your streak increases!
5. **Unlock plants** — Hit focus milestones to earn new plants for your garden.

---

## 🧰 Tech Stack

| Layer | Technology |
|---|---|
| Frontend | React / Next.js |
| Styling | Tailwind CSS |
| Animations | Framer Motion |
| State Management | Zustand |
| Storage | localStorage / Firebase (optional) |
| Clock | JavaScript `Date` API |

---

## 🎨 Customization

You can personalize the experience in `Settings`:

- **Timer duration** — Adjust focus and break lengths
- **Tree theme** — Choose from different tree styles (oak, cherry blossom, pine, cactus)
- **Clock format** — 12-hour or 24-hour
- **Ambient sounds** — Toggle rain, forest, or white noise during sessions
- **Dark / Light mode** — Switch themes based on your preference

---

## 📈 Roadmap

- [ ] User accounts and cloud sync
- [ ] Mobile app (React Native)
- [ ] Social streaks — compare streaks with friends
- [ ] Weekly & monthly focus reports
- [ ] More tree and plant species
- [ ] Browser extension for distraction blocking

---

## 🤝 Contributing

Contributions are welcome! Please follow these steps:

1. Fork the repository
2. Create a new branch: `git checkout -b feature/your-feature-name`
3. Make your changes and commit: `git commit -m "Add your feature"`
4. Push to your fork: `git push origin feature/your-feature-name`
5. Open a Pull Request

Please read [CONTRIBUTING.md](CONTRIBUTING.md) for our code of conduct and guidelines.

---

## 📄 License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

## 🙏 Acknowledgements

- Inspired by the [Forest App](https://www.forestapp.cc/)
- Tree and plant illustrations by [Your Artist / Source]
- Built with love for anyone trying to focus in a distracted world 🌱

---

> *"A tree is grown one focused session at a time."*
