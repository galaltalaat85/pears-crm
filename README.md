# Pears Construction CRM (Vercel version)

Files:
- index.html   the CRM
- api/leads.js the server function that saves leads in Upstash Redis

Environment variables (Vercel > Project > Settings > Environment Variables):
- CRM_PASSWORD  the password people type to open the CRM
- KV_REST_API_URL and KV_REST_API_TOKEN  added automatically when you connect Upstash Redis in the Storage tab
