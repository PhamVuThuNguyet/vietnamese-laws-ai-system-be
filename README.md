# vietnamese-laws-ai-system-ai

# Getting Started

Getting started developing with this template is pretty simple using docker and docker-compose.

## Clone the repository

```
git clone https://github.com/VKU-NewEnergy/vietnamese-laws-ai-system-ai.git
```

## cd into project root

```
cd vietnamese-laws-ai-system-ai
```

## Launch the project

### Run by `make` command

- Copy `.env.example` to `.env` file

```
cp .env.example .env
```

- Fill in environment's values in `.env` file
- Run services

```
make install
```

### Run locally

```
pip install -r requirements.txt
python main.py
```

### Using docker

> :warning: Please make sure that you have Docker installed.

```
docker compose up
```

Afterwards, FastAPI automatically generates documentation based on the specification of the endpoints you have written. You can find the docs at http://localhost:9000/docs.
