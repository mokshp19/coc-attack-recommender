# Clash of Clans Attack Recommender

A web application that analyzes a Clash of Clans base image and suggests
high-probability attack strategies assuming the attacker is the same Town Hall level.

## Features
- Upload a base image
- Automatically classify base archetype
- Recommend suitable attack strategies with reasoning
- Designed to learn from user feedback over time

## Tech Stack
- Frontend: Next.js (TypeScript)
- Backend: FastAPI (Python)
- ML: PyTorch / OpenCV (planned)
- Database: PostgreSQL (planned)

## Architecture
Frontend uploads an image → Backend analyzes layout →
Recommendation engine scores strategies → Results returned to UI.

## Status
🚧 Early development (MVP)

## Disclaimer
This project is not affiliated with or endorsed by Supercell.
