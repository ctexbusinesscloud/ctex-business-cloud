# CTEX Business Cloud — MVP prototype

## What's included
- Responsive business SaaS landing/dashboard experience
- Overview dashboard with sample KPIs and revenue visualisation
- Product catalogue: add and search products
- Orders: create, search and update order statuses
- Customers: add and search customers
- Reports and workspace settings
- Browser-local persistence using localStorage

## Run locally
Open `index.html` in a modern browser. No build tools or paid services are required.

## Free static deployment (GitHub Pages)
1. Create/sign in to a GitHub account.
2. Create a **public** repository named `ctex-business-cloud`.
3. Upload `index.html` (and this README).
4. Open repository **Settings → Pages**.
5. Under Build and deployment, choose **Deploy from a branch**, select `main` and `/ (root)`, then Save.
6. GitHub will publish a URL similar to `https://YOUR-USERNAME.github.io/ctex-business-cloud/`.

GitHub Pages supports publishing static HTML, CSS and JavaScript from a repository. A custom domain is optional and usually costs money.

## Important limitations
This is a functional front-end prototype, not a production SaaS backend:
- Demo numbers and sample customers/orders are illustrative.
- Data is saved only in the current browser/device and can be cleared by the user.
- There is no authentication, server database, multi-tenant isolation, payment processing, email delivery, backup, or access control.
- Do not enter real customer, payment, or confidential business information.
- Before accepting real users, add secure authentication, a server-side database, authorization rules, validation, backups, privacy/terms pages, monitoring, and security testing.

## Product roadmap
1. Validate the problem with real retailers and interview potential users.
2. Implement secure accounts and isolated business workspaces.
3. Add server-side product, order, and customer data.
4. Add imports/exports, audit history, and reliable reports.
5. Pilot with real businesses and measure usage/retention.
6. Deploy backend services to a suitable cloud provider (Google Cloud is one option).

## Google for Startups Cloud Program
Eligibility is decided by Google and is not guaranteed by a website or prototype. Current official programme information:
https://cloud.google.com/startup
