# 📜 Quote Sage App

**Quote Sage** is a sleek and dynamic React-based web app that fetches and displays random motivational quotes from a public API. Users can switch between light and dark themes, like quotes, copy them to the clipboard, adjust font size, and even download them as an image.

---

## 🚀 Features

- 🔁 Fetch a new random quote from the [ZenQuotes API](https://zenquotes.io/)
- ❤️ Like quotes with a visual toggle
- 🌗 Light and Dark theme toggle
- 📋 Copy quotes to clipboard
- ⬇️ Download quotes as PNG images using `html2canvas`
- 🔠 Font size customization (Small, Medium, Large)
- 🎨 Stylish and responsive layout

---

## 📸 Demo

[Include a live link or screenshot here if hosted.]

---

## 🛠️ Tech Stack

- **HTML5**, **CSS3**
- **React (via CDN with Babel)**
- **Axios** for HTTP requests
- **html2canvas** for downloading quotes as images

---

## 🧠 How It Works

1. On load, the app fetches a random quote using the ZenQuotes API.
2. The user can:
   - Click "🔁 New Quote" to fetch another
   - Toggle between light/dark mode
   - Like a quote
   - Copy it to the clipboard
   - Download it as an image
   - Adjust the font size

---

## 📂 Project Structure

Since this project is built using a single `index.html` file:

- `index.html` – Main entry file containing React code using JSX and Babel
- Styles and script are embedded for simplicity

---

## 🚧 Setup Instructions

You can run this project simply by opening `index.html` in your browser.

No build step or `npm install` required. Just:
1. Download the project folder.
2. Open `index.html` in a browser.
3. Enjoy your daily dose of inspiration!

---

## 📌 API Used

- [ZenQuotes.io](https://zenquotes.io/) – Returns an array of quote objects:
```json
[
  {
    "q": "Quote text",
    "a": "Author name"
  }
]
