# GitHub Pages Setup Instructions

## 1. Upload these files to the repo root

Upload all of the following to `life-sciences-market-update-2026` under the
`lifescienceconsultants` organisation:

- `index.html`
- `.nojekyll`
- `robots.txt`
- `README.md`

**Add file → Upload files** on the repo page, drag them in, write a commit
message, then **Commit changes**.

## 2. Turn on GitHub Pages

1. Go to the repo's **Settings** tab
2. Click **Pages** in the left sidebar
3. Under **Source**, choose **Deploy from a branch**
4. Set branch to **main** and folder to **/ (root)**
5. Click **Save**

## 3. Check it's live

Wait a minute or two, then visit:

https://lifescienceconsultants.github.io/life-sciences-market-update-2026/

If it shows a 404, double check `index.html` is spelled exactly that way
and sits in the repo root (not inside a subfolder).

## 4. Making future updates

- Small text/content changes: edit `index.html` directly in GitHub's web
  editor (pencil icon on the file) and commit
- Bigger changes: edit locally, then re-upload via **Add file → Upload
  files** and commit — GitHub Pages will rebuild automatically
