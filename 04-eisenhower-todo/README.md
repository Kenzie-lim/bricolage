# eisenhower-todo (아이젠하워투두)

Eisenhower matrix TODO app. Add tasks with a deadline and priority quadrant (urgent/important axes), then check them off. Data persists via a Google Apps Script backend.

Stack: Vanilla HTML/JS, Google Apps Script, PWA.

## Setup

This app talks to a Google Apps Script backend. The URL for that backend is **not** included in the repo (for security), so you need to add it yourself.

**Step by step:**

1. In this folder, find the file called `config.example.js`
2. Make a copy of it and rename the copy to `config.js`
3. Open `config.js` in any text editor
4. Replace `YOUR_SCRIPT_ID` with your actual Google Apps Script URL
5. Save — done. The app will now connect to your backend.

`config.js` is listed in `.gitignore`, so it won't accidentally get pushed to GitHub.

> If you don't have a Google Apps Script backend yet, you'll need to create one that handles `add`, `done`, and `GET` (fetch all) actions. The expected request/response format is in `index.html`.
