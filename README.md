# 🔥 Firebase Site Starter

> **Launch a beautiful static site in 5 minutes ⚡ — in just 6 easy steps!**

A simple **static landing page template** perfectly configured for **Firebase Hosting**.
Use it as your starting point for:

* 💼 Client marketing pages
* 💡 Quick prototypes
* 🌐 Fast-deploy static sites

---

## 🎁 What's Inside

✅ Minimal **HTML/CSS layout** (hero, about, features, contact)
📱 **Mobile-friendly** design with editable colors & fonts
⚙️ **Firebase CLI scripts** for one-command deploys + local emulation
✏️ Placeholder content & clear callouts for easy customization

---

## 🧰 Prerequisites

Before you start, make sure you have:

* 🟢 **Node.js 18+**
* 🔥 **Firebase project** (create one in the [Firebase Console](https://console.firebase.google.com/))
* 🧑‍💻 **Firebase CLI** (install & log in)

  ```bash
  npm install -g firebase-tools
  firebase login
  ```

---

## ⚡ Getting Started (6 Steps, 5 Minutes!)

> Follow these **6 quick steps** to go from zero → live site 🌍

### 1️⃣ Clone this repo

```bash
git clone https://github.com/FrancescoRec/Firebase-Site-Starter.git
cd Firebase-Site-Starter
```

### 2️⃣ Install dependencies

```bash
npm install
```

### 3️⃣ Connect your Firebase project

```bash
firebase use --add
```

Choose your project and set it as the default.
Optionally, add an alias (`default`, `staging`, `prod`) for easy switching 🔄.

### 4️⃣ Run locally

```bash
npm run dev
```

🔥 Launches a live preview with auto-reload at
👉 [http://localhost:5000/](http://localhost:5000/)

### 5️⃣ Customize your site

- 🖋️ Refresh the **brand name, navigation links, and page copy** in `index.html`.
- 🎨 Tweak the **color and spacing tokens** at the top of `style.css` to match your visual identity.
- 🤖 Want inspiration fast? Drop the markup into your favorite AI assistant for quick headline or layout ideas.
- ⚡ All changes you make to your files will be reflected in real time on localhost. Just save and see your updates instantly!


### 6️⃣ Deploy to production

```bash
npm run deploy
```

Deploys to Firebase Hosting using your `firebase.json` config.
🎉 Boom — your site is live!

## 🗂️ Directory Overview

```
.
├── index.html      # Landing page markup
├── style.css       # Global styles and theme tokens
├── 404.html        # Default Firebase Hosting 404 page
├── firebase.json   # Hosting configuration
├── .firebaserc     # Stores the default Firebase project alias
└── package.json    # NPM scripts + firebase-tools dependency
```

---

🧡 **Done!** You just built and deployed a Firebase site in **5 minutes and 6 steps**.
Now go make it yours 🎉


