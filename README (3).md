# POEMS — by snipxr

A personal digital poetry book that lives on GitHub Pages.

- **Readers** see a cover, an index, and the poems, with a light and dark theme, a live clock for their own time zone, optional ambient sound, and 17 hidden secrets.
- **You** (only you) get a private **Desk** where you write, edit, reorder, draft, preview, and publish poems.
- The whole site is **one file: `index.html`**. Your poems are saved in a file called `poems.json`, which the site creates for you the first time you publish.

---

## Set it up (about 5 minutes)

### 1. Create the repository
1. Sign in at **github.com** (make a free account if you need one).
2. Click **+** (top right) → **New repository**.
3. Name it `poems`, choose **Public**, and click **Create repository**.

### 2. Upload the site
1. In the repository click **Add file → Upload files**.
2. Drag in **`index.html`** (keep the name exactly `index.html`).
3. Click **Commit changes**.

### 3. Turn the website on
1. Open **Settings → Pages**.
2. Under **Branch** pick **main** and **/ (root)**, then **Save**.
3. After 1 to 2 minutes your site is live at:
   `https://YOURUSERNAME.github.io/poems/`

### 4. Make your private key (one time)
1. Click your profile picture → **Settings → Developer settings → Personal access tokens → Fine-grained tokens → Generate new token**.
2. **Name:** `poems`. **Expiration:** 1 year.
3. **Repository access:** *Only select repositories* → choose `poems`.
4. **Repository permissions → Contents → Read and write.**
5. Click **Generate token** and **copy it now** (it starts with `github_pat_`; GitHub shows it only once).

### 5. Unlock the Desk and publish
1. Open your site and click **Desk** (or click **SNIPXR** 7 times).
2. Enter `YOURUSERNAME/poems` and paste your token, then click **Unlock the desk**.
3. Click **+ New poem**, write it, tick **published**, and press **Save**.
4. Press **Publish to site**. Readers see it on the same link in about a minute.

---

## Using the Desk

| I want to… | Do this |
|---|---|
| Add a poem | **+ New poem** → fill in → **Save** |
| Keep a poem private | Leave **published** unticked (a private draft, stored on this device only) |
| Make it public | Tick **published** → **Save** → **Publish to site** |
| Change the order | Use the **↑ ↓** buttons, then **Publish to site** |
| Change the title or tagline | Edit the boxes → **Save title & tagline** → **Publish to site** |
| See it as readers do | Open a poem in the form and press **Preview** |
| Delete a poem | **Edit** → **Delete**, then **Publish to site** |
| Lock the Desk | **Log out** |

## Good to know
- **Only you can edit.** The lock is GitHub itself: nobody can publish without your token, and the token is never inside `index.html`.
- **Keep the token secret.** It stays in your browser on this device. On a new device, paste it again. If it leaks, delete it in GitHub and make a new one.
- **Updates take about a minute** to reach readers after you press **Publish to site**.
- **Drafts are private** but live only in this browser, so publish a poem to keep it safely on GitHub. Clearing your browser data deletes unpublished drafts.
- **Back it up.** Your published poems are the file `poems.json` in this repository, and you can download it any time.

## Troubleshooting

| Problem | Fix |
|---|---|
| 404 at your address | Wait 2 more minutes; check Settings → Pages is saved and the file is named `index.html` |
| "GitHub did not accept that token" | Copy it again, or make a new token |
| "That token cannot write to this repository" | Re-check step 4: *Contents → Read and write*, and the right repository |
| Poems don't appear for readers | Press **Publish to site**, then wait a minute and refresh |
| Blank page | Open the `github.io` address, not the file from your computer |

## Time, location and devices
- **The clock** uses the visitor's device time zone. Tap it, then tap **◎ Use my location** to let the browser confirm where they are. The clock then switches to that place's time and shows sunrise and sunset there. A visitor in California sees California time, one in the Maldives sees Maldives time.
- **Phones and tablets:** swipe left or right on a poem to turn the page. Three secrets are phone-only: shake the phone, press and hold a poem's title, and touch the screen with three fingers.
- **Game consoles and TVs:** plug in or pair a controller. The D-pad moves between buttons, **A** selects, **B** goes back, and left/right turn poem pages. Arrow keys work on a TV remote. On very large screens the site scales up automatically.

## Easter eggs
Press **?** on the site (or click **✦ 0/17**) to see clues. Finding all 17 has a finale. No spoilers here.
