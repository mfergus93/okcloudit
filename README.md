# okCloudIT

Static GitHub Pages website for okCloudIT cloud services.

## Local preview

```bash
python -m http.server 8000
```

Open `http://localhost:8000`.

## GitHub Pages deployment

1. Open the repository's **Settings** on GitHub.
2. Select **Pages** under **Code and automation**.
3. Choose **Deploy from a branch**.
4. Select the `main` branch and `/(root)` folder.
5. Save and wait for the Pages deployment to complete.

## Project structure

```text
okCloudIT/
|-- index.html
`-- static/
    |-- css/style.css
    `-- js/main.js
```

## Contact form

The static form opens the visitor's email application with the entered details prefilled. Replace this behavior with a Cloudflare Worker or another form backend when server-side delivery, spam protection, and submission tracking are required.

## Legacy deployment files

The Flask, Docker, GitLab CI, and AWS App Runner files remain in the repository for reference but are not used by GitHub Pages. They can be removed after the static deployment is accepted.
