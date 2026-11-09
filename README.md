# SmartUnfollow website

Static, no-build landing page for the SmartUnfollow browser extension. This folder is intended to be the complete contents of a separate public GitHub repository; it does not include the extension source or local configuration.

## Publish with GitHub Pages

1. Create a public GitHub repository named `smartunfollow-site` and upload the contents of this folder to its `main` branch.
2. In the repository, open **Settings → Pages** and set **Build and deployment → Source** to **GitHub Actions**.
3. The included workflow deploys the site on each push to `main`. When the first deployment succeeds, GitHub displays its public URL under **Settings → Pages**. For the `smartunfollow-site` repository, the standard URL is `https://<account>.github.io/smartunfollow-site/`.
4. Put that public URL in X Developer Console's **Website URL** field. Keep the `chromiumapp.org` URL in **Callback URI / Redirect URL**.
