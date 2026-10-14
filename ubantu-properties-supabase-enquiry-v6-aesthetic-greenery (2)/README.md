# Ubantu Properties — Supabase enquiry version

This build sends website enquiries directly to the Supabase `public.enquiries` table.

## Supabase setup already required
- Table: `public.enquiries`
- RLS enabled
- Anonymous INSERT policy enabled

## Important security note
The browser contains the Supabase publishable key. This is expected for a Supabase frontend when Row Level Security is configured correctly. Never put a Supabase `service_role`/secret key in this website.

## Deploy
Upload the folder containing `index.html`, `styles.css`, and all image assets to your static host (such as Netlify).
