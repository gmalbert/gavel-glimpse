# Gavel Glimpse

A static HTML portfolio hub for four legal-data projects:

- [Granite State Appeals](https://www.granitestateappeals.com/)
- [Supreme Scrutiny](https://www.supremescrutiny.com/)
- [Relief Docket](https://www.reliefdocket.com/)
- [New Hampshire Case Law Research](https://www.nhcaselaw.com/)

Open `index.html` for the current layout featuring New Hampshire Case Law Research. The previous layout is archived in the ignored `old/` folder.

To serve the pages locally from this directory:

```text
python -m http.server 8000
```

Then visit <http://localhost:8000/index-nh-case-law.html>.

`footer.py` contains a reusable Streamlit footer component for the Granite State Appeals and Supreme Scrutiny repos. Replace `GAVEL_GLIMPSE_URL` with the final deployed URL before copying it into those projects.
