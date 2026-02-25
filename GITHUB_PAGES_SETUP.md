# Enable GitHub Pages so the Car Simulation runs at kagunye.github.io/DRIVE-THRU

If you see **"There isn't a GitHub Pages site here"** (404), use the steps below.

---

## Option A: Deploy with GitHub Actions (recommended)

The repo includes a workflow that deploys the site automatically.

### 1. Make the repo **Public**

- **Settings** → **General** → change **Visibility** to **Public** (private repos on a free account don’t get public Pages).

### 2. Set Pages to use **GitHub Actions**

- Open: **[GitHub Pages settings](https://github.com/Kagunye/DRIVE-THRU/settings/pages)**
- Under **Build and deployment**, set **Source** to **GitHub Actions** (not "Deploy from a branch").
- Click **Save**.

### 3. Run the workflow

- Go to the **Actions** tab: **https://github.com/Kagunye/DRIVE-THRU/actions**
- Open the **"Deploy to GitHub Pages"** workflow.
- Click **Run workflow** → **Run workflow** (or push a commit to `main`; the workflow runs on every push to `main`).

### 4. Wait and open the site

- Wait **2–3 minutes** for the workflow to finish (green check).
- Open: **https://kagunye.github.io/DRIVE-THRU/**

---

## Option B: Deploy from a branch

If you prefer not to use Actions:

1. **[GitHub Pages settings](https://github.com/Kagunye/DRIVE-THRU/settings/pages)** → **Source**: **Deploy from a branch**.
2. **Branch**: **main** → **/ (root)**.
3. **Save**, then wait 2–5 minutes and open **https://kagunye.github.io/DRIVE-THRU/**.

---

## If it still shows 404

- Confirm the repo is **Public** (Settings → General).
- Confirm **Source** is **GitHub Actions** (Option A) or **Deploy from a branch** with **main** and **/ (root)** (Option B).
- Wait up to 5 minutes and try again, or use an incognito/private window.
- For Option A: in the **Actions** tab, check that the latest **Deploy to GitHub Pages** run completed successfully (green check).
