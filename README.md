# Dashboards Without Code

Training materials for **Dashboards Without Code Using Microsoft Power BI: From Data to Decisions**, a 4-hour hands-on session on 28 Nov 2026, 9:00 AM to 1:00 PM MYT.

## What's here

- `index.html`: redirects to the board, so the GitHub Pages root link works.
- `board.html`: the session web app. Pages: Board (`#board`), Ground rules (`#ground-rules`), Lego case study (`#lego`), Miro brainstorm (`#brainstorm`), Feedback QR (`#feedback`) and the trainer run sheet (`#run-sheet`). Press **Present** for full screen; arrow keys move between participant pages.
- The session board: A Padlet-style page with one column per block of the day (prep, welcome, Modules 1 to 4, break, follow-up), every activity, checkpoint and Power BI link, plus a minute-by-minute **trainer run sheet** at `board.html#run-sheet`.

Open `board.html` in any browser. No build step. It loads the Poppins font from Google Fonts and qrcodejs from cdnjs (for the Miro QR).

## Miro board

Set `MIRO_DEFAULT` near the top of the script in `board.html` to your public Miro board link, or paste the link on the Brainstorm page (saved in that browser). On GitHub Pages the board is also embedded live.

## Publishing with GitHub Pages

Settings → Pages → Deploy from a branch → `main` / root. The app is then at `https://yushabdullah.github.io/DWC/`.
