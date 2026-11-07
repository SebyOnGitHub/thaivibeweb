# ThaiVibe Official Web & Privacy Hub

This repository contains the official landing page and Google Play Store compliance documents (Privacy Policy, Terms of Service, Account & Data Deletion) for the **ThaiVibe** dating app.

## Structure

- `index.html`: Modern, responsive landing page introducing ThaiVibe.
- `privacy.html`: Google Play-compliant Privacy Policy covering Supabase, Firebase Cloud Messaging, GPS location handling, and data safety.
- `delete-account.html`: Dedicated web portal explaining account and data deletion mechanisms (Google Play Data Safety requirement).
- `terms.html`: 18+ eligibility, UGC safety, anti-harassment, and community rules.
- `vercel.json`: Clean URL routing (`/privacy`, `/terms`, `/delete-account`).

## Deployment on Vercel

1. Push this repository to GitHub.
2. In [Vercel](https://vercel.com), click **Add New Project** and select this repo.
3. Keep default settings (Static HTML/No Build Framework needed).
4. Click **Deploy**.

## Google Play Console URLs

Once deployed to Vercel (e.g. `thaivibe.vercel.app`):
- **Privacy Policy URL**: `https://<your-project>.vercel.app/privacy`
- **Data Deletion URL**: `https://<your-project>.vercel.app/delete-account`
