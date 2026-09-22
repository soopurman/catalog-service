# catalog-service

A minimal FastAPI CRUD API. Run `docker compose up --build`, then visit `/` for its route index, `/docs` for Swagger UI, or `/items` for seeded data on port 8000. In a deployed preview it is mounted beneath `/a` (for example `/a/docs` and `/a/items`). Branches named `fg/<feature>` join the matching feature group in `orders-service`; all other branches get an independent preview.
