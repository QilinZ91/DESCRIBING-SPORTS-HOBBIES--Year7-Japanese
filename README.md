# Year 7 Japanese — Sports & Hobbies Revision (interactive)

A single-page, self-contained interactive worksheet. Students type answers, press **Check answers**,
and get instant marking. Work auto-saves in the browser. No build step, no dependencies — just `index.html`.

## Features
- Auto-marking for matching, fill-ins, translations, kana-hunt and the script-sort activity
- "Build the sentence" task checks romaji **and** hiragana against the adjective the student picks
- **wa** / **desu** shown in green throughout
- Show/Hide kana, Reveal answers, Reset, live score bar
- Progress saved automatically (browser localStorage)
- Works on phones, tablets and laptops

---

## Publish on GitHub Pages

Your site: **https://nothingcomesone.github.io/**

### Option A — make it your homepage (cleanest URL)
1. On GitHub, create a **new repository** named exactly `nothingcomesone.github.io`.
2. Click **Add file → Upload files**, drag in `index.html`, and **Commit**.
3. Go to **Settings → Pages**. Under *Build and deployment*, set **Source = Deploy from a branch**,
   **Branch = main**, folder **/ (root)**, then **Save**.
4. Wait ~1 minute, then open **https://nothingcomesone.github.io/** 🎉

### Option B — keep it as one page among others
1. Create a repo, e.g. `japanese-revision`, and upload `index.html`.
2. **Settings → Pages → main / root → Save**.
3. It appears at **https://nothingcomesone.github.io/japanese-revision/**.

### Using git from your computer
```bash
cd japanese-revision-site
git init
git add .
git commit -m "Interactive Japanese revision worksheet"
git branch -M main
git remote add origin https://github.com/nothingcomesone/nothingcomesone.github.io.git
git push -u origin main
```

### Preview locally first
Just double-click `index.html` — it opens in any browser and works offline.

---

## Sharing with students
Give them the link (or a QR code to it). Each student's answers save in **their own** browser only,
so everyone works independently. Tell them to use the same device/browser to keep their progress.

## Editing content
All questions and answers live in the `<script>` data arrays near the bottom of `index.html`
(`S1A`, `S2B`, `S5C`, etc.). Answers accept alternatives separated by `|` (e.g. `archery|kyudo`).
