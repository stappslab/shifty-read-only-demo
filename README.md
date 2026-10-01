# Shifty read-only demo bundle

This folder is the complete static demo bundle for sharing the Shifty interface. It contains no application backend, database, secrets, or real employee records.

## Publish with GitHub Pages

1. Create a new **public** GitHub repository, for example `shifty-read-only-demo`.
2. Upload the contents of this folder to the repository root: `index.html` and `shifty-full-app.html`.
3. Commit the files to the `main` branch.
4. In GitHub, open **Settings → Pages**.
5. Under **Build and deployment**, choose **Deploy from a branch**, select `main` and `/(root)`, then save.
6. Wait for the Pages deployment to finish. Share the URL shown in the Pages settings, usually `https://<username>.github.io/shifty-read-only-demo/`.

The preview is static. Navigation and calendar controls are client-side examples; the Generate button only displays a simulated result. It does not access or change the live Shifty app or its SQLite database.
