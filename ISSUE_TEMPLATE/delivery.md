---
name: 🚀 Delivery / Deployment
about: For deploying changes to a live or staging environment.
title: "[DELIVERY] - "
labels: 'deployment'
assignees: ''

---

### What is being deployed?
A brief summary of the changes being released in this deployment. This can be a link to a pull request or a list of completed issue numbers (e.g., "Deploys feature #42 and fixes bug #51").

### Target Environment
- [ ] Staging / Preview
- [ ] Production / Live

### Pre-Deployment Checklist
This checklist must be completed **before** starting the deployment.
- [ ] All related pull requests have been reviewed, approved, and merged.
- [ ] The `main` (or `develop`) branch is up to date with the latest changes.
- [ ] All environment variables have been confirmed and are in place.
- [ ] A database backup has been created (if applicable).
- [ ] The client has been notified of the scheduled maintenance/deployment window.

### Post-Deployment Checklist
This checklist must be completed **after** a successful deployment.
- [ ] Deployment script/pipeline completed without errors.
- [ ] Perform a smoke test on key pages and functionality (e.g., Homepage, Contact Form, Checkout Process).
- [ ] Clear all relevant caches (e.g., Cloudflare, Vercel, server-side).
- [ ] Notify the client that the deployment is complete and the site is ready for their review.