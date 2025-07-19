# 🎯 SkillRack Analyzer

An Android app to track and analyze SkillRack points using your **public SkillRack profile**.  
Supports viewing DC/DT scores, CodeTrack ranks, medals, and more — even offline after the first fetch.

---

## 🚀 Features

- 🔹 Add multiple SkillRack profiles
- 🔹 Name, Department, Rank, Medals, Points display
- 🔹 Offline access after first fetch
- 🔹 Swipe to Delete, Copy, or View Info
- 🔹 Refresh profile data in background
- 🔹 Floating Action Button (FAB) for quick add
- 🔹 JSON-based local storage
- 🔹 Clean Material UI with:
  - Blue-black background
  - Sky blue profile cards

---

## 🛠️ Tech Stack

- **Language:** Kotlin  
- **UI:** RecyclerView, Material Design  
- **Async:** Kotlin Coroutines  
- **Scraping:** Jsoup (no SkillRack login required)  
- **Storage:** SharedPreferences (as JSON)  

---

## 📦 APK Download

👉 [Download the Latest APK](https://github.com/balax-24/skillrack-analyzer-app/releases/tag/skillrack-analyzer-apk)  


## 📃 Notes

- This app scrapes publicly available SkillRack profiles.
- If SkillRack changes its HTML structure, update the scraper logic in `SkillRackScraper.kt`.
- No login required.

---

## 👤 Author

Made with ❤️ by [Balaharish](https://balaharish.netlify.app)  
🔗 GitHub: [github.com/balax-24](https://github.com/balax-24)

---
