# Countries Explorer

A responsive React + TypeScript web app for exploring every country in the world, using live data from the [REST Countries API](https://restcountries.com/).

## Features

- **Browse all countries** – flag, name, population, region and capital on each card
- **Search** countries by name
- **Filter by region** (Africa, Americas, Asia, Europe, Oceania)
- **Country details page** – native name, population, region, sub-region, capital, currencies and languages
- **Border countries** – jump straight to any neighbouring country
- **Light / dark mode** – your choice is saved in localStorage
- **Responsive layout** – designed for mobile (375px) and desktop (1440px)

## Tech stack

- React 18 + TypeScript
- Vite
- Material UI (MUI)
- React Router v6
- Axios

## Getting started

```bash
git clone https://github.com/IshaqueAppiah/countriesApi.git
cd countriesApi
npm install
npm run dev
```

Then open the local URL Vite prints (usually http://localhost:5173).

To create a production build:

```bash
npm run build
npm run preview
```

## Project structure

```
src/
├── api.ts                  # REST Countries API calls
├── App.tsx                 # Routes + dark-mode state
├── useLocalStorage.ts      # Custom hook for persisted state
├── components/             # NavBar, Home, Country pages
├── HomeComponents/         # Search, Filter, Card
└── CountryComponents/      # Details view
```

## Author

**Ishaque Appiah** – Front-end developer (React, Angular, TypeScript)
