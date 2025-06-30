# Portfolio Manager Codex

This repository provides a very small starter project for building a portfolio
management application.  It contains:

* **backend/** – an ASP.NET Core Web API (`.NET 8`)
* **frontend/** – a React application bootstrapped with Vite and TypeScript

## Prerequisites

* [.NET 8 SDK](https://dotnet.microsoft.com/) installed
* [Node.js](https://nodejs.org/) and npm available

## Running the backend

```bash
cd backend
dotnet run
```

The API is available by default at `http://localhost:5000` and exposes a sample
`/weatherforecast` endpoint.

## Running the frontend

```bash
cd frontend
npm install  # only required the first time
npm run dev
```

Vite serves the app on `http://localhost:5173`.  API calls to the backend are
allowed through a permissive CORS policy for development purposes.
