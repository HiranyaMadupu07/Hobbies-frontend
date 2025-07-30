# Environment Variables Setup

This project uses Vite and requires environment variables to be set in a `.env` file in the project root.

## Required Environment Variable

- `VITE_API_URL`: The base URL of your backend API server.

### Example `.env` file content:

```
VITE_API_URL=http://localhost:5000
```

Replace `http://localhost:5000` with the actual URL where your backend API is running.

## Important

After creating or updating the `.env` file, you must restart the Vite development server to load the new environment variables.

## Troubleshooting

If you see errors related to API calls or URLs containing `undefined`, please verify that the `.env` file exists and contains the correct `VITE_API_URL` value.
