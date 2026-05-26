# Portafolio Personal — Guillermo Ubeda

> **Data & BI Analyst** · React 19 + Vite + Firebase Hosting · 9 proyectos interactivos
> **Status:** Deployed to production · 2026-05

[![Live](https://img.shields.io/badge/Live-proyectos--personales.web.app-60a5fa?style=for-the-badge&logo=firebase&logoColor=white)](https://proyectos-personales.web.app)
[![Stack](https://img.shields.io/badge/Stack-React%2019%20+%20Vite-61dafb?style=for-the-badge&logo=react&logoColor=white)](.)
[![Domain](https://img.shields.io/badge/Domain-Data%20%26%20BI-34d399?style=for-the-badge)](.)

---

## Project Status

| Phase | Status |
|---|---|
| Portafolio base (9 proyectos) | Done |
| Soporte bilingüe ES/EN | Done |
| Dashboards interactivos con Recharts | Done |
| Deploy Firebase Hosting | Done |

---

## Project Overview

Sitio de portafolio personal con dashboards interactivos para cada proyecto de Data & BI. Construido en React 19 + Vite con soporte bilingüe (ES/EN), datos pre-agregados en JSON estático y despliegue en Firebase Hosting.

Los datos del dashboard ETL son generados por el pipeline [project-sales-weather-etl](https://github.com/Guillermo1987/project-sales-weather-etl) y se incluyen como assets estáticos.

---

## Proyectos incluidos

| Ruta | Proyecto | Dominio |
|------|----------|---------|
| `/etl` | Sales & Weather ETL | Data Engineering |
| `/executive` | Executive Dashboard 360° | BI & RevOps |
| `/churn` | Churn Analysis | Data Science |
| `/hotel` | Hotel Pricing Engine | Revenue Management |
| `/ia-digox` | Consultoría Tech | AI Automation |
| `/automations` | Automatizaciones n8n | Workflow Automation |
| `/dashboards` | Power BI / Tableau | BI Embed |

---

## Tech Stack

| Layer | Technology |
|---|---|
| Frontend | React 19, React Router |
| Build | Vite |
| Charts | Recharts |
| i18n | LangContext propio (ES/EN) |
| Hosting | Firebase Hosting (Spark) |

---

## Repository Structure

```
project-portfolio/
├── public/data/     # JSONs estáticos pre-agregados (assets del portafolio)
├── src/
│   ├── components/  # Gráficos Recharts por proyecto
│   ├── contexts/    # LangContext (ES/EN)
│   └── pages/       # Una página por proyecto
├── firebase.json
└── .firebaserc
```

---

## How to Run

```bash
git clone https://github.com/Guillermo1987/project-portfolio.git
cd project-portfolio
npm install
npm run dev          # localhost:5173
```

### Deploy

```bash
npm run build
firebase deploy --only hosting:portfolio --token "$FIREBASE_TOKEN"
```

---

## Links

- **Portfolio:** [proyectos-personales.web.app](https://proyectos-personales.web.app)
- **LinkedIn:** [Guillermo Ubeda Garay](https://www.linkedin.com/in/guillermo-ubeda-garay)
- **Email:** guille.ubeda.garay@gmail.com

---

*Built by [Guillermo Ubeda](https://github.com/Guillermo1987) · Data & BI Analyst · MBA · ISC2 CC*
