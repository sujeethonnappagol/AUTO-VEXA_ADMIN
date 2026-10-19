# Auto-Vexa Admin Portal

Role-specific Auto-Vexa admin frontend deployment.

## Build and deploy

1. Copy `.env.example` to `.env` and set `VITE_API_URL` to the deployed Auto-Vexa API URL.
2. Run `npm install` and `npm run build`.
3. Deploy the dist/admin directory as the static site output.

This frontend only permits the configured role. It shares the API and MongoDB database with the other Auto-Vexa portals; the API enforces permissions.
