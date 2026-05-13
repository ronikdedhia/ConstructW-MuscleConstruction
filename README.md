# ConstructW — Muscle Construction

A web platform for the construction industry built during a 24-hour hackathon. ConstructW connects construction companies with skilled workers, streamlining workforce procurement and project management in a domain traditionally reliant on informal hiring.

## Features

- Worker profiles with skills, availability, and ratings
- Company dashboard for posting job requirements
- Worker discovery and filtering by skill and location
- Project assignment and tracking
- Analytics dashboard with charts (ApexCharts)
- Responsive UI with dark/light mode toggle

## Tech Stack

| Layer | Technology |
|-------|-----------|
| Frontend | Next.js, React |
| UI Components | Material UI (MUI) |
| Charts | ApexCharts (react-apexcharts) |
| Backend | Node.js (Express) |
| Styling | MUI ThemeProvider |

## Getting Started

```bash
git clone https://github.com/ronikdedhia/ConstructW-MuscleConstruction.git
cd ConstructW-MuscleConstruction
```

### Frontend

```bash
cd app
npm install
npm run dev
```

Frontend runs at `http://localhost:3000`

### Backend

```bash
cd backend
npm install
npm start
```

## Project Structure

```
app/            # Next.js frontend
  src/
    @core/      # Layout, theme, shared components
    pages/      # Next.js pages (dashboard, workers, jobs)
backend/        # Express API server
working/        # Hackathon demo assets
```

## Built At

24-hour hackathon — construction industry track.

## License

MIT
