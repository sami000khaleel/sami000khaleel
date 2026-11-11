<div align="center">

# Hi, I'm Sami Khaleel 👋

### Full-Stack Developer · Java · Spring Boot · TypeScript · React · Node.js

📍 Jülich, NRW, Germany &nbsp;·&nbsp; 🎓 B.Eng. Computer Engineering
💼 **Open to Junior Full-Stack / Web Developer roles**
🚀 **Available immediately:** already in Germany, no visa sponsorship needed

[**▶ TeachMe live demo**](https://teach-me-al46.onrender.com/home) &nbsp;·&nbsp;
[**🧩 Chrome extension (live)**](https://chromewebstore.google.com/detail/learn-languages-youtube-d/icbikjpimmfhofelddlfabbhpaombepm) &nbsp;·&nbsp;
[📧 Email](mailto:sami000khaleel@gmail.com) &nbsp;·&nbsp;
[💼 LinkedIn](https://www.linkedin.com/in/YOUR-LINKEDIN)

</div>

---

## 👨‍💻 About me

I'm a full-stack developer with a Computer Engineering degree and hands-on experience building real-time web applications. I focus on clean architecture, real-time features (WebRTC, Socket.IO), and AI integration in web apps.

I'm looking for my first professional role in Germany, where I can contribute to a team and keep growing as an engineer. I code daily, learn fast, and like solving real problems with code. Two of my projects below are **live right now**, so you can try them instead of just reading about them.

---

## 🛠 Tech stack

| | |
|---|---|
| **Backend** | Java, Spring Boot, Node.js, Express, REST APIs |
| **Frontend** | TypeScript, React, Vite, Tailwind CSS |
| **Databases** | MySQL, MongoDB |
| **Real time** | WebRTC, Socket.IO |
| **Security** | JWT, bcrypt, role-based access, rate limiting |
| **Other** | Git, Chrome Extensions (Manifest V3), Cloudflare R2, Render, AI / computer vision |

---

## 🚀 Featured projects

### 🎓 [TeachMe](https://github.com/sami000khaleel/teach-me): Live-Class Platform
A teacher starts a live video lesson, students join from the browser, and the teacher stays in control.

- **Try it:** [**live demo**](https://teach-me-al46.onrender.com/home). One click signs you in as the teacher, no sign-up. Open it in a second window to join as a student. *(Free hosting: the first load can take up to a minute. Turn your VPN off.)*
- **Features:** peer-to-peer video (WebRTC), screen sharing, raise hand, chat, per-student mute / stop video / remove, attendance reports
- **Engineering:** signaling over Socket.IO with JWT-checked handshake, ICE candidates queued until the remote description exists, live screen share via `replaceTrack`, moderation enforced on the server, private image storage on Cloudflare R2, one deployable service (Express serves the React build)
- **Stack:** `React` `Vite` `Tailwind` `Node.js` `Express` `WebRTC` `Socket.IO` `MySQL` `MongoDB`
- 🔗 [Live demo](https://teach-me-al46.onrender.com/home) · [Code](https://github.com/sami000khaleel/teach-me) · [Video walkthrough](https://onedrive.live.com/?qt=allmyphotos&photosData=%2Fshare%2FCA524006C0AC4FC8%21sba07ab39ff054fbe80ccbf94f38270bb%3Fithint%3Dvideo%26migratedtospo%3Dtrue&cid=CA524006C0AC4FC8&id=CA524006C0AC4FC8%21sba07ab39ff054fbe80ccbf94f38270bb&redeem=aHR0cHM6Ly8xZHJ2Lm1zL3YvYy9jYTUyNDAwNmMwYWM0ZmM4L0VUbXJCN29GXzc1UGdNeV9sUE9DY0xzQmtPdWhTRFZVMG9rWFY4UndaUGc0dmc&v=photos)

---

### 🧩 [Learn Languages: YouTube Dual Captions & Sentence Capture](https://chromewebstore.google.com/detail/learn-languages-youtube-d/icbikjpimmfhofelddlfabbhpaombepm): Chrome Extension
**Published on the Chrome Web Store.** Turns any YouTube video into a language lesson: the original subtitles and your translation appear together, you save sentences and words with one key, then practice them in built-in games.

- **Features:** dual captions you can drag and restyle, one-key sentence capture (**W**), click-to-translate words, sentence navigation (**A / S / D**), word game and listening game, export to `.json` / `.csv`, 47 languages including right-to-left ones
- **Engineering:** reads the player's own caption responses by wrapping `fetch` / `XHR` in the page context (no private API), rebuilds real sentences from raw auto-captions with per-language rules, generates and caches the interface translations on demand with placeholder validation, serialized storage writes
- **Privacy:** all data stays on the user's device, no tracking, no accounts, no backend
- **Stack:** `JavaScript` `Chrome Extensions (MV3)` `Web Speech API` `Intl.Segmenter` `chrome.storage`, zero dependencies
- 🔗 [**Install from the Chrome Web Store**](https://chromewebstore.google.com/detail/learn-languages-youtube-d/icbikjpimmfhofelddlfabbhpaombepm)

---

### 🏛 [2Syria](https://github.com/sami000khaleel/2syria): AI-Powered Tourism App
A MERN-stack app that helps tourists discover places in Syria using AI image search.

- **Features:** image-based place recognition (computer vision), location filter, user reviews
- **Stack:** `MongoDB` `Express` `React` `Node.js` `Python (Flask)` `Computer Vision`
- 🔗 [Demo](https://onedrive.live.com/?qt=allmyphotos&photosData=%2Fshare%2FCA524006C0AC4FC8%21s633ef9c6cbcb45d499fd12013e605811%3Fithint%3Dvideo%26migratedtospo%3Dtrue&cid=CA524006C0AC4FC8&id=CA524006C0AC4FC8%21s633ef9c6cbcb45d499fd12013e605811&redeem=aHR0cHM6Ly8xZHJ2Lm1zL3YvYy9jYTUyNDAwNmMwYWM0ZmM4L0VjYjVQbVBMeTlSRm1mMFNBVDVnV0JFQjMyd3VtZFg2YV9hUEdJMUNlMy1qNXc&v=photos) · [Code](https://github.com/sami000khaleel/2syria) · [Flask server](https://github.com/sami000khaleel/2syria-flask-server)

---

### 🌐 [Social Media Platform: Backend API](https://github.com/sami000khaleel/social-media-application/tree/main/server)
A production-style Node.js / Express REST API with posts, threaded comments, role-based communities, and a personalized recommendation engine.

- **Features:** JWT auth, threaded comments, community roles (manager / admin / member), AI content classification, personalized feed, cascading deletes, file uploads, notifications
- **Highlight:** custom recommendation algorithm using time decay, linear interpolation, and a derivative-based probability distribution to compose a dynamic feed per user
- **Stack:** `Node.js` `Express` `MongoDB` `Mongoose` `JWT` `bcrypt` `Multer` `Axios`
- 🔗 [Code](https://github.com/sami000khaleel/social-media-application/tree/main/server)

---

## 📫 Contact me

- 📧 **Email:** [sami000khaleel@gmail.com](mailto:sami000khaleel@gmail.com)
- 📞 **Phone:** +49 179 1761950
- 💼 **LinkedIn:** [add your link](https://www.linkedin.com/in/YOUR-LINKEDIN)
- 🧠 **Codewars:** [sami000khaleel](https://www.codewars.com/users/sami000khaleel)
- 📍 **Location:** Jülich, NRW, Germany

<div align="center">

*Open to Junior Full-Stack / Web Developer roles. Available immediately.*

</div>
