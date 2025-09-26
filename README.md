# 🏆 Club Commander

Club Commander is an event and team management web app built with **HTML, TailwindCSS, and Firebase**.  
It helps clubs manage events, teams, members, and tasks — with features like task assignment, deadlines, leaderboards, and member history.  

## 🚀 Features
- 🔑 User authentication (Login / Register) with **Firebase Auth**
- 📅 Create and manage events
- 👥 Add teams and assign members
- ✅ Assign, edit, complete, and delete tasks
- ⏰ Deadline tracking & overdue task alerts
- 🏆 Member leaderboard with points system
- 📊 Work history tracking
- 🤖 Built-in AI assistant for quick suggestions (frontend demo)

## ⚙️ Tech Stack
- **Frontend:** HTML, TailwindCSS, JavaScript
- **Backend:** Firebase (Auth + Realtime Database)
- **Storage:** LocalStorage (fallback when not logged in)

## 📂 Project Structure
```
club_commander_Final.html   # Main HTML file (contains all logic)
README.md                   # Project documentation
```

## 🛠️ Getting Started
1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/club-commander.git
   cd club-commander
   ```

2. Open `club_commander_Final.html` in your browser.

3. To enable Firebase features:
   - The Firebase configuration is already included.
   - Make sure the Firebase project exists (or update the `firebaseConfig` inside the HTML with your own project’s config).

## 🌐 Deployment Options
### GitHub Pages
1. Push this repo to GitHub.
2. Go to **Settings → Pages**.
3. Select `main` branch → `/ (root)`.
4. Your app will be live at:
   ```
   https://your-username.github.io/club-commander
   ```

### Firebase Hosting (Recommended)
1. Install Firebase CLI:
   ```bash
   npm install -g firebase-tools
   ```
2. Login:
   ```bash
   firebase login
   ```
3. Initialize hosting:
   ```bash
   firebase init hosting
   ```
   - Select your Firebase project
   - Set public directory to `.`
   - Configure as single-page app? **No**
4. Deploy:
   ```bash
   firebase deploy
   ```
5. Your app will be live at:
   ```
   https://yourproject.web.app
   ```

## 📸 Screenshots
*(Add screenshots/gifs of your app here)*

## 📜 License
This project is licensed under the MIT License — feel free to use and modify it.

---

👨‍💻 Built with ❤️ using Firebase + TailwindCSS
