# Jeremy Xu — Portfolio

Personal portfolio for Jeremy Xu, Lead Data Engineer (Snowflake, dbt, Airflow, Python, LangChain).

A single static page (`index.html`) with an animated isometric data-pipeline backdrop drawn in SVG. No build step or dependencies; fonts load from Google Fonts.

## Run locally

Open `index.html` in a browser, or serve the folder:

```bash
python3 -m http.server 8000
```

## Deploy

Every push to `main` deploys to GitHub Pages through the workflow in `.github/workflows/deploy.yml`. It can also be run by hand from the Actions tab.

One-time setup: in **Settings › Pages**, set **Source** to **GitHub Actions**.
