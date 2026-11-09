# Vesper AI Assistant

Vesper is a personal assistant that runs in your browser. It has a glowing 3D core, saved chats, a Today page, timers, tasks, private memory, world clocks, exact math and conversions, slash commands, a command menu (Ctrl or Cmd + K), and a Customize panel for its name, personality, colors and more.

Everything is stored in each visitor's own browser. There is no server and no account.

## Put it online with GitHub Pages (free)

1. Sign in at [github.com](https://github.com) and create a new **public** repository, for example `vesper`.
2. In the new repository, choose **Add file → Upload files**. Upload every file from this folder:
   `index.html`, `manifest.webmanifest`, `favicon.svg`, `icon-192.png`, `icon-512.png`, `apple-touch-icon.png` and `README.md`.
   If you got a zip, unzip it first and upload the files inside, not the zip itself.
3. Choose **Commit changes**.
4. Go to **Settings → Pages**. Under **Build and deployment**, set **Source** to **Deploy from a branch**, then choose the **main** branch and the **/ (root)** folder, and select **Save**.
5. Wait a minute or two, then refresh that page. Your site address appears at the top. It looks like `https://YOUR-USERNAME.github.io/vesper/`.

On a phone, you can open the site and use **Add to Home Screen** to get it as an app with its own icon.

## What works on the website

These work for every visitor, instantly and for free:

- **Timers, reminders and focus sessions**, with a chime when they finish.
- **Tasks and memory**, saved in the visitor's browser.
- **World clocks, date math, unit conversions, tips and exact math.**
- **Passwords** made on the device.
- **Code:** a Run button for Python and JavaScript, and a live Preview for HTML.
- **Customize**, saved chats, the Today page, slash commands and the command menu.

Open-ended AI replies need an AI behind them. On the website, Vesper runs its built-in, on-device skills. For full AI replies, use Vesper inside Claude or the desktop version, which uses a free local model through Ollama.

## Updating the site

Upload a new `index.html` to the repository with **Add file → Upload files**. It replaces the old one, and GitHub Pages updates within a minute or two.
