# Fasal-Mitra AI

Satellite-based crop monitoring and irrigation advisory MVP.

## Objective
Use free Sentinel satellite images, weather data, and soil data to estimate crop health, water stress, and field-specific irrigation requirement.

## MVP Workflow
Field Boundary → Satellite + Weather + Soil Data → Feature Processing →
Crop/Stress Analysis → FAO-56 Advisory → Dashboard + Alert

## Tech Stack
- Frontend: Next.js, React, TypeScript, MapLibre, Tailwind CSS
- Backend: FastAPI, PostgreSQL, PostGIS
- Data: Sentinel-1/2, Open-Meteo, SoilGrids
- ML: Python, Scikit-learn/PyTorch
- Advisory: FAO-56-inspired irrigation rules
- Deployment: Docker

## Team
- Nirmal: Leader, frontend, integration, pitch
- Navneet: Data processing and feature engineering
- Sanyogita: Testing, validation, irrigation/advisory science
- Sahil Sir: Backend, database, deployment
- Pragya: Geospatial data and irrigation inputs
- Abhi: AI/ML crop intelligence

## Safety Note
This MVP provides satellite-based estimates. Field verification is required before any costly or irreversible agricultural action.
