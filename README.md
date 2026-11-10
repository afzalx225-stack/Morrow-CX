# MorrowCX PWA Starter

This is the first **frontend prototype** for MorrowCX Support Desk.

## Included
- Responsive PWA shell with install manifest and offline app-shell caching
- Overview, inbox, customers, knowledge base, follow-ups, reports and settings screens
- Demo enquiry creation and FAQ creation (in-memory only)
- Mobile navigation

## Important status
This is **not production-ready**. It uses sample/demo data held only in browser memory. It has no authentication, database, tenant isolation, live AI, email/WhatsApp connection, website chat embed, billing, or server-side persistence. Do not enter real customer information.

## Run locally
Serve this folder from any static web host. For example, GitHub Pages or Render Static Site can host the frontend. A service worker requires HTTPS (or localhost).

## Next engineering stage
1. Create a dedicated GitHub repository for MorrowCX and upload this starter.
2. Deploy the static PWA to Render (Singapore region if available).
3. Create Supabase project in Mumbai and implement authentication + database.
4. Add row-level security and test tenant isolation before storing customer data.
5. Build secure server-side AI gateway, then the website chat widget and human handover.
6. Add email integrations and payment subscriptions only after core workflows pass testing.

## Brand
MorrowCX — Better customer experiences. Less business workload.
