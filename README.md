# Mattetränaren

A static HTML export of Mattetränaren, prepared for GitHub Pages.

## Preview locally

Open `index.html` in a modern browser.

## Publish with GitHub Pages

1. Create a new repository on GitHub.
2. Extract this ZIP and upload **the contents** of this folder to the repository's top level (so `index.html` is at the root, not inside another folder).
3. Commit the files to the `main` branch.
4. In the repository, open **Settings → Pages**.
5. Under **Build and deployment**, choose **Deploy from a branch**.
6. Select branch **main** and folder **/(root)**, then click **Save**.
7. Open the URL shown in the Pages settings after the deployment completes.

GitHub's instructions: https://docs.github.com/en/pages/getting-started-with-github-pages/creating-a-github-pages-site

## Important security note

The current sign-in screen is implemented entirely in browser-side HTML/JavaScript. Its usernames and passwords are embedded in `index.html` and can be discovered by anyone who can access the page or repository. It is only a visual/convenience gate, **not real access control**. GitHub Pages websites are publicly available on the internet, even when the source repository is private (subject to GitHub's plan and settings).

Do not publish this version as a private or password-protected service, and do not use these credentials for anything else. For genuine protection, replace this gate with server-side authentication or a hosting-layer access-control service before making the site public.
