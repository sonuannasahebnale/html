# ✅ HabitFlow — Habit Tracking Website

A clean, dark-themed habit tracker built with pure HTML, CSS, and JavaScript.  
No frameworks, no build step — just open the file and start tracking your habits.

---

## 🚀 How to View the Site

### Option 1 — Open directly in your browser (easiest)

1. [Download or clone this repository](https://github.com/sonuannasahebnale/html/archive/refs/heads/main.zip)
2. Unzip the folder (if downloaded as ZIP)
3. Double-click **`index.html`**

> The file opens in your default browser instantly — no server needed.

---

### Option 2 — GitHub Pages (view online, no download needed)

If the repository has GitHub Pages enabled, visit:

```
https://sonuannasahebnale.github.io/html/
```

To enable GitHub Pages yourself:
1. Go to the repository on GitHub
2. Click **Settings → Pages**
3. Under *Source*, choose **Deploy from a branch**
4. Select **`main`** branch and **`/ (root)`** folder
5. Click **Save** — your site will be live in about a minute at the URL above

---

### Option 3 — VS Code Live Server extension

1. Install the [Live Server](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer) extension in VS Code
2. Open the project folder in VS Code
3. Right-click `index.html` → **"Open with Live Server"**
4. The site opens at `http://127.0.0.1:5500` and auto-reloads on save

---

### Option 4 — Python built-in server

If you have Python installed, run this in the project folder:

```bash
# Python 3
python -m http.server 8080
```

Then open **http://localhost:8080** in your browser.

---

## 🌟 Features

| Feature | Description |
|---|---|
| Add habits | Give each habit a name and category |
| Daily check-off | Mark habits complete for today |
| 7-day heatmap | See your completion history at a glance |
| Streak counter | Consecutive-day streak per habit |
| Summary bar | Total habits · Done today · Best streak · Completion % |
| Category filters | Filter by Health, Mind, Productivity, Social, or Other |
| Persistent data | Everything saved in `localStorage` — no sign-up needed |

---

## 🗂 Project Structure

```
html/
├── index.html   ← App markup + JavaScript logic
└── style.css    ← Styles (dark theme, responsive)
```

---

## 🛠 Tech Stack

- **HTML5** — semantic structure
- **CSS3** — custom properties, flexbox, grid, responsive design
- **Vanilla JavaScript** — DOM manipulation, localStorage persistence
