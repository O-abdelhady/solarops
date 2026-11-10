# SolarOps

Web app for small commercial solar operators: turns daily production data into prioritized, dollar-valued maintenance decisions.

- Live app: https://o-abdelhady.github.io/solarops/
- Backend: Supabase (Postgres with row-level security, Edge Functions, scheduled sync). The page contains only the public (publishable) client key; all data access is enforced by the database.
- Analytics: deterministic, explainable rules (EPI, shortfall, anomaly detection). Anomalies flag performance deviations; they do not confirm equipment faults. Dollar figures are estimates.
- Includes an offline demo with synthetic data.
