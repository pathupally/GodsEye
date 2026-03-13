# GodsEye Frontend

This directory contains the primary operator console for GodsEye.

## Run

```bash
npm install
npm run dev
```

## Environment

- `VITE_WS_URL`
- `VITE_API_URL`
- `VITE_CESIUM_ION_TOKEN`
- `VITE_OPENWEATHER_API_KEY`
- `VITE_WAQI_TOKEN`

The frontend expects the backend at `http://localhost:3001` unless you override those values.

## Notes

- The console uses CesiumJS with imperative layer rendering for high-entity-count scenes.
- Live state is driven by WebSocket plus REST fetches for on-demand domains.
- The frontend targets the active JavaScript backend in `/Users/adrianmathew/Code/GodsEye/backend`, which preserves the promoted operator-facing contracts.
