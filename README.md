Hi, I'm Ran 👋  
3rd-year Software Engineering student at Afeka College.

🚀 I build real-world applications with a focus on Android, backend systems, recommendation systems, and clean architecture.

📌 Featured Projects:
-
⭐ PlayNext – Personalized Steam Game Recommendation Engine (Main Project) ⭐
- FOMO – Social Competition Android App
- SuperMarket – C-based Management System
- Save The Princess – Unity 2D Game

---

## 💼 Projects

⭐ **[PlayNext – Personalized Steam Game Recommendation Engine](https://github.com/Ranavivcs/PlayNext)**  
A full-stack Steam game recommender built around a real, explainable ranking algorithm — implemented from scratch, not an AI wrapper. It links your Steam account, learns your taste from the games you own and how long you've played them, and ranks the games you don't own yet. A separate AI layer only *explains* each pick — it never ranks.

**Key Features:**
- Hybrid ranking engine using classic CS algorithms: TF-IDF + cosine similarity, multi-source Dijkstra over a k-NN game graph (transitive similarity), and Kruskal MST single-linkage clustering for diversity
- Adaptive engine that detects whether a library is focused or diverse and tunes its weighting per user
- Learning-to-rank + an offline evaluation harness (NDCG@10, leave-one-out, de-biased synthetic benchmark) — content beats a popularity baseline by ~2 orders of magnitude
- Grounded AI "why this match?" explanations (Claude), generated after ranking — explains, never ranks
- Steam OpenID + Steam Web API + SteamSpy ingest, with a ~2,500-game enriched catalog
- Supabase (Postgres + pgvector + Auth) with row-level security

**Tech:** Next.js 16, React 19, TypeScript, Supabase, Claude API, Steam Web API, Vercel

> ⚠️ Requires a Supabase project, a Steam Web API key, and an Anthropic API key. See the repo README for setup.

---

📱 **[FOMO - Android App](https://github.com/Ranavivcs/FOMO_App)**  
A social competition app designed to turn "Fear of Missing Out" into motivation.  
Users join groups, log activities, compete in challenges, and track leaderboards.  
Includes **Firebase Auth**, **Firestore**, **Google Maps**, **FCM push**, and Firebase Functions.

---

🧰 **[Mini Supermarket - Java Project](https://github.com/Ranavivcs/MiniSupermarket-Java)**  
A compact Java OOP project modeling a supermarket. Includes core classes like Product, Buyer, Cart, and MarketManager, with a focus on inheritance and encapsulation.

---

🛒 **[SuperMarket C Project](https://github.com/Ranavivcs/SuperMarket_C_Project)**  
A modular C program managing customers, products, and shopping carts — using binary file I/O and dynamic memory.

---

🚀 **[Space Dodge Android Game](https://github.com/Ranavivcs/DodgeGameApp)**  
Fast-paced Android game where you dodge meteors in a spaceship using buttons or sensors.

---

👑 **[Save The Princess - Unity Game](https://Ranavivcs/Unity_Game_Project)**  
A 2D platformer built in Unity — jump, dodge, and fight your way to rescue the princess using classic game mechanics and modular C# scripting.

---

## 🛠 Tech Stack

**Languages:** C, Java, Python, Kotlin, TypeScript  
**Frameworks:** Next.js, Firebase, Supabase  
**Tools:** Android Studio, Git, Visual Studio, Unity  
**Concepts:** OOP, Clean Architecture, Recommendation Systems, Memory Management, REST APIs

---

## 📫 How to Reach Me

- 📧 ranaviv.cs@gmail.com  
- 💼 https://www.linkedin.com/in/ran-aviv-9581aa328
