# RUN

create `.env` file with the following content

```
OPENAI_API_KEY=sk-proj-adfskjfsadlkjfalskdglasasdfsadfg
```

then run

```bash
docker compose -f docker-compose.yaml -f docker-compose.searxng.yaml up -d
```

if update

```bash
docker-compose pull
docker-compose up -d
```

# TODO

- [ ] add sonnet claude 3
