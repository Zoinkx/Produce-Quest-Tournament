# Produce Quest — 1v1 Tournament

An interactive single‑page web app where you pick between **Produce Quest** contestants in head‑to‑head (1v1) matchups. Your choices generate a **personal ranking** from #1 to the rest.

## Demo

Live at:
➡️ **[https://zoinkx.github.io/Produce-Quest-Tournament/](https://zoinkx.github.io/Produce-Quest-Tournament/)**

## How it works

* A **double‑elimination** style flow presents two contestants at a time.
* Click a side to advance your pick; progress is tracked with a bar.
* When all matches are resolved, you’ll see a **final placements** screen (1st, 2nd, 3rd, plus the full ordered list).
* State is saved in `localStorage` so you can refresh without losing progress.

## Tech Stack (Languages Used)

* **HTML** — single‑file layout and markup
* **CSS** — custom styles in a `<style>` block (no frameworks)
* **JavaScript (Vanilla)** — tournament logic, rendering, and localStorage

> All three live together in one file: `index.html`.

## Data & Media

* Contestant metadata (age, height, birthday, etc.) is defined in JavaScript objects.
* **Profile images** are linked directly via **URLs** to the official *Produce Quest* website or other web sources (no local images required).
* Each contestant card includes a **YouTube performance** embed (via `<iframe>`).

## Getting Started

1. **Clone / download** this repo.
2. Keep the folder simple:

   ```
   / (repo root)
   └─ index.html
   ```
3. Open `index.html` directly in your browser, or use a local server (e.g., VS Code Live Server) to avoid any embed/security quirks.

## Deploy (GitHub Pages)

1. Create a **public** GitHub repository and push the file.
2. In the repo: **Settings → Pages**

   * Source: **Deploy from a branch**
   * Branch: `main` • Folder: `/` (root)
3. Save — wait a minute — the **Pages URL** appears at the top of that section.

## Customization

* **Add / edit contestants**: update the `RAW` array and `DETAILS` object in the `<script>` of `index.html`.
* **Change visuals**: tweak CSS variables in the `:root` section (colors, shadows, spacing).
* **Reset**: there’s a floating **Reset** button that clears `localStorage` and reloads.

## Notes on Media & Attribution

* **Images and videos** are sourced from official *Produce Quest* platforms — the official website and YouTube channel.
* This site is **non‑commercial and fan‑made**, created for entertainment and ranking purposes only.
* All image and video rights belong to **Produce Quest** and their respective copyright holders.
* Please respect their **Terms of Service** when forking or redistributing this project.

## License

MIT — for the original code and structure only (HTML, CSS, and JavaScript).
All external media remain property of their original owners.

## Repo Description (one‑liner)

> 1v1 bracket picker for the YouTube girl‑group survival show *Produce Quest* — built with HTML, CSS, and vanilla JavaScript; outputs your personal ranking.
