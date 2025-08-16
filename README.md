# Context-Aware PDF Question Answering with LLMs

This project is a context-aware question answering system built on top of large language models (LLMs). It allows users to upload PDF documents and then ask natural language questions about the document’s content. The system uses advanced embedding and retrieval techniques to provide accurate, contextually relevant answers.

## Key Features:

Upload PDF documents for analysis

Ask questions in natural language about the uploaded content

Dynamic display of the LLM model used for answering

Responsive React frontend styled with Material-UI

Flask backend API serving health checks, file upload, and question answering endpoints

Dockerized setup for easy development and deployment

## How to run ?

```bash
$ cd compose
$ docker-compose up --build
```

* Check on `http://localhost:3000/` for React frontend
* Check on `http://localhost:5000/api/health` for Flask backend

## github codes

```bash
$ git config --local user.name "Sanjay Prabhu Kunjibettu"
$ git config --local user.email "41kusa1mst@hft-stuttgart.de"


git init --initial-branch=main
git remote add origin https://gitlab.rz.hft-stuttgart.de/41kusa1mst/context-aware-chatbot.git
git add .
git commit -m "Initial commit"
git push --set-upstream origin main
```
