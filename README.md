# CardioSight Clinical Risk Console

A GitHub-ready Flask project for Render deployment. This app presents a polished hospital-style UI for cardiovascular disease risk screening using a saved machine learning pipeline.

## Deployment-ready files
- `app.py`
- `requirements.txt`
- `.python-version`
- `render.yaml`
- `templates/index.html`
- `static/styles.css`
- `model/` (put the saved `.joblib` model here)
- `model/model_metadata.json`

## Local run
```bash
python -m venv .venv
# Windows
.venv\Scripts\activate
pip install -r requirements.txt
python app.py
```


