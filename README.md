# App Store privacy & support pages

Hosted free with GitHub Pages. Each app gets two pages:

- `https://YOURNAME.github.io/appstore/APP-FOLDER/privacy/`
- `https://YOURNAME.github.io/appstore/APP-FOLDER/support/`

## First-time setup

1. Create a **public** GitHub repo named `appstore`.
2. Upload all files in this folder (Add file → Upload files). Keep the `_layouts` folder.
3. Edit `_config.yml`: set your `company` name and `contact_email`.
4. Go to **Settings → Pages**, set Source to *Deploy from a branch*, choose `main` and `/ (root)`, and save.
5. After 1–2 minutes the site is live. The home page lists all your apps.

## Adding a new app

1. Copy the `example-app` folder and rename it, e.g. `my-new-app`
   (lowercase, hyphens, no spaces – it becomes part of the URL).
   In the GitHub web editor: open each file, click the pencil, and change the
   path at the top to `my-new-app/privacy.md` (and `support.md`) while
   creating a new file with the same contents.
2. In both files, change `app:` to the app’s name.
3. In `privacy.md`, set `updated:` to today’s date and edit the sections so
   they match what the app really collects.
4. Replace the `[bracketed]` placeholders, like `[Settings → Delete Account]`.
5. Paste the two URLs into App Store Connect.

Delete or rename `example-app` once you’ve set up your first real app.

## Optional: custom domain

1. At your DNS provider, add a CNAME record: `apps.yourcompany.com` → `YOURNAME.github.io`.
2. In **Settings → Pages**, enter the domain and tick **Enforce HTTPS**.
3. URLs then become `https://apps.yourcompany.com/APP-FOLDER/privacy/`.

## Note

The privacy text is a starting template, not legal advice. Make sure each
policy accurately describes the app, matches its App Privacy labels in
App Store Connect, and lists every third-party SDK that receives data.
