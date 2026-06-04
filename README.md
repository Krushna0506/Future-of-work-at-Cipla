# Cipla Forward — The Future of Work

An interactive, executive-facing dashboard visualising **intelligent automation potential** across the enterprise — role by role, division by division.

It maps **622 positions across 12 divisions** to an automation percentage, and lets you drill from a high-level overview down to a single role's task-level breakdown (what can be automated, what stays human, and the recommended technology stack).

---

## 🔎 What's inside

This is a **single, self-contained file** — `index.html`. Everything (data, styling, charts, interactions) is embedded, so:

- It works by simply **double-clicking the file** — no server, no internet, no build step.
- It works **as a live website** on GitHub Pages with zero configuration.

### Three levels of detail
1. **Overview** — every division as a card with its automation gauge, plus a ranked comparison chart. Hover for the top clusters.
2. **Division** — a cluster breakdown chart and a searchable, filterable grid of every role.
3. **Role** — full scope, automatable vs. human-led split, the reasons work stays manual, and a mapped technology stack.

---

## 🚀 Put it online with GitHub Pages (free, ~3 minutes)

You'll get a shareable link like `https://YOUR-USERNAME.github.io/cipla-forward/`.

### Option A — GitHub website (no tools needed)
1. Go to **github.com** → click **New repository**.
2. Name it `cipla-forward`, choose **Private** (recommended — this is internal), click **Create repository**.
3. On the new repo page, click **uploading an existing file**.
4. Drag in **`index.html`** (and `README.md` if you like), then **Commit changes**.
5. Go to **Settings → Pages**.
6. Under **Branch**, pick `main` and folder `/ (root)`, then **Save**.
7. Wait ~1 minute, refresh — your live link appears at the top of the Pages screen.

> **Note:** GitHub Pages on a **Private** repo requires a paid plan (Team/Enterprise). On a **free** account, Pages only works for **Public** repos. If this must stay private and free, keep it Public-with-no-Pages and just share the `index.html` file directly (it opens fine offline), or host it on internal infrastructure.

### Option B — Git command line
```bash
git init
git add index.html README.md
git commit -m "Cipla Forward dashboard"
git branch -M main
git remote add origin https://github.com/YOUR-USERNAME/cipla-forward.git
git push -u origin main
# then enable Pages under Settings → Pages
```

---

## 🖥️ Just want to share it without GitHub?

Because it's one self-contained file, you can also:
- **Email** `index.html` and have anyone open it in a browser.
- Drop it on **SharePoint / Google Drive / internal portal**.
- Open it locally and **Print → Save as PDF** for a static handout.

---

## ✍️ Editing the content

All role data lives inside `index.html` in a single JavaScript object near the top of the `<script>` block (look for `const DATA =`). Each role has its scope, automatable tasks, manual tasks, reasons, and technology stack.

If you'd like a cleaner editing workflow (data in a separate file / spreadsheet that regenerates the page), that can be set up — ask and it'll be provided.

---

## ⚠️ Data note

- **Human Resources** and **Finance** reflect detailed role-and-process assessment.
- The other **10 divisions are illustrative models** built on the same methodology and pharma-industry benchmarks to show enterprise scale. They are labelled **"Illustrative"** in the interface and should be **validated with each division's COE leads** before any execution decisions.
- All percentages are **directional**. Every role retains essential human judgment.

---

**Confidential — internal use only.** Cipla · Enterprise Transformation.
