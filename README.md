# Northstar Capital website starter

This is a responsive static website starter for a fictional investment advisory brand. It is not a bank, broker, licensed investment adviser, or a live financial product.

## Files
- `index.html` — complete responsive website, styles, and small interactions.

## Important before public launch
1. Replace the fictional brand name and placeholder contact details.
2. Confirm the company is legally permitted to offer any advertised financial services in its jurisdiction.
3. The contact form is a demo only and does not send or save data.
4. Do not collect client funds or sensitive financial data through this starter.
5. Add a secure backend and access controls before using any client dashboard.

## Deploy using Cloudflare Pages
- Create a GitHub repository and upload `index.html` at the repository root.
- In Cloudflare dashboard, go to Workers & Pages > Create application > Pages > Connect to Git.
- Select your GitHub repository.
- For a plain static HTML site, choose no framework; set build command to `exit 0` if required and output directory to `/` (the repository root).
- Deploy. Cloudflare should provide a `*.pages.dev` subdomain.
