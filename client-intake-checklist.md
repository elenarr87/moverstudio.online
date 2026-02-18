# MOVER Studio — Client Intake Checklist

| Scenario | Fit (Yes/No) | Key Indicator | Action | Qualifying question |
|---|---:|---|---|---|
| Local multi-location service (e.g., roadside assistance) | Yes | Needs many geo-targeted landing pages and phone conversions | Build static multi-location pages, add LocalBusiness schema, host on CDN, collect Lighthouse reports | "How many distinct service areas/locations do you need pages for?" |
| Small professional practice (dentist/lawyer/consultant) | Yes | Infrequent content changes; primary need is brochure + contact capture | Deliver static brochure site with serverless form integration and 30‑day edit SLA | "How often do you need to update services or staff profiles each month?" |
| Performance-sensitive paid campaign / landing page | Yes | Requires deterministic, minimal-load pages for ads/A-B testing | Build ultra-lean static landing pages, defer third-party tags, host on edge CDN | "Is peak page speed and predictable A/B performance critical for the campaign?" |
| Full e-commerce store with cart & accounts | No | Requires transactions, inventory sync, authenticated sessions | Recommend Shopify/BigCommerce or headless e‑commerce (API backend + storefront) | "Do you need on-site checkout, user accounts, or inventory sync with suppliers?" |
| Large editorial / multi-author site | No | High publishing velocity and editorial workflows with previews | Recommend managed CMS (WordPress with good hosting) or headless CMS with editorial tooling | "How many people publish or edit content daily, and do you need preview workflows?" |
| SaaS or web app with dashboards/real-time data | No | Needs authenticated APIs, server logic, and real-time features | Build full-stack app (serverless/APIs or traditional backend) and keep marketing site static | "Does your product require authenticated dashboards, personalized data, or real-time updates?" |

*Usage:* Print this page and use during sales calls. Tick the "Key Indicator" column quickly to qualify leads; follow the recommended Action if fit = No.
