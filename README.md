# bindery


A literay agent that supports aspiring authors in their journey of delivering a manuscript. 

## Overview

add what this project is about 

## Setup Instructions

How to get this running locally

### Set up environment variables

Go to `./backend` and create `.env` file. Follow the example in `.env.example`.

### Backend Setup

The backend is built using the LangChain CLI and utilizes LangGraph's `create_react_agent` for agent creation.

```bash
cd backend
poetry install
poetry run python -m app.server
```

### Frontend Setup

The frontend is generated using the assistant-ui CLI tool.

```bash
cd frontend
yarn install
yarn dev
```

## Credits

Based on https://github.com/hminle/langserve-assistant-ui