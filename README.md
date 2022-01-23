# Clinic

## Installation

```bash
git clone https://github.com/fahiraaa06/clinic-frontend.git

cd clinic-frontend

docker-compose up --build -d

curl http://127.0.0.1:9004
```

# Host Local To Internet

```bash
ngrok http 8080 -host-header="localhost:8080"
ngrok start --config=./ngrok.yml --all
```
