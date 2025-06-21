
# 🚀 Crypto Tracker

[![Netlify Status](https://api.netlify.com/api/v1/badges/YOUR_NETLIFY_BADGE/deploy-status)](https://crypto-tracker2025.netlify.app/)
[![GitHub Issues](https://img.shields.io/github/issues/your-username/your-repo-name.svg)](https://github.com/your-username/your-repo-name/issues)
[![GitHub Forks](https://img.shields.io/github/forks/your-username/your-repo-name.svg)](https://github.com/your-username/your-repo-name/network)
[![GitHub Stars](https://img.shields.io/github/stars/your-username/your-repo-name.svg)](https://github.com/your-username/your-repo-name/stargazers)
[![License](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)

> A modern, responsive cryptocurrency tracker built using React, Firebase, and CoinGecko API. Track real-time prices, save favorite coins, authenticate users, and toggle dark/light mode.

🌐 **Live Site**: [crypto-tracker2025.netlify.app](https://crypto-tracker2025.netlify.app/)

---

## 📸 Screenshots

![Home Page](./screenshots/home.png)
![Watchlist](./screenshots/watchlist.png)

---

## ✨ Features

- 🔁 Real-time cryptocurrency price updates
- 🔍 Search and filter through 100+ coins
- 📈 Detailed charts and market info
- 🔐 Google Authentication (Firebase)
- 📄 Watchlist saved in Firestore
- 💡 Dark/Light Mode toggle
- ⚙️ Fully responsive UI with Material-UI

---

## 🚦 Getting Started

Follow the steps below to run the project locally.

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/your-repo-name.git
cd your-repo-name
```

### 2. Install Dependencies

```bash
npm install
```

### 3. Set Up Firebase

- Go to [Firebase Console](https://console.firebase.google.com/) and create a new project.
- Enable **Google Sign-In** in Authentication > Sign-in Method.
- Enable **Cloud Firestore** from Build > Firestore Database.
- In your project settings, find your config object and paste it into `src/firebase.js`:

```js
const firebaseConfig = {
  apiKey: "YOUR_API_KEY",
  authDomain: "YOUR_AUTH_DOMAIN",
  projectId: "YOUR_PROJECT_ID",
  storageBucket: "YOUR_STORAGE_BUCKET",
  messagingSenderId: "YOUR_MESSAGING_SENDER_ID",
  appId: "YOUR_APP_ID"
};
```

### 4. Start the Development Server

```bash
npm start
```

> App will run on: [http://localhost:3000](http://localhost:3000)

---

## 🗂️ Project Structure

```
src/
├── components/        # Reusable components
├── pages/             # Home, CoinDetail, Watchlist
├── firebase.js        # Firebase configuration
├── App.js             # Main app logic
├── index.js           # Entry point
public/
└── index.html
```

---

## 🚀 Deployment

### Deploy to Netlify

1. Run:
   ```bash
   npm run build
   ```
2. Drag & drop the `build` folder into [Netlify](https://netlify.com/)
3. Or connect your GitHub repo for auto-deploys.

### Deploy to GitHub Pages

1. Install:
   ```bash
   npm install gh-pages --save-dev
   ```
2. Update your `package.json`:
   ```json
   "homepage": "https://your-username.github.io/your-repo-name",
   "scripts": {
     "predeploy": "npm run build",
     "deploy": "gh-pages -d build"
   }
   ```
3. Run:
   ```bash
   npm run deploy
   ```

---

## 🧑‍💻 Contributing

Contributions are welcome!

1. Fork the project
2. Create your branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some feature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

---

## 🐛 Issues

Report bugs or request features here:  
[https://github.com/your-username/your-repo-name/issues](https://github.com/your-username/your-repo-name/issues)

---

## 📄 License

Licensed under the [MIT License](LICENSE)

---

## 🙏 Acknowledgements

- [CoinGecko API](https://www.coingecko.com/en/api)
- [Firebase](https://firebase.google.com/)
- [Material-UI](https://mui.com/)
- [Netlify](https://www.netlify.com/)

---

## 📬 Contact

**Author:** [Your Name](https://github.com/your-username)  
**Email:** your.email@example.com

> Made with 💖 for crypto enthusiasts!
