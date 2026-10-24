# Pictures service

Flask API for the band website's picture records. This project started from the IBM Skills Network capstone template.

## Endpoints

`GET /health`, `GET /count`, `GET /picture`, `GET /picture/<id>`, `POST /picture`, `PUT /picture/<id>`, and `DELETE /picture/<id>`.

## Local development

Install Flask and pytest in a Python environment, then run `python -m pytest` and `python app.py`. The API listens on port 8080. Picture records are seeded from `backend/data/pictures.json` and changes are kept in memory for the process lifetime.
