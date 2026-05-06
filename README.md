# KWN Al-Cu Precipitation Hardening Dashboard

A real-time interactive simulator for Al-Cu precipitation hardening kinetics using the Kampmann-Wagner Numerical (KWN) framework.

## Features
- **Adjustable aging temperature** (120–280°C)
- **Configurable aging time** (10–500 hours)
- **Variable Cu content** (1–6 wt%)
- **Live simulation** with phase evolution tracking
- **Microstructure visualization** at any point in time
- **Real-time hardness plots** with peak hardness detection

## Local Development
```bash
npm install
npm run dev
```

Open `http://localhost:5000` and navigate to `dashboard.html`

## Deployment
This project is deployed on Vercel and requires no backend. The simulation runs entirely in the browser using JavaScript.

## References
- Robson & Bhadeshia, MSEA (1997)
- Zhu et al., Acta Materialia (2004)
- Starink et al., MSEA (2012)
