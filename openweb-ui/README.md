# RUN

create `.env` file with the following content

```
OPENAI_API_KEY=sk-proj-adfskjfsadlkjfalskdglasasdfsadfg
```

then run

```bash
docker compose -f docker-compose.yaml -f docker-compose.searxng.yaml up -d
```

## setup pipelines

see https://docs.openwebui.com/pipelines/#-quick-start-with-docker

# UPDATE

if update

```bash
docker-compose pull
docker-compose up -d
```

# TODO

- [ ] migrate anthropic api to use function instead of pipeline
