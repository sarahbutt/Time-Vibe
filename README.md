# 🌍 Time Vibe

### [👉 Try it Live Here](https://sarahbutt.github.io/Time-Vibe/)

**Time Vibe** is a zero-dependency, natural language time zone converter that lives entirely in your browser.

Designed for people who hate "time zone math," it allows you to type conversational queries like *"7pm Austin to Dublin"* or *"in 2 hours in Tokyo"* and get instant, accurate results that account for Daylight Saving Time automatically.

## ✨ Features

* **💬 Natural Language Processing:** Understands "to", "in", "into", "ago", and "from".
* **⚡ Zero Dependencies:** Written in pure HTML/JS. No libraries, no API keys, no tracking.
* **📱 Responsive Design:** Works perfectly on Desktop, Mobile (iOS/Android), and Tablets.
* **🧠 Context Aware:** Tells you if the converted time is "Tomorrow" or "Yesterday".
* **🌎 Massive Database:** Supports hundreds of major cities, countries, and time zone codes (EST, CET, IST, etc.).
* **🔮 Future/Past Math:** Calculates relative time (e.g., "in 90 minutes" or "3 hours ago").

## 🚀 How to Use

Simply open the website and type. The interface is designed to be as fast as a terminal but as friendly as a chat bot.

### Examples

**Standard Conversion:**
> `17:05 Austin to Dublin`
> `7pm EST to UTC`
> `9am London to Sydney`

**Current Time Lookup:**
> `Time in India`
> `Paris`
> `What time is it in California?`

**Relative Time (Future/Past):**
> `in 2 hours in London`
> `in 45 mins in CST`
> `2 hours ago in Tokyo`

## 🛠️ Installation & Deployment

Because this project is a **Single File Application**, deployment is instant.

### Option 1: Run Locally
1.  Download the `index.html` file.
2.  Double-click it.
3.  That's it!

### Option 2: Host on GitHub Pages (Recommended)
1.  Fork this repository.
2.  Go to **Settings** > **Pages**.
3.  Select `main` branch as source and hit **Save**.
4.  Your site is live!

## 💻 Tech Stack

* **Core:** HTML5, CSS3, ES6 JavaScript.
* **Math Engine:** Uses the browser's native `Intl.DateTimeFormat` API for atomic-level time zone accuracy without external libraries.

## 📝 License

This project is open source and free to use.

---
*Maintained by the Time Zone Wizards.*
