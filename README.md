# ZAY-MAN Birthday Protocol

A self-contained birthday landing page for Zaryab (Zay-Man).

## Deploy to GitHub Pages

1. Create a new GitHub repository, for example `zayman-birthday`.
2. Upload `index.html` to the repository root.
3. Go to **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select the `main` branch and `/ (root)`, then save.
6. GitHub will provide a public URL such as:
   `https://YOUR-USERNAME.github.io/zayman-birthday/`

## Personalize the birthday message

Open `index.html` and search for:

- `const PERSONAL_MESSAGE`
- `const ZAYMAN_TRANSLATION`

Replace the text inside the backticks with your final message.

Everything else is contained in the same HTML file. No npm, build step, backend, or external library is required.
