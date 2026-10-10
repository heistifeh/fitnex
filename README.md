<h1 align="center">Fitnex</h1>
<p align="center"><b>The workout tracker built for serious lifters.</b><br/>Log every set, beat every record, and share your gains.</p>

<p align="center">
  <a href="https://fitnexonline.com"><img src="https://img.shields.io/badge/Live%20app-fitnexonline.com-111?style=for-the-badge" alt="Live app"/></a>
  <img src="https://img.shields.io/badge/React-19-61DAFB?style=for-the-badge&logo=react&logoColor=black" alt="React 19"/>
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white" alt="TypeScript"/>
  <img src="https://img.shields.io/badge/Supabase-3FCF8E?style=for-the-badge&logo=supabase&logoColor=white" alt="Supabase"/>
</p>

## Overview

Fitnex is a progressive web app for tracking strength training. It installs on your phone's home screen like a native app, stores your workouts in Supabase, and turns your training history into charts and shareable progress cards.

**Live:** [fitnexonline.com](https://fitnexonline.com)

## Features

- Log workouts set by set, with weights and reps
- Track personal records and progress over time with charts
- Generate shareable progress images to post on X
- Installable PWA with a mobile-first UI
- Accounts and cloud sync with Supabase

## Tech stack

| Area | Tools |
|---|---|
| Frontend | React 19, TypeScript, Vite, React Router |
| State | Zustand, Immer |
| Styling & motion | Tailwind CSS, Framer Motion, Lucide icons |
| Data & auth | Supabase |
| Charts & sharing | Recharts, html2canvas |

## Running locally

```bash
git clone https://github.com/heistifeh/fitnex.git
cd fitnex
npm install
```

Create a `.env` file with your Supabase project keys:

```bash
VITE_SUPABASE_URL=your-project-url
VITE_SUPABASE_ANON_KEY=your-anon-key
```

```bash
npm run dev     # start the dev server
npm run build   # type-check and build for production
```

## Author

Built by **Boluwatife Osineye**. [Portfolio](https://boluwatifeosineye.com) · [LinkedIn](https://linkedin.com/in/boluwatifeosineye) · [X](https://x.com/tifethedev)
