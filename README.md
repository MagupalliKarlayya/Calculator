# OnePlus-Style Calculator

This project is a static calculator web app (`index.html`) and can be hosted publicly using **GitHub Pages**.

## Publish to GitHub (public URL)

1. Create a new GitHub repository and push this code.
2. In the GitHub repo, open **Settings → Pages**.
3. Under **Build and deployment**, select **GitHub Actions** as the source.
4. Push to the `main` branch (or your default branch).
5. Wait for the **Deploy static content to Pages** workflow to complete.

Your public URL will be:

`https://<your-github-username>.github.io/<your-repo-name>/`

For this project, the app entry page is `index.html`, so the URL above will open it directly.

## Local run

```bash
python3 -m http.server 4173 --bind 0.0.0.0 --directory .
```

Open:

`http://localhost:4173/index.html`
