# HayNardi Privacy Policy

This repository hosts the official public Privacy Policy for **HayNardi**, an Armenian Long Nardi mobile game for Android (`com.haynardi`).

The policy is intended to provide the permanent public URL required by:

- Google Play Console
- Google AdMob and the Google User Messaging Platform (UMP)

The site is a single lightweight HTML page. It has no framework, analytics, trackers, external JavaScript, or cookies of its own.

## Local preview

Open `index.html` directly in a web browser. No build step or local server is required.

If you prefer to preview it through a local web server and have Python installed, run:

```powershell
python -m http.server 8000
```

Then open `http://localhost:8000/` in your browser.

## Publish with GitHub Pages

1. Create a **public** GitHub repository named `haynardi-privacy`.
2. Push this repository's `main` branch to GitHub.
3. In the GitHub repository, open **Settings > Pages**.
4. Under **Build and deployment**, select **Deploy from a branch**.
5. Select the `main` branch and the `/ (root)` folder, then save.

The expected public URL format is:

```text
https://<github-username>.github.io/haynardi-privacy/
```

Here, `<github-username>` denotes the GitHub account that owns the repository. Use the resulting public URL in Google Play Console and Google AdMob / UMP after confirming that it opens without authentication.

## Contact

Privacy questions: hovhannespetrosyan67@gmail.com

## Security note

No passwords, access tokens, signing credentials, AdMob credentials, or other secrets belong in this repository.
