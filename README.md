# cs2-dm

### Setup
Clone and set up the repo
```bash
git clone https://github.com/Bims-sh/cs2-dm && \
cd cs2-dm && \
mkdir -p cs2 && \
chown 1000:1000 cs2
```

### Setup .env
Copy the env example and edit the variables
```
cp .env.example .env
```

### Start
Start the container with docker compose
```bash
docker compose up -d
```
