# Using GitHub Web UI (No local GitHub app needed)

This project can be managed completely from github.com in your browser.

## Create a folder and upload your HTML app

1. Open your repository on GitHub.
2. Click **Add file** → **Create new file**.
3. In the filename box, type a path like:
   - `app/index.html`
4. Paste your HTML code.
5. Scroll down, add a commit message, and click **Commit changes**.

> Tip: typing `app/index.html` creates the `app` folder automatically.

## Upload multiple files (CSS, JS, images)

1. Click **Add file** → **Upload files**.
2. Drag and drop your files.
3. If needed, place files in folders by editing each destination path before commit (for example `app/styles.css`, `app/script.js`, `app/assets/logo.png`).
4. Commit changes.

## Move files into a folder using only the web UI

GitHub web does not have a direct "move" button, but you can rename a file path:

1. Open the file.
2. Click the **pencil** icon (Edit).
3. Change filename from `index.html` to `app/index.html`.
4. Commit changes.

Repeat for `styles.css`, `script.js`, etc.

## What to tell Codex after upload

After your files are committed, send a short message like:

- "My app is at `app/index.html`. Please review and improve it."

That path is enough for Codex to begin.
