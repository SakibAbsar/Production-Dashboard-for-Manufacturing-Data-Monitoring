# MES Dashboard

This project is a real-time dashboard for monitoring MES metrics using Blazor and ASP.NET Web API.

## Features
- Real-time display of production rate, machine uptime, and error logs
- API endpoints to update and retrieve MES metrics
- Easy-to-deploy with Docker

## Setup
1. Clone the repository: `git clone <your_repo_url>`
2. Run with Docker: `docker-compose up`
3. Access the frontend at `http://localhost:5001`

## API Endpoints
- `GET /api/metrics` - Retrieves current metrics
- `POST /api/metrics` - Updates metrics
