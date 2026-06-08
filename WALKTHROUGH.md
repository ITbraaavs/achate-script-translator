# Script Translator — Walkthrough

A simple guide to using the Script Translator app (`script-translator.html`).
It turns a Dutch script into a clean Dutch → English table, lets you copy it
into Google Docs, download a PDF, pull the voiceover text for ElevenLabs, and
keeps a history of everything you've translated.

---

## Opening the app

1. **Double-click `script-translator.html`** — it opens in your web browser.
2. That's the whole app. Nothing to install.

> Tip: bookmark it in your browser, or in Chrome use **⋮ → Cast, Save and Share →
> Create shortcut** (check *Open as window*) to give it its own app-like window.

You need an internet connection only for the **Translate** step. Everything else
(copy, PDF, history) works offline.

---

## Step 1 — Paste your script

1. In Google Docs, select the rows of your script table and **copy** them (Cmd+C).
2. Click inside the big text box in the app and **paste** (Cmd+V).

Your script should be in the `Nummer / Type / Script / Shots` layout — the same
one you already use. The app reads each cell automatically.

> Not sure it'll work? Click **Load sample** to drop in an example script you can
> practice with.

---

## Step 2 — Parse the script

1. Click **① Parse script**.
2. The app builds a table with these columns:
   - **Nummer** · **Type** · **Script (NL)** · **Script (EN)** · **Shots (NL)** · **Shots (EN)**
3. The English columns are empty for now — that's expected.

**Every cell is editable.** If anything landed in the wrong spot, just click the
cell and fix it before translating.

---

## Step 3 — Translate to English

1. Click **② Translate to English**.
2. A progress bar shows it working through each row.
3. When it finishes, the **Script (EN)** and **Shots (EN)** columns fill in, and
   the result is **saved to History automatically**.

> The translator is free and needs no setup, but has a daily limit. If you ever
> see a "limit reached" message, wait a bit and try again.

---

## Step 4 — Get your results out

After translating, a row of export buttons appears:

### 📋 Copy for Google Docs
Copies the **whole table**. Switch to Google Docs, click where you want it, and
press **Cmd+V** — it pastes as a real formatted table.

### 🎙️ Copy Script (NL) for ElevenLabs
Copies **only the Dutch voiceover text** (the Script NL column), as clean
plain text with each line as its own paragraph. Paste it straight into
ElevenLabs to generate the voiceover. No numbers or shot descriptions are
included, so nothing extra gets read aloud.

### Copy as TSV
Copies the table as tab-separated text — best for pasting into a **spreadsheet**
(Google Sheets / Excel), where each piece drops into its own cell.

### ⬇️ Download PDF
Saves the full bilingual table as a PDF to your Downloads folder.

### 💾 Re-save edits
Only needed if you edit cells *after* translating and want to store that updated
version in History.

---

## History (right-hand panel)

- **Saved automatically** after every translation — newest at the top.
- Each entry shows the opening line, the date/time, and the row count.
- **Click an entry** to reload that whole translated table.
- Click the **✕** on an entry to delete just that one.
- **Clear all** (top of the panel) wipes the entire history (asks you to confirm).

> History is stored in *this browser, on this computer*. It stays between sessions,
> but it won't follow you to a different browser or machine.

---

## Light / Dark mode

- Use the **🌙 Dark / ☀️ Light** button in the top-right to switch themes.
- Your choice is remembered the next time you open the app.

---

## Quick reference

| I want to… | Do this |
|---|---|
| Start over | **Clear** button (clears the paste box and table) |
| Fix a wrong translation | Click the cell, edit it, then **Re-save edits** |
| Put it in Google Docs | **📋 Copy for Google Docs** → paste in Docs |
| Make the voiceover audio | **🎙️ Copy Script (NL) for ElevenLabs** → paste in ElevenLabs |
| Put it in a spreadsheet | **Copy as TSV** → paste in Sheets/Excel |
| Save a file to send | **⬇️ Download PDF** |
| Reopen an old translation | Click it in the **History** panel |

---

## Typical workflow, start to finish

1. Copy your script rows from Google Docs.
2. Paste into the app → **Parse** → **Translate**.
3. **📋 Copy for Google Docs** to drop the bilingual table into your doc.
4. **🎙️ Copy Script (NL) for ElevenLabs** to generate the voiceover.
5. Done — it's already saved in History if you need it again later.
